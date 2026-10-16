# M8 Chapter 4: Audit Planning II — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. Explain the audit risk model (AR = IR × CR × DR) and analyse the relationship between business risk, inherent risk, control risk and detection risk in determining the audit approach.
2. Apply materiality and performance materiality (HKSA 320), using quantitative benchmarks and qualitative factors, to plan and evaluate audit work.
3. Distinguish between tests of controls and substantive procedures (tests of detail and substantive analytical procedures) and select an appropriate combined or substantive audit approach.
4. Apply analytical procedures (HKSA 520) at the planning, substantive and final review stages, including ratio, trend and common-size analysis.
5. Evaluate the factors affecting the persuasiveness of audit evidence (HKSA 500/505/580) and the requirements for using the work of experts (HKSA 620) and internal auditors (HKSA 610 (Revised 2013)).

### 必背考點

#### A. Audit Risk & Assertions（風險模型 + 斷言）

**Audit Risk Model**
- **Audit risk** = risk that the auditor expresses an incorrect opinion on the financial statements. HKSAs require a **risk-based approach**; auditors cannot check every transaction.
- **AR = IR × CR × DR**（量化時用乘數：如 AR 10%, IR 70%, CR 70% → DR = 10% ÷ 49% = **20.4%**）
- **Inherent risk** (HKSA 200.13(n)(i)): susceptibility of an assertion to a misstatement that could be material, **before consideration of any related controls**. 例：complex standards (HKFRS 9 forward contracts)、fast-obsolescing inventory (HKAS 2 lower of cost and NRV)、estimates with high estimation uncertainty（可能是 significant risk，屬 inherent risk spectrum 高端）.
- **Control risk** (HKSA 200.13(n)(ii)): risk that a misstatement that could be material will **not be prevented, or detected and corrected, on a timely basis by the entity's controls**. 受管理層對內控嘅態度、control environment、員工能力影響。
- **Detection risk** (HKSA 200.13(e)): risk that the auditor's procedures will not detect a material misstatement that exists. **唯一受 auditor 控制嘅風險**；= sampling risk + non-sampling risk。
- **Inverse relationship**: RoMM（IR × CR）越高 → 可接受 DR 越低 → **越多 substantive testing**；反之亦然。
- **Business risk** (HKSA 315 (Revised 2019) para 12(b)): risk resulting from significant conditions/events/circumstances that could adversely affect the entity's ability to achieve its objectives and execute its strategies. 分 **operational / financial / compliance** 三類。Business risk **broader than** RoMM — 不是所有 business risk 都影響財務報表（LP 明示：business risk identified by management, reviewed continuously；inherent risk identified by auditor, assessed at time of audit）。
- **RoMM 兩個層次**：financial statement level（整體，如 fraud、incompetent management、going concern uncertainties）vs **assertion level**（再分 IR + CR，需 **separate assessment**）。Presumed fraud risk：**fraud in revenue recognition**（HKSA 240 要求 professional scepticism，唔可以靠過往對 client integrity 嘅經驗排除 fraud）。
- **Cybersecurity risk**：auditor 要 evaluate automated controls 同 general IT controls；發現 material breach 要考慮對財務報告及 disclosures 嘅影響。

**Assertions（HKSA 315 (Revised 2019)）**
- 定義：representations by management, explicit or otherwise, inherent in preparing the financial statements per the applicable framework.
- **Transactions and events (6)** — HKSA 315 (Revised 2019) para A190(a): **Occurrence / Completeness / Accuracy / Cutoff / Classification / Presentation**
- **Account balances at period end (6)** — HKSA 315 (Revised 2019) para A190(b): **Existence / Rights and obligations / Completeness / Accuracy, valuation and allocation / Classification / Presentation**
- Disclosures：上述 assertions 經適當調整後適用；可用 **disclosure checklist**（要 up-to-date，符合 HKFRS 及 Companies Ordinance (Cap. 622)）。
- **Significant risk**：必須了解相關 controls；如打算 rely on controls over a significant risk，必須 **current period** 測試，且仍要做 substantive procedures。
- **HKSA 250 (Revised)** laws & regulations：management 負責合規；auditor 要 obtain general understanding of legal/regulatory environment、inspect correspondence with regulators、enquire of management/TCWG、obtain written representations on known non-compliance。Direct effect（HKFRS、Cap. 622、tax legislation）vs indirect effect（environmental、employment、health & safety）。

