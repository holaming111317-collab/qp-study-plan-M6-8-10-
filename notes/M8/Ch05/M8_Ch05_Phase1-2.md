# M8 Chapter 5: Sampling — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. Explain the concept of audit sampling and representative sampling under HKSA 530 Audit Sampling.
2. Distinguish between sampling risk and non-sampling risk, and between statistical and non-statistical sampling.
3. Describe the principal sample selection methods and the factors that influence sample size for tests of control and tests of details.
4. Apply substantive sampling techniques (variable sampling and monetary unit sampling) to an audit plan.
5. Evaluate sample results, including projecting misstatements and dealing with anomalous errors.

### 必背考點

#### A. Evidence — 抽樣風險與核心定義
- **Audit sampling (HKSA 530):** The application of audit procedures to **less than 100% of items** within a population of audit relevance such that **all sampling units have a chance of selection**, in order to provide the auditor with a reasonable basis on which to draw conclusions about the entire population.
- **Population:** the entire set of data from which a sample is selected and about which the auditor wishes to draw conclusions.
- **Representative sample:** one in which the properties of interest of the sample are approximately the same as those of the population. A sample may fail to be representative because of **both sampling risk and non-sampling risk**.
- **Sampling risk (HKSA 530):** the risk that the auditor's conclusion based on a sample may be different from the conclusion if the entire population were subjected to the same audit procedure. Sampling risk is a component of **detection risk** — the only risk in the audit risk model under the auditor's control. Two types of erroneous conclusion:
  - **(a) Affects audit EFFECTIVENESS** (the one the auditor is *primarily* concerned with — more likely to lead to an inappropriate audit opinion):
    - Tests of control: concluding controls are **more effective** than they actually are;
    - Tests of details: concluding a material misstatement **does not exist when in fact it does**.
  - **(b) Affects audit EFFICIENCY** (leads to additional work to establish initial conclusions were incorrect):
    - Tests of control: concluding controls are **less effective** than they actually are;
    - Tests of details: concluding a material misstatement **exists when in fact it does not**.
- **Non-sampling risk (HKSA 530):** the risk that the auditor reaches an erroneous conclusion for **any reason not related to sampling risk** — e.g. applying inappropriate audit procedures, failure to recognise a misstatement or deviation, misinterpreting audit evidence.
- 考試重點：auditor 只提供 **reasonable assurance**，永遠唔係 absolute assurance —— 因為根本冇驗證 100% 嘅交易。

#### B. Evidence — Statistical vs Non-statistical Sampling（HKSA 530）
- **Statistical sampling** must have **BOTH**: (i) **random selection** of sample items; and (ii) the use of **probability theory** to evaluate sample results, **including measurement of sampling risk**. Any approach lacking either characteristic = non-statistical sampling.
- Whichever approach is used is a matter of **professional judgement**; statistical sampling still requires professional judgement (e.g. defining what constitutes a misstatement, setting performance materiality).
- **Non-statistical sampling:** sample size based on auditor's judgement of what is desirable; no complex mathematical procedures; results are **not statistically valid**; risk of bias; not defensible if selection lacks logic; different auditors may produce different samples.

#### C. Procedures — Sample Selection Methods（HKSA 530.2–.4, App 1）
| Method | Statistical? | Key point |
|---|---|---|
| **Random selection** | Yes | Random number generators or tables |
| **Systematic selection** | Yes | Population units ÷ sample size = **sampling interval** (e.g. every 50th invoice); starting point best set by random number generator; ensure no pattern within the population matches the interval |
| **Monetary unit sampling (MUS)** | Yes | Value-weighted selection; conclusion in monetary amounts; larger balances have a **greater chance of selection** (protective for the auditor); starting point need NOT be zero |
| **Haphazard selection** | No | No structured technique; must avoid conscious bias (e.g. easy-to-locate items); **inappropriate when using statistical sampling** |
| **Block selection** | No | Block of contiguous items; often used in **cut-off testing**; **rarely appropriate** for drawing valid inferences about the entire population |

