# M6 Chapter 23: Preparation of Consolidated Financial Statements — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives

1. **Explain** why a parent must present consolidated financial statements and apply the single economic entity concept under HKFRS 10.
2. **Apply** the consolidation procedures (HKFRS 10 Appendix B) to combine a parent and its subsidiary line-by-line on a consolidation worksheet.
3. **Prepare** pro forma consolidation adjustment journal entries for fair value adjustments, pre-acquisition equity elimination, intra-group balances/transactions and unrealised profits/losses.
4. **Calculate** goodwill, the NCI share of consolidated profit or loss, and the NCI share of consolidated equity, distinguishing upstream from downstream transactions.
5. **Identify** the presentation and disclosure requirements of HKAS 1, HKFRS 12, HKAS 24 and Schedule 4 of the Companies Ordinance (Cap. 622) for consolidated financial statements.

### 必背考點

#### A. Recognition — 邊個要 consolidate、由幾時開始

- **HKFRS 10 paras 4, 4B**: a parent that controls one or more subsidiaries **must present consolidated financial statements** — assets, liabilities, equity, income, expenses and cash flows of parent + subsidiaries presented as those of a **single economic entity**. Limited exemptions (e.g. certain intermediate parents, investment entities); s.379(3) of the Companies Ordinance (Cap. 622) also provides limited relief.
- 考點：考試鍾意考「持股 < 50% 係咪一定唔使 consolidate？」——**No**。Consolidation turns on **control**, not the percentage. Consolidation begins when control is **gained** and ceases only when control is **lost** (HKFRS 10 paras 25, B98–B99).
- **Line-by-line consolidation**: recognise 100% of the subsidiary's assets/liabilities even if the parent owns less than 100% — because control gives the parent power over **all** the assets and liabilities. NCI exists only to attribute the slice of equity/results not belonging to owners of the parent (HKFRS 10 paras 22, B94).
- **Loss of control (HKFRS 10 paras 25, B98–B99)**: derecognise the former subsidiary's assets, liabilities, goodwill and NCI; recycle related OCI; recognise the **gain/loss in profit or loss**; consolidate income/expenses **up to the date control is lost**. Any retained interest is re-measured at fair value and accounted for as an associate (HKAS 28), joint venture (HKFRS 11) or financial asset (HKFRS 9).
- **Partial disposal WITHOUT loss of control (HKFRS 10 paras 23, B96)**: **no gain or loss in profit or loss**; treat as an **equity transaction** (transaction with owners as owners) — adjust NCI and recognise any difference directly in equity. Goodwill is NOT re-measured.

#### B. Measurement — consolidation procedures 與調整

**統一基礎（開始 consolidate 前必做）**
- **Same reporting date** (HKFRS 10 paras B92–B93): subsidiary's reporting date may differ by **no more than three months**; Cap. 622 s.367(4) requires subsidiary's financial year to coincide with the parent's unless the parent's directors have good reasons against it.
- **Uniform accounting policies** (HKFRS 10 paras 19, B87): adjust the subsidiary's figures to group policies in the consolidation worksheet.

**Consolidation procedures (HKFRS 10 para. B86)** — 三大步：
1. Combine (add across) like items of assets, liabilities, equity, income, expenses and cash flows;
2. **Eliminate the parent's investment in each subsidiary against the subsidiary's pre-acquisition equity** — difference = goodwill (Dr) or gain from bargain purchase (Cr);
3. **Eliminate in full** intra-group assets, liabilities, equity, income, expenses and cash flows (HKFRS 10 para. B86(c)).

**Consolidation worksheet / pro forma journal entries**
- Adjustment JEs are recorded **only in the consolidation worksheet**; they are **never posted to any entity's ledger** (the group has no ledger of its own) and therefore **do not carry forward — must be re-posted ("refreshed") every period**. 考試伏位：舊年嘅調整今年要重新做，仲要分開 opening retained earnings 部分。