#### B. Materiality（HKSA 320）

- 定義 (HKSA 320.2): misstatements are material if they, individually or in aggregate, could reasonably be expected to **influence the economic decisions of users**.
- **Quantitative benchmarks**（起點，非硬性規定，professional judgement）：**0.5%–1% of revenue；5%–10% of profit before tax；1%–2% of total assets**。
- **Material by nature**（qualitative）：misstatement 令 profit 變 loss / net assets 變 net liabilities；**directors' transactions / directors' remuneration**；going concern material uncertainties；potential legal claims 嘅 disclosures。例：平賣車俾 director — 金額 immaterial 但 **material by nature**，屬 related party transaction (HKAS 24 (Revised))，唔披露 → modify opinion。
- **Materiality vs audit risk**：materiality 越高 → 越少 transactions 被測 → audit risk **越高**（inverse）。審計途中可上調/下調 materiality。
- **Performance materiality** (HKSA 320.9): amount(s) set at **less than** materiality for the FS as a whole, to reduce to an appropriately low level the probability that the **aggregate of uncorrected and undetected misstatements** exceeds FS materiality. 可用百分比（如 75% × FS materiality）計算。
- **用啱 benchmark**：misstatement 要同受影響嘅項目比較（如 irrecoverable receivable → PBT + gross assets，唔係 revenue / net assets）。

#### C. Procedures（審計程序設計）

**Audit strategy vs audit plan**
- Strategy **先於** plan，定 scope、timing、direction；考慮 characteristics of the engagement、reporting objectives、significant factors（materiality、assessed RoMM 等）、nature/timing/extent of resources。Plan 跟住 strategy，列明每個 audit area 點攞 evidence。
- Audit programme = list of audit procedures per area；**audit engagement partner** review + authorise 後先可以開始 fieldwork。

**Tests of controls**
- 目的：測 **operating effectiveness** of controls；**唔測金額**（indirect evidence only）。有效 → 少啲 substantive；無效/唔存在 → 唔 rely，改做多啲 substantive。
- **理解內控係 mandatory**（HKSA 315 (Revised 2019)），無論打唔打算 rely；五個 components：control environment / entity's risk assessment process / process to monitor the system of internal control / information system and communication / control activities。
- **Walk-through test**：trace a sample of transactions through the accounting system，可作 tests of controls 一部分。
- Service organisation（如外判 payroll）：可 attend/visit provider、arrange another firm、或攞 **Type 1 report**（description + design）/ **Type 2 report**（仲包 operating effectiveness）。
- Significant deficiencies in internal control → report to TCWG/management per **HKSA 265**。
- **HKSA 330** 要求無論如何都做嘅 substantive procedures：agree FS to underlying accounting records；examine material journals；examine other adjustments。

**Substantive procedures**
- 定義：procedures designed to **detect material misstatement at the assertion level**；= tests of detail + substantive analytical procedures。內控再好都**必須做一啲**（唔可以 100% rely on controls）。
- **Tests of detail**：verify individual transactions/balances（如 trace additions to purchase invoices → rights & obligations + valuation）。

**Substantive analytical procedures — 4 steps**
1. **Develop an independent expectation**（先於計算差異！）
2. **Define a significant difference / threshold** — threshold **must not exceed performance materiality**
3. **Calculate the difference**（expectation vs recorded amount）
4. **Investigate the significant differences and draw conclusions** — 要解釋 **full difference**，唔係只係超過 threshold 嗰部分
- 適用性 4 factors：assertion being tested / reliability of the data / degree of precision possible / amount of variation acceptable。
- **Proof in total**（reasonableness test，常用於 payroll）：Total wages last year × (1 + inflation) × No. of employees this year ÷ No. of employees last year。
- Analytical procedures **唔可以單獨用** — 佢哋 identify possible sources of misstatement，唔直接 detect；要配 inquiry / recalculation / reperformance。