- **Stratification (HKSA 530):** breaking a population into sub-populations with similar characteristics; objective is to **reduce variability within each stratum so sample sizes can be reduced WITHOUT increasing sampling risk**. Tests of details often stratified by **monetary value** (larger items = higher overstatement risk) or by risk characteristic (e.g. receivables by age). Results from a stratum can only be projected to **that stratum**; combine stratum projections for the total balance.
- **Three approaches to testing items (only the third is "audit sampling"):**
  1. **100% selection** — NOT sampling; appropriate for small populations of high-value items, significant risk, or high expected misstatement in tests of details;
  2. **Selection of specific items** — NOT sampling (not all units stand a chance); high-value/unusual/error-prone items; subject to non-sampling risk;
  3. **Audit sampling** — every sampling unit stands an equal chance of selection.
- **Factors to consider when designing/selecting a sample (4 factors):**
  1. The **purpose of the procedure**;
  2. The **combination of procedures** being performed;
  3. The **nature of the audit evidence** sought;
  4. The **possible misstatement conditions**.
- **Factors influencing sample size — Tests of control (HKSA 530, Appendix 2):**
  - ↑ Extent to which risk assessment takes into account relevant controls (more reliance on controls) → **Increase**
  - ↑ Tolerable rate of deviation → **Decrease**
  - ↑ Expected rate of deviation of the population → **Increase**
  - ↑ Assurance required that tolerable rate is not exceeded → **Increase**
  - ↑ Number of sampling units in population → **Negligible effect** (large populations)
- **Factors influencing sample size — Tests of details (HKSA 530, Appendix 3):**
  - ↑ Assessed risk of material misstatement → **Increase** (no tests of control ⇒ need low detection risk ⇒ more substantive evidence)
  - ↑ Use of other substantive procedures directed at the same assertion → **Decrease**
  - ↑ Assurance required that tolerable misstatement is not exceeded → **Increase**
  - ↑ Tolerable misstatement → **Decrease**
  - ↑ Expected misstatement in the population → **Increase**
  - **Stratification** of the population (when appropriate) → **Decrease**
  - Number of sampling units in population → **Negligible effect** (but under MUS, ↑ monetary value of population increases sample size unless offset by a proportional increase in materiality)
- **Sampling process (3 steps):** Step 1 **Design the sample** (objectives, period covered, size, population/sampling unit, assertions, what constitutes a deviation/misstatement) → Step 2 **Select the sample and carry out tests** (apply alternative procedures if expected evidence unavailable) → Step 3 **Evaluate the results**.

#### D. Procedures — Techniques for Substantive Tests
- **Variable sampling:** predicts the value of a specific variable within a population; each individual item is the sampling unit. Three common types:
  - **Mean per unit** — sample mean × number of items in population;
  - **Ratio estimation** — apply the sample ratio to the entire population;
  - **Difference estimation** — like ratio estimation but also incorporates the records in the population itself.
- **Monetary unit sampling (MUS):** uses the **currency unit value** (not the items) as the sampling population; applied to large-variance populations (receivables, inventories); sample size considers population size, tolerable misstatement (related to performance materiality) and assurance level required. **Sampling interval = population value ÷ sample size**; select the balance containing each cumulative interval.
- **Attribute sampling:** used to **test controls**; each item either does or does not possess the attribute ("correct / not correct"); monetary amount is irrelevant — a test of control provides **indirect** evidence over the financial statements. **Upper deviation rate = sample (population) deviation rate + sampling risk**; if upper deviation rate ≤ tolerable rate of deviation, the auditor can place reliance on the control. (Confidence level + sampling risk = 100%.)

#### E. Procedures / Assertions — Tests of Control vs Substantive Procedures（HKSA 315 (Revised 2019)、HKSA 500、HKSA 520）
- **Tests of control:** evaluate the **operating effectiveness** of controls in preventing, or detecting and correcting, material misstatement; focus is on the **processes**, NOT the monetary amount.
- **Substantive procedures (HKSA 500):** = **tests of details** + **substantive analytical procedures**; aim to **detect** material misstatement **at the assertion level**; focus on monetary values.
- **Analytical procedures (HKSA 520.4):** evaluations of financial information through analysis of plausible relationships among financial and non-financial data; they identify possible sources of misstatement but **do not, in themselves, detect misstatements** (misstatements may cancel out/contra). Use as the main substantive evidence only where internal controls are assessed as reliable.
- **Mandatory rule:** the auditor must perform **some substantive testing over ALL material** transactions and balances — can never rely wholly on tests of control.
- Audit risk model: **Audit risk = Inherent risk × Control risk × Detection risk**.
- Assertion direction example (completeness of revenue): trace from **sales orders → GDNs → sales invoice → sales day book → sales ledger → general ledger** (starting point "outside" the accounting system tests for understatement).
- Example: tracing receivables to **post-year-end cash receipts** supports **existence and valuation** assertions.

