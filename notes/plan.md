# HKICPA QP AI Tutor — plan.md（執行藍圖）
Last updated: 2026-10-16 (HKT) | Exam: 2027-05-20 (D-216)

## Mission
Senior AI Tutor for HKICPA QP Associate Level（M6 / M8 / M10），基於 v2.0 prompt（M7+M9 實戰驗證版）。
- M6 Financial Accounting
- M8 Assurance（官方名稱 Principles of Auditing）
- M10 Business & Company Law

## 考試形式（已查證，待用戶確認）
Source: HKEAA QP June 2026 timetable + HKICPA Learning Pack 文本
- M6 Financial Accounting：Computer-based examination，2.5 小時，closed-book
- M8 Principles of Auditing：Computer-based examination，2.5 小時，closed-book
- M10 Business and Company Law：3 小時，HK 考場 BYOD，**open-book**（Associate 1–10 中唯一開卷）
- 官方 past paper：留返考前約 10 日（約 2027-05-10 起）先做

## Persistent State Files（single source of truth，新對話 upload 呢三份即可無縫接上）
| File | Purpose |
|---|---|
| `QP_Error_Log_錯題本.md` | 錯因圖例、三科錯題明細、Active Retest Queue、Errata、Spaced Repetition log |
| `QP_Progress_Tracker.md` | 整體狀態、每科 Master List、每週進度、Mock 紀錄、里程碑 |
| `QP_Exam_Vocab_急救詞彙表.md` | 每章術語 + Model Sentences（考試可直接搬用句式） |

## Workflow per chapter（用戶 upload Learning Pack chapter 後）
- Stage 1（Phase 1 速查表）：3–5 個學習目標 + 必背考點 + 2 個易混淆概念對比
  - M6：recognition / measurement / disclosure + journal entries
  - M8：assertions / procedures / evidence / ethics / report modifications
  - M10：Ordinances + leading cases + IRAC
- Stage 2（Phase 2 閃卡）：8 張雙語卡——Front 英文問題；Back 英文 point-form + 中文白話
- Stage 3（Phase 3 Quiz）：全英文 5 題 OTQ（MCQ + 計算/簡答），closed-book 限時 15 分鐘；Quiz 同 Answers 分開兩檔；Answers 每題附 English model answer + 繁中解題思路
- Stage 4（Phase 4 批改，用戶提交後）：
  1. 逐題對錯 + 分數 X/5
  2. Rule Check——準則/條文/case/journal entries 要精確，編號寫錯都捉
  3. 繁中錯因分析 + 一段全英文 Model Sentence 背誦
  4. 重複犯錯 → 罰抄/默寫處方（2nd strike 加倍）
  5. 即場更新 Error Log + Active Retest Queue + Tracker + Vocab
  6. 即出另一科（最近最少郁嘅）保溫卷：5 題 OTQ、限時 6 分鐘，抽自已清除錯題 + 輪轉考點；保溫卷錯題重返隊列

## Active Retest Queue 機制
- 答錯 → 下份 quiz 開 Retest Section（新場景、同理論）
- 編號 R1, R2… 連續唔重用；答啱剔除；答錯帶落
- 同一弱點再錯 = 2nd strike，處方加倍

## Mock 階段（該科全部章節完成後）
- 20 題 OTQ，計時 60 分鐘，closed-book；歷史錯題重點回測
- 錯題注入下一份 Mock 直至清零
- 評分：16–20 = exam-ready；12–15 = 有暗瘡；≤11 = 分章重溫

## Rules of Engagement
- 所有 quiz 計時 + closed-book，超時如實申報；提交格式從簡，貼完即改
- 語言政策：對話/解釋 = 繁體中文；術語、HKAS/HKFRS、audit assertions、Ordinances、leading cases、所有題目與標準答案 = 全英文
- 每個回覆開頭：HKT 日期時間 + 考試倒數
- 教學風格：客觀、批判性、唔冧人；答錯直講；進度落後照直講
- 用戶質疑答案卡 → 必須重新驗證；確認係 Tutor 錯 → 認錯 + 記入 Errata，唔准硬拗

## Open Items
- [x] 考試格式校準已確認（2026-10-16）：跟真實格式——M10 前期 closed-book 操練，後期加 open-book 應試策略（條文檢索速度、bookmark 技巧）
- [x] 用戶 upload M6 Chapter 1 Learning Pack → 即出 Phase 1–3（開局科目已定：M6）— 2026-10-16 用戶確認全部資料已喺 /mnt/agents/upload/（三科 4th ed LP + past papers + panelist reports），改為**一次過生成三科全章節**

---

## 全章節生成工程（2026-10-16 啟動）
**範圍**：M6 25 章 + M8 10 章 + M10 13 章 = 48 章；每章 3 檔（Phase1-2 速查表+閃卡、Phase3_Quiz、Phase3_Answers），合共 144 檔 + 每科 00_INDEX。

**Stage 0 — 準備（Orchestrator）**：LP 切章完成 → `_lp_text/{mod}/ch{nn}.txt`；輸出目錄 `HKICPA_QP/{mod}/Ch{nn}/`。
**Stage 1 — Exam Lens（3 個 intel sub-agents 並行）**：分析 past papers + panelists' reports → `_exam_lens/Exam_Lens_{M6,M8,M10}.md`（題型風格、常考主題、考生常犯弱點、難度校準）。**禁止抄 past paper 題目**——past papers 留返學生考前 10 日操。
**Stage 2 — 章節生成（qp_chapter_writer，每章 1 個 sub-agent，8 個一波）**：讀 chapter 文本 + Exam Lens → 寫 3 檔。
**Stage 3 — 質檢**：✅ 2026-10-16 全量機械驗證通過（144 檔、240 題、384 閃卡、每題 Rule Check、Quiz 零洩題、closed-book header 齊）。
**Stage 4 — 整合**：✅ Tracker Master Lists 已填 48 章、每科 00_INDEX.md 已建、已交付。

**檔名規格**：`{MOD}_Ch{NN}_Phase1-2.md`、`{MOD}_Ch{NN}_Phase3_Quiz.md`、`{MOD}_Ch{NN}_Phase3_Answers.md`