**Analytical procedures 三個階段（HKSA 520）**
1. **Planning stage**（risk assessment procedures，HKSA 315 (Revised 2019) required）— identify unusual transactions/ratios/trends、fraud risks
2. **Substantive analytical procedures**（HKSA 520.3(a): obtain relevant and reliable audit evidence）
3. **Final review near end of audit**（HKSA 520.3(b): assist in forming an overall conclusion whether FS are consistent with auditor's understanding — **mandatory**）
- 定義 (HKSA 520.4): evaluations of financial information through analysis of **plausible relationships** among both financial and non-financial data + investigation of fluctuations inconsistent or differing significantly from expected values。
- 技術：**Comparisons**（prior year、budgets/forecasts、auditor's expectations、industry）、**Trend analysis**、**Common-size analysis**（line item ÷ base × 100；SoFP base = total assets；P/L base = revenue）、**Ratio analysis**。
- **Ratio categories**：Profitability（GP margin = GP/Revenue×100；NP margin = PBT/Revenue×100）｜Efficiency（receivables days = receivables/revenue×365；inventory days = inventory/COS×365；payables days = payables/purchases×365）｜Liquidity（current、quick = (CA − inventory)/CL、gearing）｜Return（gearing、ROCE）。
- 影響 AP precision 嘅 4 factors：**disaggregation / data reliability / predictability / type of analytical procedure**。
- **Data analytics**：操作完整 data set；用處包括 cost vs NRV comparison、inventory ageing、revenue trends by product/region、match orders to cash、segregation of duties user-code analysis、GP margin analysis、AR/AP ageing。

#### D. Evidence（審計證據）

- **HKSA 500 七大 procedures**：**Inspection / Observation / External confirmation / Recalculation / Reperformance / Analytical procedures / Inquiry**（"Review" **唔係** HKSA 500 procedure）。
- **Inspection**：文件（rights & obligations、cut-off、控制運作痕跡）+ physical inspection of assets（existence、condition/impairment）— 但 physical inspection **未必** prove rights & obligations。
- **Observation**：只證明觀察當刻控制有運作（auditor presence 可能影響行為）— 局限要記。
- **External confirmation**（HKSA 505.6(a) 定義：direct written response to the auditor from a third party）：auditor 要 maintain control — auditor prepares letters、selects sample、sends requests（HKSA 505.7）。Receivables confirmation → **existence + rights & obligations**，**唔係 valuation**。Bank confirmation letter 包 balances + security pledged。Legal confirmation → HKAS 37 provision/contingent liability 判斷。
- **Recalculation**（數學準確性，如 depreciation）vs **Reperformance**（auditor 獨立重做 client 嘅 control/procedure，如 bank reconciliation）— 唔好撈亂。
- **Inquiry**：alone is **insufficient**（low quality, inherent bias）；要 corroborate；可要求 confirm in written representation。
- Evidence 質素 hierarchy（更可靠）：independent external source > internally generated under effective controls > auditor direct > documentary form > **original** documents（scanned/photocopied 可能被 tamper — fraud risk factor）。
- **Sufficiency**（quantity）vs **Appropriateness**（quality = relevance + reliability）：unreliable evidence 攞幾多都冇用。
- Factors affecting information as audit evidence：**relevance / reliability / competence / sufficiency / timeliness**（SoFP evidence 越近 reporting date 越可靠；P/L evidence 要 cover 全年）。
- **Written representations**（HKSA 580）：internal evidence，只作 complement，唔可以單獨 rely；letter on client letterhead、signed by CEO/CFO、**date = date FS authorised for issue**、auditor's report 簽署**前**取得。Management 拒絕 → discuss reasons → re-evaluate integrity of management → consider implications for auditor's report。Representation 與其他 evidence 不一致 → reconsider reliability、risk assessment、further procedures。

#### E. Using the Work of Others

- 兩類 expert：**Management's expert**（HKSA 500 — client 僱用，協助 prepare FS，如 valuer/actuary/lawyer）vs **Auditor's expert**（HKSA 620 — 審計師僱用，攞 sufficient appropriate audit evidence）。
- 需要 expert 嘅情況：property valuations、construction WIP、actuarial valuations for defined benefit plans、specialist inventory、legal provisions、complex financial instruments、complex accounting estimates（HKSA 540 (Revised) para A31 情況）。
- **HKSA 620 三步**：
  1. **Agree scope** in engagement letter：nature/scope/objectives、roles & responsibilities、communication、confidentiality
  2. **Assess competence, capability and objectivity**（**before** work starts）：qualifications、experience、professional body membership、published work；business/personal relationships with client → objectivity threat
  3. **Evaluate adequacy of work**：consistency with other audit evidence、relevance & reasonableness of assumptions/methods、relevance/completeness/accuracy of source data。Inadequate → agree further work 或換 expert。