#### F. Evidence — Evaluation of Results（HKSA 530.12, .14, .15, .A21–.A23）
- **HKSA 530.12:** the auditor **shall investigate the nature and cause** of any deviations or misstatements identified, and evaluate their possible effect on the purpose of the audit procedure and on other areas of the audit.
- **Anomalous error:** a one-off misstatement/deviation not representative of the population; the auditor must obtain **sufficient appropriate audit evidence** (via further procedures) that it is genuinely anomalous, and be satisfied it is **not indicative of a fraud risk factor**. Anomalous misstatements **may be excluded from projection** (tests of details only — for tests of control the sample deviation rate IS the projected rate).
- **HKSA 530.14:** the auditor **shall project misstatements** found in the sample to the population for tests of details. **Projected misstatement = (misstatement in sample ÷ sample value) × population value**.
- **HKSA 530.15(a),(b):** evaluate (a) the results of the sample; and (b) whether sampling has provided a **reasonable basis for conclusions** about the population.
- **Evaluation rule (HKSA 530.A21/A22):** **projected misstatement + anomalous misstatement = best estimate of misstatement in the population**; if this total **exceeds tolerable misstatement**, the sample does NOT provide a reasonable basis for conclusions. The closer the total is to tolerable misstatement, the more likely actual misstatement exceeds it.
- **Tolerable misstatement (HKSA 530.A22; HKSA 320 para. 9):** the application of **performance materiality** to a particular sampling procedure; may be the same as, or lower than, performance materiality.
- **If sampling does not provide a reasonable basis (HKSA 530.A23):** (i) request management to investigate identified misstatements and potential further misstatements and make necessary adjustments; or (ii) tailor the nature, timing and extent of additional procedures (e.g. increase sample size, test an alternative control, modify related substantive procedures).
- **Tolerable rate of deviation:** the rate of deviation from prescribed internal control procedures set by the auditor in respect of which the auditor seeks assurance that it is not exceeded by the actual rate in the population.

### 易混淆概念對比

**Table 1: Sampling Risk vs Non-sampling Risk**

| 比較點 | Sampling Risk | Non-sampling Risk |
|---|---|---|
| Definition (HKSA 530) | Conclusion based on a sample may differ from the conclusion if the entire population were subjected to the same procedure | Erroneous conclusion for any reason NOT related to sampling risk |
| Root cause | Sample not representative / sample too small | Inappropriate procedures; failure to recognise a misstatement or deviation; misinterpreting evidence |
| Relationship | Component of detection risk | Opposite of sampling risk |
| How to reduce | Increase the sample size | Better training/supervision, appropriate procedure design, proper direction & review |
| 點樣分辨 | 問題出在「抽唔啱」— 樣本本身代表性不足 | 問題出在「做唔啱」— 就算抽啱樣本，人為判斷/程序都出錯 |
| 考試伏位 | Panelist 報告（Jun 2024）話考生分唔清兩者："did not put enough effort into studying audit sampling"。記住：misinterpreting audit evidence = **non-sampling risk**，唔好見到「risk」就亂揀 | 100% testing 冇 sampling risk，但仍然有 non-sampling risk |

**Table 2: Statistical vs Non-statistical Sampling**

| 比較點 | Statistical Sampling | Non-statistical Sampling |
|---|---|---|
| Defining characteristics | BOTH (i) random selection AND (ii) probability theory to evaluate results, including measurement of sampling risk | Any approach lacking either characteristic; sample size by auditor's judgement |
| Selection methods | Random, systematic, monetary unit sampling | Haphazard, block selection |
| Measurement of sampling risk | Yes — mathematically measured | No — results not statistically valid |
| Advantages | Defensible/precise probability statements; efficient sample sizes; usable by all staff levels; standard testing programme | No complex maths; no specialist knowledge; harnesses auditor's judgement and experience |
| Disadvantages | Complex mathematics; principles must be properly applied | Bias risk; sample sizes too large (cost) or too small (invalid); not defensible without logic; inconsistent between auditors |
| 點樣分辨 | 兩個條件缺一不可：random + probability theory。淨係 random selection 而冇 probability evaluation 都唔算 | Haphazard selection 喺 statistical sampling 入面係 **inappropriate**（HKSA 530 明確講） |
| 考試伏位 | 唔好以為 statistical = 唔使 professional judgement — 兩者都要 judgement | Block selection 雖然常用於 cut-off testing，但對成個 population 推論「rarely appropriate」 |

