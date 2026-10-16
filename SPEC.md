# SPEC.md — GitHub 網站同步規格（每個新對話開始必讀）

> ⚠️ 本檔係 M6/M8/M10 筆記「自動上網」流程嘅唯一規格書。任何新對話要郁筆記／網站，**先讀晒呢份先好郁手**。

## 1. 基本資料

| 項目 | 值 |
|---|---|
| GitHub 用戶 | `holaming111317-collab` |
| Repo | `qp-study-plan-M6-8-10-`（public，default branch `main`） |
| Pages URL | https://holaming111317-collab.github.io/qp-study-plan-M6-8-10-/ |
| Pages 來源 | Deploy from branch `main` / (root) |
| Token 位置 | `/mnt/agents/output/.gh_token`（PAT，scope: `repo` + `workflow`） |
| 筆記根目錄 | `/mnt/agents/output/HKICPA_QP/` |
| 網站 scaffold | `/mnt/agents/output/HKICPA_QP/site/`（build.py + .github/workflows/rebuild.yml） |
| 考試日 | 2027-05-20（M6 + M8 + M10 同日） |

## 2. 架構（点样運作）

1. 筆記 `.md` 放喺 `HKICPA_QP/`（M6/ M8/ M10/ _exam_lens/ + 狀態檔）。
2. 推送上 repo 時**每個 .md 都要雙路徑**：repo 根目錄一份（GitHub 網頁瀏覽用）+ `notes/` 一份（workflow 監聽 `notes/**`，rebuild 嘅來源）。
3. Push 到 `notes/**` 或 `build.py` → GitHub Actions（`.github/workflows/rebuild.yml`）自動行 `HKICPA_SRC=notes python3 build.py` → 產生 `pages/`、`index.html`、`assets/` → bot commit（`[skip ci]`）。
4. GitHub Pages 由 `main` root serve `index.html`。
5. `assets/config.js` 記住 GitHub user + repo 名（「在 GitHub 編輯」按鈕用）。build.py 重建時會保留已存在嘅 config.js，**唔會**覆寫。

### build.py 本地用法
```bash
cd /mnt/agents/output/HKICPA_QP/site && python3 build.py
# SRC_DIR 預設 = site/ 嘅上層 = HKICPA_QP/；輸出喺 site/ 入面（pages/ index.html assets/ notes/）
```

## 3. 推送程序（Part C 常規同步——每次更新筆記後必做）

用 **Git Data API**（唔好用 Contents API——批量檔案會爆 rate limit）：

1. `GET /repos/{owner}/{repo}/git/ref/heads/main` → 攞而家 commit sha
2. `GET /repos/{owner}/{repo}/git/commits/{sha}` → 攞 `base_tree`
3. 每個檔案 `POST /git/blobs`（`content` = base64，`encoding` = "base64"）→ 攞 blob sha
4. `POST /git/trees`（`base_tree` + 全部 entries：`path`/`mode:100644`/`type:blob`/`sha`）
5. `POST /git/commits`（`message` + `tree` + `parents:[舊sha]`）
6. `PATCH /git/refs/heads/main`（`sha` = 新 commit）

**Retry 規則**：任何一步失敗（SSL / RemoteDisconnected / HTTP 5xx / 403 / 429），sleep `5 × attempt` 秒後重試，最多 3 次。唔准假設成功。

**現成腳本**：`/tmp/gh_push.py`（首次推送用嗰隻；新對話如 /tmp 已清，按上面步驟重寫一隻——邏輯簡單，照 SPEC 抄得返）。

## 4. 驗證程序（推送後必做）

1. 等 **~170 秒**（Actions build ~1–2 分鐘 + Pages deploy ~1 分鐘）。
2. Cache-bust 驗證：
   ```bash
   curl -s "https://holaming111317-collab.github.io/qp-study-plan-M6-8-10-/?v=$(date +%s)" | grep -o "Module 6 Financial Accounting"
   curl -s "https://holaming111317-collab.github.io/qp-study-plan-M6-8-10-/pages/m6-ch01-phase1-2.html?v=$(date +%s)" | grep -c 'class="fcard"'   # 預期 > 0
   curl -s "https://holaming111317-collab.github.io/qp-study-plan-M6-8-10-/assets/config.js?v=$(date +%s)"
   ```