- **HKSA 610 (Revised 2013) Using the Work of Internal Auditors**：
  - 評估 IA function（610.15–610.17）：**objectivity**（organisational status + policies）、**competence**、**systematic and disciplined approach (incl. quality control)**
  - 用之前再評估：work properly planned/performed/supervised/reviewed/documented、sufficient appropriate evidence obtained、conclusions appropriate、reports consistent with work；external auditor 要 **reperform** 部分程序
  - **Direct assistance** = internal auditors perform audit procedures under direction, supervision and review of external auditor。**禁止** (HKSA 610.28(a)(b))：significant threats to objectivity 或 lacks sufficient competence。唔可以 assign：significant judgements / high RoMM areas / IA 曾參與嘅工作 / HKSA 610 下 external auditor 自己嘅決定
  - Direct assistance 條件：management **written agreement** 唔會干預 + IA **written confirmation of confidentiality** + external auditor direction/supervision/review；documentation per HKSA 610.36/37（包括 HKSA 230 下 review details）
- **Responsibility for conclusion**：auditor's opinion 永遠係 engagement partner 負責；**must not refer to the work of others in the auditor's report** unless required by law or regulation（即使提咗都要講明唔 diminish responsibility）。

### 易混淆概念對比

**Table 1: Tests of Controls vs Substantive Procedures**

| | Tests of Controls | Substantive Procedures |
|---|---|---|
| Objective | Test **operating effectiveness** of internal controls | **Detect material misstatement at the assertion level** |
| Focus | 控制有冇運作（唔理金額） | 財務報表嘅金額／disclosures |
| Evidence type | Indirect evidence over FS | Direct evidence over FS |
| Sub-types | Walk-through tests, observation, reperformance of controls, inspection of authorisation | Tests of detail + substantive analytical procedures |
| Mandatory? | 了解內控 mandatory (HKSA 315 (Revised 2019))；tests of controls 只在打算 rely 時做 | **永遠要做一啲** — 內控再好都唔可以 100% rely；HKSA 330 指定三項必做 |
| 點樣分辨／考試伏位 | 見到 "authorisation"、"segregation of duties"、"credit check evidence" 字眼 = test of control | 見到 "trace to invoice"、"recalculate"、"proof in total"、"confirm balance" = substantive。**伏位**：觀察員工打卡（test of control）≠ trace capital item to invoice（substantive）；GP margin 按年比較係 analytical procedure 但未必係 *substantive* AP |

**Table 2: Financial Statement Materiality vs Performance Materiality (HKSA 320)**

| | FS Materiality | Performance Materiality |
|---|---|---|
| Definition (HKSA 320.2 / 320.9) | Misstatements that could influence **economic decisions of users** | Amount(s) set **at less than** FS materiality so aggregate of **uncorrected + undetected** misstatements unlikely to exceed FS materiality |
| Level | Higher | **Lower**（如 75% × FS materiality） |
| Purpose | 評估個別／合計 misstatement 對 FS 整體嘅影響；opinion 判斷基準 | 設計測試範圍嘅操作門檻；防止大量細 misstatement 加埋變 material |
| Benchmarks | 0.5–1% revenue / 5–10% PBT / 1–2% total assets | FS materiality 嘅一個百分比（professional judgement） |
| Qualitative? | Yes — material by nature（directors' transactions、profit→loss） | 主要係量化工具 |
| 點樣分辨／考試伏位 | 題目問「material or not」→ 用 FS materiality + nature 判斷 | 題目講「threshold for substantive AP must not exceed ___」→ 答案係 **performance materiality**，唔係 FS materiality（常見伏位） |

## Phase 2 閃卡

### Card 1
**Front:** State the audit risk model and define each of its three components. Which component is under the auditor's control?