## Phase 2 閃卡

### Card 1
**Front:** Define "audit sampling" according to HKSA 530, and state the two key numerical/selection characteristics in the definition.

**Back:**
- The application of audit procedures to **less than 100% of items** within a population of audit relevance;
- Such that **all sampling units have a chance of selection**;
- Purpose: to provide a reasonable basis for conclusions about the **entire population**.
- 100% examination and selection of specific items are **NOT** audit sampling.

💬 白話解：抽樣嘅精髓係「唔驗晒，但每個單位都有機會被抽中」。如果 auditor 淨係揀大額嗰啲嚟驗（specific items），嗰個唔叫 sampling，考試好鐘意用呢個位考你。

### Card 2
**Front:** State the two types of erroneous conclusion caused by sampling risk, and identify which one the auditor is PRIMARILY concerned with and why.

**Back:**
- **Type (a) — effectiveness:** controls concluded **more effective** than they are (ToC); material misstatement concluded **not to exist when it does** (ToD) → auditor primarily concerned — affects **audit effectiveness**, more likely to lead to an **inappropriate audit opinion**.
- **Type (b) — efficiency:** controls concluded **less effective** than they are (ToC); misstatement concluded **to exist when it does not** (ToD) → affects **audit efficiency** (extra work).

💬 白話解：記憶口訣 —— 「漏咗」（以為冇錯其實有錯）先係大鑊，會出錯 opinion；「做多了」（以為有錯其實冇錯）只係嘥時間。Effectiveness 永遠係考官首選答案。

### Card 3
**Front:** Give three examples of non-sampling risk and explain how it differs from sampling risk.

**Back:**
- Applying **inappropriate audit procedures**;
- **Failure to recognise** a misstatement or deviation;
- **Misinterpreting** the audit evidence obtained.
- Difference: non-sampling risk arises even if the whole population is tested — it is unrelated to the fact that only a sample was examined.

💬 白話解：凡係「人為失手」—— 用錯程序、睇漏咗、解讀錯 evidence —— 全部歸 non-sampling risk。抽樣方法本身冇問題都會中。

### Card 4
**Front:** List the FIVE principal sample selection methods in HKSA 530 and classify each as statistical or non-statistical.

**Back:**
- **Random selection** — statistical (random number generators/tables);
- **Systematic selection** — statistical (sampling interval = population units ÷ sample size);
- **Monetary unit sampling** — statistical (value-weighted; larger balances more likely selected);
- **Haphazard selection** — non-statistical (no structured technique; must avoid bias; inappropriate for statistical sampling);
- **Block selection** — non-statistical (contiguous items; cut-off testing; rarely appropriate for inferences about the whole population).

💬 白話解：三統計、兩非統計。記住 haphazard 同 block 係「 judgement 派」；MUS 雖然揀大額嘢，但佢係 statistical 嘅 value-weighted selection。

### Card 5
**Front:** For tests of details, state the effect (increase/decrease/negligible) on sample size of: (1) higher assessed risk of material misstatement; (2) higher tolerable misstatement; (3) more expected misstatement; (4) more use of other substantive procedures on the same assertion; (5) stratification; (6) more sampling units in the population. (HKSA 530, Appendix 3)

**Back:**
1. Higher RMM → **Increase**;
2. Higher tolerable misstatement → **Decrease**;
3. More expected misstatement → **Increase**;
4. More other substantive procedures on same assertion → **Decrease**;
5. Stratification → **Decrease**;
6. More sampling units → **Negligible effect** (large populations).

💬 白話解：方向邏輯好簡單 —— 「越驚錯就抽越多」（risk↑、expected error↑ → size↑）；「條線越鬆/有其他人幫手 → 抽越少」（tolerable↑、其他 procedures↑、stratify → size↓）。人口數量對大 population 基本上冇影響，呢個係最常見 distractor。