3. 檢查 Actions run 狀態：
   ```bash
   curl -s -H "Authorization: token $(cat /mnt/agents/output/.gh_token)" \
     "https://api.github.com/repos/holaming111317-collab/qp-study-plan-M6-8-10-/actions/runs?per_page=1" \
     | python3 -c "import json,sys; r=json.load(sys.stdin)['workflow_runs'][0]; print(r['status'], r['conclusion'])"
   ```
4. 向用戶報告 **commit hash** + 驗證結果。驗證唔到就再推一次，**唔准假設成功**。

## 5. build.py 改裝要點（M7/M9 → M6/M8/M10 已做嘅嘢）

- `categorize()` regex：`r"(M(?:6|8|10))_Ch(\d+)"`；`MODULE_WEEK = {"M6": M6_WEEK, "M8": M8_WEEK, "M10": M10_WEEK}`
- **31 週計劃**（2026/10/16 → 2027/5/20）：M6（25 章）W1–13 → M10（13 章）W14–20 → M8（10 章）W21–25，每週 2 章；W26–28 Mock；W29–31 past papers + 衝刺
- `TYPE_ORDER = {"Phase1-2": 0, "Quiz": 1, "Answers": 2}`（對應我哋嘅檔名 `M6_ChNN_Phase1-2.md` / `_Phase3_Quiz.md` / `_Phase3_Answers.md`）
- Badge：m6（藍灰）/ m8（鼠尾草綠）/ m10（塵玫瑰）；hero/tagline 已改三科名 + 考試日
- **閃卡 input 適配**：我哋 Phase 2 用 `### Card N` + `**Front:**` + `**Back:**` 寫法；`_rewrite_card_blocks()` 喺 markdown 層面將佢改寫成翻卡引擎識得嘅 `[Flashcard N]` bullet 格式（兼容 `- **Front:**` bullet 變體，e.g. M6 Ch18）。**渲染引擎（transform_flashcards）本身冇郁過**
- CSS 加咗 `.fcard-a code { white-space: pre-wrap; }`——卡背 journal entry fence 喺 list 入面只能渲染做 inline `<code>`，靠呢條 rule 保留換行對齊
- `assets/config.js` 有兩個變數：`HKICPA_GITHUB_USER` + `HKICPA_GITHUB_REPO`

## 6. 常見故障

| 症狀 | 原因 | 解法 |
|---|---|---|
| Push 後 Pages 404 | Actions 未行完／未成功 | 查 Actions run；首次推送後要等够 170s |
| 閃卡唔翻 / 原樣顯示 bullet | 新筆記嘅 Card 格式唔啱（`### Card N` 後必須 `**Front:**` 一行 + `**Back:**`） | 改筆記格式；`_rewrite_card_blocks` 對唔啱格式係 no-op |
| 表格變原碼 | 表格前冇空行 | build.py 有 `_ensure_blank_line_before_tables`，正常唔會發生；如發生檢查該表係咪喺特殊巢狀入面 |
| 「在 GitHub 編輯」404 | config.js 嘅 user/repo 名錯 | 改 `assets/config.js` 後重新推送（Actions 會保留佢） |
| 時鐘漂移導致驗證混亂 | sandbox clock 唔準 | 用 `TZ=Asia/Hong_Kong date`，同 `curl -sI https://api.github.com \| grep -i date` 對錶 |
| Token 失效（401） | PAT 過期／被 revoke | 叫用戶開新 PAT（`repo` + `workflow` scope），寫返入 `/mnt/agents/output/.gh_token` |

## 7. 保安

- Token **只**放 `/mnt/agents/output/.gh_token`，**絕對唔准** commit 入 repo（佢喺筆記根目錄之外，正常掃描唔會掂到佢）。
- 用戶已獲提醒：對話完結後去 GitHub Settings → Developer settings → revoke / rotate 個 PAT。
- `_lp_text/`（LP 原文節錄）**唔推送**（版權 + 體積）——推送清單只包 `.md`。