**Fair value adjustments on acquisition (HKFRS 3 (Revised))**
- Write back accumulated depreciation/amortisation/impairment of the acquired assets, then restate to **fair value**; recognise previously unrecognised identifiable assets (e.g. brand name). Credit side goes to a temporary equity account — **Business combinations reserve**.
- **Subsequent periods**: extra depreciation/amortisation on the FV uplift must be charged each period (current year to Depreciation expense; prior years to opening Retained earnings). If the remeasured asset is later sold, the **group's gain/loss is computed on the group carrying amount** (FV-based), not the subsidiary's book gain.

**Pre-acquisition equity elimination（每期都要重做）**

```
DR Share capital (subsidiary, 100% at acquisition date)          X
DR Retained earnings (subsidiary, pre-acquisition)               X
DR Reserves (subsidiary, pre-acquisition)                        X
DR Business combinations reserve (FV adjustments)                X
DR Goodwill (balancing figure)                                   X
    CR Investment in subsidiary                                     X
    CR Non-controlling interests — equity (if partly owned)         X
```
（Bargain purchase → CR Gain from bargain purchase instead of DR Goodwill.）

**Goodwill（HKFRS 3 (Revised) acquisition method）**

```
Consideration transferred
+ NCI at acquisition (fair value [full goodwill] OR proportionate share of recognised net assets [partial goodwill])
− HKFRS 3 recognised amounts of identifiable net assets (at fair value)
= Goodwill (or gain from bargain purchase if negative)
```
- Acquisition-related costs (e.g. due diligence fees) are **expensed**, NOT added to consideration.

**Intra-group adjustments（全部 eliminate in full）**

| Transaction | Pro forma consolidation adjustment JE |
|---|---|
| Cash-in-transit | DR Cash / CR Receivables（當收款方已收） |
| Intra-group loan | DR Loan payable / CR Loan receivable；DR Interest income / CR Interest expense（本期）；DR Interest payable / CR Interest receivable |
| Intra-group services | DR Management fee revenue / CR Management fee expense；DR Payables / CR Receivables（**淨利潤冇影響，但都要 eliminate**，否則 revenue/expense 各自 overstated，誤導使用者） |
| Intra-group inventory sale | DR Sales revenue / CR Cost of sales（full intra-group sale value）；再 DR Cost of sales / CR Inventory（**只限 year-end 未售出部分嘅 unrealised profit**） |
| Unrealised profit in **opening** inventory（翌年重做） | DR Retained earnings / CR Cost of sales |
| Intra-group sale of non-current asset | (1) DR PPE / CR Accumulated depreciation（還原售出前累計折舊）；(2) DR Retained earnings (gain on sale) / CR PPE（消除 unrealised gain）；(3) DR Accumulated depreciation / CR Depreciation expense（本期）+ CR Retained earnings（前期）— 把折舊還原到「冇賣過」嘅水平，gain 透過 excess depreciation 逐步 realised |
| Intra-group dividend | DR Dividend income / CR Retained earnings — dividend（**只限 parent 份額**）；DR Dividend payable / CR Dividend receivable；NCI 份額：DR NCI — equity / CR Retained earnings — dividend |

**NCI measurement（本章核心計算）**
- **NCI share of profit or loss** = NCI% × subsidiary's reported profit for the period **adjusted for consolidation adjustments that affect consolidated net assets**（LP §23.3.1.3）:
  - 額外折舊/攤銷（acquisition FV uplift）→ 扣
  - **Upstream** unrealised profit（subsidiary 係賣方）→ 扣 subsidiary profit（NCI 要分擔）
  - **Downstream** unrealised profit（parent 係賣方）→ **唔郁** subsidiary profit（NCI 唔使分擔）
  - Intra-group loans/services（equal amounts）→ 唔影響 net assets → 唔使調整