### Card 6
**Front:** Explain how monetary unit sampling (MUS) works, including how the sampling interval is calculated and why it is "protective" for the auditor.

**Back:**
- Uses the **currency unit value** (not individual items) as the sampling population;
- **Sampling interval = total population value ÷ sample size**;
- Starting from a (possibly random) start point, select the balance containing each cumulative interval;
- Larger balances have a **greater chance of selection** → automatically directs effort to higher-value (higher overstatement-risk) items — hence protective;
- Suited to **large-variance populations** (receivables, inventories).

💬 白話解：想像成條 population 係一條「銀紙長龍」，每隔 interval 插一支旗，旗插喺邊個客戶嘅累計餘額入面就抽邊個。大額客戶「佔地」大，自然易中旗 —— 所以 MUS 天生偏向抽大額，對 auditor 有保護作用。

### Card 7
**Front:** What is attribute sampling, and how does the auditor use the "upper deviation rate" to conclude on a test of control?

**Back:**
- Technique used to **test controls**; result is binary — the item either does or does not possess the attribute (e.g. authorised / not authorised);
- Monetary amount is irrelevant → tests of control give **indirect** evidence over the financial statements;
- **Upper deviation rate = sample deviation rate + sampling risk** (confidence level + sampling risk = 100%);
- If upper deviation rate ≤ **tolerable rate of deviation** → auditor can **place reliance on the control**; otherwise increase substantive procedures.

💬 白話解：即使樣本錯誤率低過 tolerable rate 都唔可以即刻落結論 —— 一定要加返 sampling risk 上去先比較。呢個「加返個 risk buffer」嘅動作係 LP Illustrative Example 9 嘅核心。

### Card 8
**Front:** An auditor finds a misstatement in a sample which appears to be a one-off "anomalous error". What must the auditor do before excluding it from projection, and how are sample results evaluated overall? (HKSA 530.12, .14, .15)

**Back:**
- Investigate the **nature and cause** of the misstatement (HKSA 530.12);
- Perform **further procedures** to obtain sufficient appropriate audit evidence that it is genuinely anomalous and **not representative** of the population;
- Be satisfied it is **not indicative of a fraud risk factor**;
- Only then may it be **excluded from projection** (tests of details);
- Overall evaluation: **projected misstatement + anomalous misstatement** = best estimate; if total > **tolerable misstatement** (application of performance materiality per HKSA 320 para. 9), the sample gives **no reasonable basis** → ask management to investigate/adjust, or extend procedures (increase sample size, test alternative control, modify substantive procedures).

💬 白話解：「一時失手」唔係你話咁算 —— auditor 要攞足證據證明佢真係 isolated，仲要排除 fraud 因素。最後條數好簡單：projected + anomalous 大過 tolerable misstatement = 個 sample 冇用，要做多啲嘢。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Audit sampling | 抽唔到100%，但個個單位都有機會被抽中嘅測試方法 | Audit sampling involves applying audit procedures to less than 100% of items such that all sampling units have a chance of selection. |
| Population | 想落結論嗰成堆數據（成個餘額） | The population of trade receivables comprises all individual customer balances at year-end. |
| Sampling risk | 樣本唔代表性，令結論同驗晒成個 population 唔同嘅風險 | Sampling risk increases when the sample size is too small to be representative of the population. |
| Non-sampling risk | 同抽樣無關嘅人為失手風險（用錯程序、睇漏、解讀錯） | Misinterpreting audit evidence is an example of non-sampling risk. |
| Tolerable misstatement | Auditor 接受得嘅最大錯誤金額（performance materiality 嘅應用） | The projected misstatement plus the anomalous misstatement exceeded tolerable misstatement, so the sample provided no reasonable basis for conclusions. |
| Tolerable rate of deviation | 控制測試入面接受得嘅最高偏差率 | If the upper deviation rate exceeds the tolerable rate of deviation, the auditor cannot place reliance on the control. |
| Stratification | 將 population 按特性（例如金額）拆細，抽少啲但唔加風險 | Stratifying the receivables population by monetary value reduced the sample size without increasing sampling risk. |
| Monetary unit sampling | 用「銀碼」做抽樣單位，大額項目天然易被抽中 | Under monetary unit sampling, the sampling interval is calculated by dividing the population value by the sample size. |