**Back:**
- AR = IR × CR × DR
- Inherent risk (HKSA 200.13(n)(i)): susceptibility of an assertion to material misstatement **before** consideration of related controls
- Control risk (HKSA 200.13(n)(ii)): risk a material misstatement is not prevented, or detected and corrected, on a timely basis by the entity's controls
- Detection risk (HKSA 200.13(e)): risk the auditor's procedures fail to detect a material misstatement that exists
- **Only detection risk** is under the auditor's control (comprises sampling + non-sampling risk)

💬 白話解：三件事乘埋就係審計風險。IR 係「件嘢本身易錯」（未計內控），CR 係「公司內控捉唔到錯」，DR 係「審計師自己都搵唔到」。審計師控制唔到間公司嘅 IR 同 CR，唯一可以做嘅係做多啲測試壓低 DR — 所以 IR/CR 高 → 要接受低 DR → 做多啲 substantive work。

### Card 2
**Front:** Distinguish business risk from inherent risk, and explain why the auditor is not required to identify all business risks.

**Back:**
- Business risk (HKSA 315 (Revised 2019) para 12(b)): risks affecting the entity's ability to achieve objectives and execute strategies; categories: operational / financial / compliance; identified by **management**; reviewed **continuously**
- Inherent risk: function of the audit risk model; identified by the **auditor**; assessed at the time of the audit; always relates to potential material misstatement of the FS
- Business risk is **broader than** RoMM — not all business risks have financial statement consequences, hence outside the scope of the audit

💬 白話解：business risk 係公司嘅嘢（管理層日日要管），inherent risk 係審計嘅嘢（auditor 審計時先評）。公司執笠風險大把，但得嗰啲會搞錯財務報表嘅先關 auditor 事 — 考試鍾意問「邊個 identify 邊個」。

### Card 3
**Front:** List the six assertions for classes of transactions and events, and the six assertions for account balances at period end, per HKSA 315 (Revised 2019).

**Back:**
- Transactions & events (para A190(a)): **Occurrence, Completeness, Accuracy, Cutoff, Classification, Presentation**
- Account balances (para A190(b)): **Existence, Rights and obligations, Completeness, Accuracy-valuation-and-allocation, Classification, Presentation**

💬 白話解：記口訣 — 交易用「OCCACC-P」，結餘用「ERCCAP」。最大伏位：**existence / rights & obligations / valuation & allocation 只屬於 balances**，transactions 冇呢啲；相反 **occurrence / cutoff 只屬於 transactions**。考試最愛叫你在 combination MCQ 裏面分。

### Card 4
**Front:** State the materiality benchmarks suggested by the LP, the definition of performance materiality, and give two examples of items material by nature.

**Back:**
- Benchmarks (HKSA 320, starting points only): **0.5–1% of revenue; 5–10% of profit before tax; 1–2% of total assets**
- Performance materiality (HKSA 320.9): amount(s) set at **less than** FS materiality to reduce to an appropriately low level the probability that the aggregate of uncorrected and undetected misstatements exceeds FS materiality
- Material by nature: misstatements turning a profit into a loss (or net assets into net liabilities); **directors' transactions/remuneration**; going concern material uncertainties; disclosures of potential legal claims

💬 白話解：materiality 唔淨止睇數字大細，仲要睇性質 — 賤賣資產俾董事，金額再細都 material by nature（HKAS 24 related party 要披露）。Performance materiality 係「保險線」，拉低啲，等啲小錯加埋都唔會爆 FS materiality。

### Card 5
**Front:** List the seven procedures for gathering audit evidence per HKSA 500, and state one limitation each of observation and inquiry.

**Back:**
- **Inspection, Observation, External confirmation, Recalculation, Reperformance, Analytical procedures, Inquiry**
- Observation: only evidences the control operating **at the time of observation**; auditor's presence may influence behaviour
- Inquiry: alone is **insufficient** — responses have inherent bias / low quality; must be corroborated by other procedures

💬 白話解：七式口訣「IOECRAI」。**Review 唔係其中一式**（LP 明講，考試考過呢個陷阱）。Observation 嘅致命傷係「你望住佢先做足」；inquiry 嘅致命傷係「佢講咩你唔可以就咁信」。