- **NCI share of consolidated equity at reporting date** = NCI at acquisition + NCI% × (subsidiary's post-acquisition movements in equity, adjusted for net-asset-affecting consolidation adjustments, net of dividends)
- Attribution JEs: DR Retained earnings (opening, prior periods' share) / CR NCI — equity；DR Profit attributable to NCI (P/L) / CR NCI — equity；DR NCI — equity / CR Retained earnings — dividend（NCI dividend share）。

#### C. Disclosure — presentation 與披露要求

- **Complete set of consolidated FS** (HKAS 1 para. 10): consolidated SFP, SPLOCI, SOCIE, statement of cash flows + notes, with comparatives.
- **On the face**:
  - SFP: NCI presented **within equity**, separately from equity attributable to owners of the parent (HKAS 1 para. 54(q); HKFRS 10 para. 22) — single line item, no need to split into "share capital — NCI" etc.
  - SPLOCI: profit or loss attributable to NCI vs owners of the parent presented separately (HKAS 1 para. 81B); same split for total comprehensive income.
  - SOCIE: comprehensive income attributable to NCI shown separately (HKAS 1 para. 106(a)).
- **HKFRS 12 Disclosure of Interests in Other Entities**: disclose significant judgements in determining control (HKFRS 12 paras 7, 10); composition of the group; nature/extent of significant restrictions on accessing group assets/settling liabilities; consequences of changes in ownership interest and of losing control; summarised financial information for each **material non-wholly owned subsidiary** (HKFRS 12 paras 12, B10(b)); unconsolidated structured entities (HKFRS 12 paras 19A–19G); profit/OCI attributable to NCI and dividends paid to NCI (HKFRS 12 paras 12(e), 12(f)).
- **Schedule 4, Part 1, para. 2 of Cap. 622**: the notes to the consolidated FS must include the **parent's company-level statement of financial position** (with a single "investment in subsidiaries" line) and **movements in the parent's company-level reserves**. HKFRSs themselves do NOT require the parent to prepare separate company-level FS.
- **HKAS 24 para. 13**: disclose relationships between parent and subsidiaries (even if there were no transactions).

### 易混淆概念對比

**Table 1: Upstream vs Downstream intra-group transactions**

| | Upstream (Subsidiary → Parent) | Downstream (Parent → Subsidiary) |
|---|---|---|
| Seller / profit earner | Subsidiary records the profit | Parent records the profit |
| Elimination JE | Same — eliminate in full either way (HKFRS 10 para. B86(c)) | Same |
| Effect on NCI share of profit | **Yes** — subsidiary's reported profit must be reduced by unrealised profit (and increased by realisation via excess depreciation); NCI bears its % | **No** — no profit earned by the subsidiary, so NCI calculation is unaffected |
| 點樣分辨 | 問「邊個記低咗個 profit？」— profit 喺 subsidiary 簿度 → upstream | profit 喺 parent 簿度 → downstream |
| 考試伏位 | Panel reports 連續幾年話考生將 downstream unrealised profit 錯誤分攤畀 NCI（Jun 2025 Q1 就係咁）；相反 upstream 又唔記得調。記住：**NCI 只分擔 subsidiary 自己賺嗰啲** | 同左 |

**Table 2: Loss of control vs Partial disposal without loss of control**

| | Loss of control (HKFRS 10 paras 25, B98–B99) | Partial disposal, control retained (HKFRS 10 paras 23, B96) |
|---|---|---|
| Consolidation | Ceases from the date control is lost; consolidate results up to that date | Continues unchanged |
| Gain/loss | Recognised in **profit or loss** | **No gain/loss in P&L** — equity transaction |
| NCI / equity | Derecognise NCI of former subsidiary | Adjust NCI carrying amount; difference between consideration and NCI adjustment goes **directly to parent's equity** |
| Goodwill | Derecognised in full | **Not** re-measured |
| Remaining interest | Re-measured at fair value; becomes associate (HKAS 28) / JV (HKFRS 11) / financial asset (HKFRS 9) | N/A (still consolidating) |
| 點樣分辨 | 唯一問題係「仲有冇 control？」——唔係睇持股跌唔跌穿 50% | 持股降但 control 仍在 → 全部入 equity |
| 考試伏位 | 以為賣咗部分持股就一定入 P&L；或者 <50% 就自動當失去 control（可以 de facto control） | 錯誤將差額入 P&L，或者重計 goodwill |

## Phase 2 閃卡

### Card 1
**Front:** Why must intra-group income and expense line items that fully offset each other (e.g. intra-group interest income/expense, management fees) still be eliminated on consolidation?

**Back:**
- Net profit is unaffected, BUT individual line items (e.g. revenue, expenses) would be **overstated**.
- Overstated line items give **misleading information** — revenue may be a key performance indicator for users.
- Consolidation presents the group as a **single economic entity**; an entity cannot trade with itself (HKFRS 10 para. B86(c)).

💬 白話：雖然一加一減淨利潤冇變，但條 revenue 同 expense 線會各自谷大咗，報表使用者睇落集團生意額大過實際。所以就算「冇 net effect」都一樣要對銷——呢點係考生常見扣分位。

### Card 2
**Front:** Why must consolidation adjustment journal entries be re-posted ("refreshed") every reporting period, and where are they recorded?

**Back:**
- They are **pro forma** entries recorded **only in the consolidation worksheet**.
- The group itself keeps **no ledger**; entries are never posted to any entity's books.
- The worksheet **starts afresh each period** → prior-period adjustments (e.g. FV uplift, unrealised profit in opening inventory) must be re-entered, with the prior-year portion taken to **opening retained earnings**.

💬 白話：集團本身冇自己嘅帳簿，啲調整分錄只係 worksheet 上面做，所以每年開新 worksheet 就要由頭做返晒，上年嗰啲要改用 opening retained earnings 落。

### Card 3
**Front:** State the pro forma consolidation adjustment journal entry for the pre-acquisition equity elimination of a partly owned subsidiary (with goodwill).

**Back:**
- DR Share capital (subsidiary, 100% at acquisition date)
- DR Retained earnings (pre-acquisition)
- DR Reserves (pre-acquisition)
- DR Business combinations reserve (FV adjustments)
- DR Goodwill (balancing figure)
- CR Investment in subsidiary
- CR Non-controlling interests — equity
- (Bargain purchase → CR Gain from bargain purchase instead of DR Goodwill)

💬 白話：母公司簿入面嘅「Investment in subsidiary」同子公司收購前嘅 equity 屬於「集團成立之前」嘅嘢，要成條對銷；差額就係 goodwill，NCI 嗰份就 credit 去 NCI — equity。呢條 entry 每期都要重做。

### Card 4
**Front:** An intra-group sale of inventory took place during the year and part of the inventory remains on hand at the reporting date. Give the consolidation adjustment entries and the follow-up entry next year if the inventory is then sold externally.

**Back:**
- Year of sale: DR Sales revenue / CR Cost of sales (full intra-group sale value); DR Cost of sales / CR Inventory (**unrealised profit on unsold portion only**).
- Following year (if sold externally): DR Retained earnings / CR Cost of sales (unrealised profit in opening inventory).
- Only the portion relating to inventory **still on hand** is eliminated; the on-sold portion is realised by the group.

💬 白話：存貨未賣出集團之外，利潤就係「unrealised」，要壓低返存貨值同利潤；下年賣出咗，就用 opening retained earnings 對 COGS，等利潤落返啱嘅年度。

### Card 5
**Front:** How is the NCI's share of a partly owned subsidiary's profit or loss measured when intra-group transactions exist?

**Back:**
- NCI% × subsidiary's **reported** profit, **adjusted only for consolidation adjustments that change consolidated net assets**:
  - less extra depreciation/amortisation on acquisition FV uplift;
  - less unrealised profit on **upstream** sales (subsidiary is the seller);
  - plus realisation of upstream unrealised gains via excess depreciation;
  - **no adjustment** for downstream sales, intra-group loans or services (equal amounts).
- Then attribute: DR Profit attributable to NCI (P/L) / CR NCI — equity.

💬 白話：口訣——「跟錢走」。只有影響集團淨資產嘅調整先會動到 NCI；同埋只有子公司自己賺嘅（upstream）利潤先關 NCI 事，母公司賺嘅（downstream）唔使分畀 NCI。

### Card 6
**Front:** What alignment of reporting dates and accounting policies is required before combining the parent and subsidiary financial statements, and what are the limits?

**Back:**
- **Same reporting date**: if impracticable, subsidiary's date may differ by **no more than three months**, consistently applied (HKFRS 10 paras B92–B93). Cap. 622 s.367(4) requires subsidiary's financial year to coincide with the parent's unless the parent's directors have good reasons otherwise.
- **Uniform accounting policies**: adjust subsidiary's figures to group policies via consolidation adjustments (HKFRS 10 paras 19, B87).

💬 白話：「Apples with apples」——同期、同 policy 先可以加埋一齊。考試見到唔同年結日，記住上限三個月。

### Card 7
**Front:** A parent sells part of its interest in a subsidiary but retains control. How is the transaction accounted for under HKFRS 10?

**Back:**
- Continue to consolidate; **no gain or loss in profit or loss** (HKFRS 10 paras 23, B96).
- Treated as an **equity transaction** (transaction with owners as owners): adjust the carrying amount of NCI; any difference between the consideration and the NCI adjustment is recognised **directly in the parent's equity**.
- Goodwill is **not** re-measured; acquisition-date accounting is unchanged.

💬 白話：一日仲 control 住，就一日當係「同自己股東做交易」，所有差額落 equity，唔准碰 P&L。一旦失去 control 先至計 gain/loss 入 P&L。

### Card 8
**Front:** List the NCI-related items that must appear on the face of the consolidated financial statements, and the parent-level disclosure required by the Companies Ordinance (Cap. 622).

**Back:**
- SFP: NCI within equity, separate from owners of the parent (HKAS 1 para. 54(q); HKFRS 10 para. 22).
- SPLOCI: profit/loss and total comprehensive income split between owners of the parent and NCI (HKAS 1 para. 81B).
- SOCIE: comprehensive income attributable to NCI separately (HKAS 1 para. 106(a)).
- Cap. 622 Schedule 4, Part 1, para. 2: notes must include the **parent's company-level SFP** (single "investment in subsidiaries" line) and **movements in the parent's reserves**.
- HKFRS 12: summarised financial information for each material non-wholly owned subsidiary (paras 12, B10(b)).

💬 白話：NCI 係 equity 入面一條獨立線，P&L 要拆「歸母公司 / 歸 NCI」。另外香港公司法要求集團帳附註埋母公司自己嘅 SFP——呢啲 disclosure 題考生成日留白，係易攞分位。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Consolidation worksheet | 合併工作底稿，將母子公司報表逐行加總再做調整嘅工具；唔係正式帳簿 | Consolidation adjustment journal entries are recorded in the consolidation worksheet and are not posted to any entity's ledger. |
| Pro forma journal entry | 「模擬」調整分錄，只存在於 worksheet，每年要重做 | The pro forma journal entry eliminates the parent's investment in the subsidiary against the subsidiary's pre-acquisition equity. |
| Pre-acquisition equity | 子公司喺被收購日之前累積嘅權益，唔屬於集團，要對銷 | Pre-acquisition profits relate to periods before the group came into existence and are eliminated on consolidation. |
| Business combinations reserve | Worksheet 上面暫記 FV 調整嘅臨時 equity 戶口 | The fair value uplift on the subsidiary's plant was credited to the business combinations reserve. |
| Unrealised profit | 集團內部交易產生、但貨未賣畀外人嘅利潤，要消除 | The unrealised profit on the intra-group sale was eliminated against the carrying amount of inventory still on hand. |
| Upstream / Downstream transaction | Upstream = 子公司賣畀母公司；downstream = 母公司賣畀子公司；決定 NCI 使唔使分擔 unrealised profit | Because the sale was downstream, the unrealised profit adjustment did not affect the NCI's share of profit. |
| Non-controlling interest (NCI) | 子公司權益中唔屬於母公司嗰份，喺 consolidated SFP 嘅 equity 內獨立呈列 | Non-controlling interests are presented within equity, separately from the equity attributable to owners of the parent. |
| Loss of control | 母公司失去對子公司嘅控制，由嗰日起停止合併，盈虧入 P&L | On loss of control, the parent derecognises the subsidiary's assets, liabilities and NCI and recognises the gain or loss in profit or loss. |