### Card 6
**Front:** Describe the four steps of a substantive analytical procedure and the rule regarding the threshold.

**Back:**
1. Develop an **independent expectation**
2. Define a **significant difference / threshold** — the threshold **must not exceed performance materiality**
3. **Calculate the difference** between expectation and recorded amount
4. **Investigate significant differences and draw conclusions** — obtain explanations for the **full difference**, not just the amount exceeding the threshold

💬 白話解：次序好重要 — 一定要 **先有 expectation 先計差異**，如果倒轉做（睇完實數先度 expectation）就係 anchoring，LP 明講唔得。Threshold 上限係 performance materiality，唔係 FS materiality — 考試 MCQ 陷阱位。

### Card 7
**Front:** When is an external confirmation appropriate, what must the auditor control (HKSA 505), and which assertions does a trade receivables confirmation support (and not support)?

**Back:**
- External confirmation (HKSA 505.6(a)): audit evidence as a **direct written response to the auditor from a third party**; used for receivables, payables (no supplier statements), legal confirmations, inventory held by third parties, bank balances
- Auditor maintains control (HKSA 505.7): auditor **prepares** the letters, **selects** the sample, **sends** the requests; responses come **directly to the auditor**
- Receivables confirmation supports **existence** and **rights & obligations** — does **NOT** provide reliable evidence over **valuation** (customer may owe but never pay)

💬 白話解：confirmation 之所以可靠係因為第三方直接覆俾 auditor，唔經 client 手（唔會被做手腳）。但記住：客話「係呀我欠你錢」唔代表佢還得起 — 所以 existence ✓、valuation ✗，呢個係萬年伏位。

### Card 8
**Front:** State the three criteria for evaluating the internal audit function (HKSA 610 (Revised 2013)), the two prohibitions on using internal auditors for direct assistance, and the rule on referring to others' work in the auditor's report.

**Back:**
- Evaluate IA function: **objectivity** (organisational status + policies/procedures), **competence**, **systematic and disciplined approach including quality control**
- Direct assistance prohibited if: (a) **significant threats to the internal auditor's objectivity**, or (b) internal auditor **lacks sufficient competence**; also cannot assign work involving significant judgements / high RoMM / work IA was involved in / HKSA 610 decisions
- Auditor's report: the auditor **must not refer to the work of others** unless required by law or regulation; responsibility for the opinion always rests with the audit engagement partner

💬 白話解：用內審之前要驗三樣：客觀、勝任、有系統。Direct assistance 兩個煞停制：唔客觀、唔夠料。最重要：專家做咗嘢都好，report 上面**唔准提佢個名**（除非法律要求），責任永遠係 partner 孭 — 呢個 MCQ 出到爛。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Audit risk | 審計師出錯 opinion 嘅風險（= IR × CR × DR） | Audit risk is the risk that the auditor expresses an incorrect opinion on the financial statements. |
| Detection risk | 審計程序搵唔到重大錯誤嘅風險；唯一 auditor 控制到嘅風險 | Detection risk is reduced by increasing the nature, timing and extent of substantive procedures. |
| Performance materiality | 低過 FS materiality 嘅操作門檻，防小錯加埋變大錯 | The threshold for substantive analytical procedures must not exceed performance materiality. |
| Substantive procedures | 專登設計嚟喺 assertion level 捉重大錯誤嘅程序（tests of detail + substantive AP） | Substantive procedures are required on material items even when internal controls are effective. |
| Walk-through test | 抽幾單交易由頭行到落尾，驗證對系統嘅理解（可作 test of controls） | The auditor performed a walk-through test by tracing a sales order through the accounting system. |
| Proof in total | 用獨立數據砌出整個餘額嘅合理期望值（常用於 payroll/depreciation） | A proof in total of payroll was developed using last year's wages, pay rises and headcount changes. |
| External confirmation | 第三方直接書面回覆俾 auditor 嘅證據（HKSA 505） | The auditor maintained control over external confirmations by preparing, selecting and sending the requests. |
| Auditor's expert | 審計師自己請嘅專家，幫手攞 sufficient appropriate audit evidence（HKSA 620） | Before using an auditor's expert, the auditor must assess the expert's competence, capability and objectivity. |
