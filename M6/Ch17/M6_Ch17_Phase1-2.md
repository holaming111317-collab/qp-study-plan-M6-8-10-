# M6 Chapter 17: Earnings per Share — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. **Explain** the scope of HKAS 33 Earnings per Share and identify the entities required to present EPS.
2. **Calculate** basic EPS, including the determination of earnings and the weighted average number of ordinary shares (WANOS), incorporating bonus issues and rights issues with a bonus element.
3. **Calculate** diluted EPS by assessing whether potential ordinary shares (options, warrants, convertible instruments) are dilutive or anti-dilutive, and sequence them from most to least dilutive.
4. **Apply** the presentation and disclosure requirements of HKAS 33 for basic and diluted EPS, including discontinued operations and restatement of comparatives.
5. **Evaluate** the limitations of EPS as a performance measure.

### 必背考點

#### A. Scope & "Recognition" of the EPS numbers（邊啲公司要計、用邊個盈利數字）

| 考點 | 內容 | Reference |
|---|---|---|
| Scope | HKAS 33 applies to each entity whose **ordinary shares or potential ordinary shares are traded in a public market** (e.g. HKEX, foreign exchange, OTC markets), or that is **in the process of arranging** a public listing. | HKAS 33.2 |
| Ordinary share | Equity instrument **subordinate to all other classes** of issued securities; participates in profit only after other classes (e.g. preference shares). | HKAS 33.5 |
| Potential ordinary share | A financial instrument or other contract that **may entitle its holder to ordinary shares** — e.g. options, warrants, convertible notes, convertible preference shares. | HKAS 33.5 |
| Earnings (numerator) | **Profit or loss attributable to ordinary shareholders of the parent entity** — excludes NCI; can be a **loss** (loss per share). | HKAS 33.5, 33.31 |
| Continuing vs discontinued | Two separate earnings amounts → two separate basic EPS amounts (continuing operations / discontinued operations, per HKFRS 5). | HKAS 33; HKFRS 5 |
| Preference share returns | Any non-principal payments on preference shares — **whether classified as liabilities or equity under HKAS 32** — are an expense-like deduction from earnings, at the **after-tax** amount. If classified as a liability, the cost (interest) is already in P&L → no further action. If equity: **cumulative** → deduct declared AND undeclared returns for the period; **non-cumulative** → deduct only returns **declared** in the period. | HKAS 33.12, 33.13 |
| Mandatorily convertible instruments | Adjustment to earnings may be needed where they carry a guaranteed return before conversion. | HKAS 33.23 |

#### B. Measurement（Basic EPS 同 Diluted EPS 點計）

**B1. Basic EPS**

```
Basic EPS = Profit/loss attributable to ordinary shareholders of the parent entity
            ─────────────────────────────────────────────────────────────────
                 Weighted average number of ordinary shares on issue
```

| 考點 | 內容 | Reference |
|---|---|---|
| WANOS 時間加權 | Shares issued/bought back during the period are **time-weighted** (days or months) for the portion of the period they were on issue; weighting runs from the date consideration is due (normally issue/redemption date). | HKAS 33.20, 33.21 |
| Shares issued to acquire a business | Included in WANOS **from the date of acquisition** (when the acquiree's earnings enter the group). | HKAS 33.22 |
| Issue at full market value | No restatement of comparatives — resources and share numbers change proportionately; EPS comparable across periods. | HKAS 33 |
| Change in shares WITHOUT change in resources (bonus issue / share split / rights issue with bonus element) | WANOS for the current period **AND all comparative periods** must be adjusted (restated) so EPS is comparable. | HKAS 33.27, 33.28 |
| Rights issue formulas | **Theoretical ex-rights price per share** = (Fair value of shares immediately prior to exercise of rights + Proceeds from exercise of rights) ÷ Number of shares outstanding after exercise of rights. **Adjustment factor** = Fair value per share prior to exercise of rights ÷ Theoretical ex-rights price per share. Prior-period EPS is restated by multiplying prior WANOS by the factor (equivalently, dividing prior EPS by the factor). | HKAS 33.A2 |

**B2. Diluted EPS**

```
Diluted EPS = (Profit/loss attributable to ordinary shareholders −/+ effect of converting dilutive potential ordinary shares)
              ─────────────────────────────────────────────────────────────────────────────────────
              (WANOS + dilutive potential ordinary shares)
```

| 考點 | 內容 | Reference |
|---|---|---|
| Adjustment to earnings | Add back the **after-tax** effect of: (i) dividends/returns on dilutive potential ordinary shares already deducted; (ii) **interest recognised in finance costs** on dilutive potential ordinary shares; (iii) any other income/expense impacts of assumed conversion. | HKAS 33.33 |
| Adjustment to shares | Assume conversion at the **beginning of the period** (or issue date of the potential ordinary shares, if later); determine dilution **independently for each period**; instruments that **lapsed** during the period are included pro-rata for the time outstanding. | HKAS 33.36, 33.37, 33.38 |
| Options & warrants | Assume exercised. Assumed proceeds are treated as received from issuing shares at the **average market price** of the period. Only the **shares issued for no consideration** (shares issuable under the option − shares that the proceeds would buy at average market price) enter the denominator. **Numerator is NOT adjusted.** Shares deemed issued at average market price are neither dilutive nor anti-dilutive — ignore them. | HKAS 33.45, 33.46 |
| Convertible instruments | Dilutive only when **total contractual return ÷ ordinary shares issuable on conversion < basic EPS** (i.e. earnings per incremental share below basic EPS). Add back after-tax return to numerator; add conversion shares to denominator. | HKAS 33.50 |
| Dilutive vs anti-dilutive | Dilutive = conversion would **decrease EPS** (or increase loss per share) from continuing operations → include. Anti-dilutive = conversion would **increase EPS** (or decrease loss per share) → **exclude** from diluted EPS. Benchmark is profit or loss from **continuing operations** attributable to the parent. | HKAS 33.41, 33.42, 33.43 |
| Sequencing (multiple series) | Each series considered **separately**, in order from **most dilutive to least dilutive** based on **earnings per incremental share** (options first — nil earnings effect). Stop when the next instrument would increase EPS. | HKAS 33.44 |

> **Journal entries（本章特別提示）：** HKAS 33 係計量同披露準則 — EPS 本身**唔會產生任何 journal entries**。考試相關嘅 "entries" 係調整分子（after-tax add-back of interest/preference returns）同分母（incremental shares）嘅 **EPS workings**，唔係 double entry。股份發行本身嘅分錄（Dr Cash / Cr Share capital (+ Share premium)）屬於股東權益章節範圍，唔屬於 EPS 計算。考 M6 EPS 題時，**show workings 就有 method marks**，唔好試圖寫 Dr/Cr。

#### C. Presentation & Disclosure（擺邊、披露啲乜）

| 考點 | 內容 | Reference |
|---|---|---|
| Face of SPLOCI | Basic and diluted EPS from **continuing operations** must be presented **on the face of the statement of profit or loss and other comprehensive income**, with **equal prominence**, for **all periods presented** — applies equally to losses per share (negative EPS). | HKAS 33.66, 33.67 |
| Discontinued operations | Separate basic and diluted EPS for discontinued operations — on the face **or in the notes**. | HKAS 33.68 |
| Numerator reconciliation | Disclose the earnings used as numerators for basic and diluted EPS, **reconciled to profit or loss attributable to the parent entity**. | HKAS 33.70 |
| Denominator reconciliation | Disclose the WANOS used as denominators, **reconciled between basic and diluted EPS**, showing the effect of each class of instruments. | HKAS 33.70 |
| Anti-dilutive instruments | Disclose instruments that **could dilute basic EPS in the future** but were excluded because anti-dilutive in the period(s) presented. | HKAS 33.70 |
| Post-reporting-period share transactions | Describe ordinary/potential ordinary share transactions after period end that would have **significantly changed** the share numbers (e.g. large share issue, large conversion). | HKAS 33.70 |

#### D. Limits of EPS as a Performance Measure
- WANOS may be **irrelevant** when large issues/buy-backs occur late in the period (period-end share count differs materially; investors take a forward-looking view).
- Weighting of **lapsed** shares is questioned (known at reporting date that they lapsed).
- **Average market price** used in diluted EPS may not reflect the recent price.
- EPS is **not comparable across industries/geographies** (growth-phase biotech vs mature retailer); EPS is **backward-looking** and only one metric — use with other measures.

### 易混淆概念對比

**Table 1: Basic EPS vs Diluted EPS**

| | Basic EPS | Diluted EPS |
|---|---|---|
| Purpose | Actual interests of each ordinary share in the period's performance | "Worst-case" **warning sign**: EPS if all **dilutive** potential ordinary shares were converted/exercised |
| Numerator | Profit/loss attributable to ordinary shareholders of parent (less after-tax preference returns) | Same, **plus after-tax add-back** of interest/returns on dilutive potential ordinary shares (HKAS 33.33) |
| Denominator | WANOS actually on issue (HKAS 33.20) | WANOS **+ dilutive potential ordinary shares** deemed converted at start of period (HKAS 33.36) |
| When required | All entities in scope | Only when potential ordinary shares exist (complex capital structure) |

**點樣分辨／考試伏位（繁中）：** 見到 options/convertible bonds 唔代表一定要計 diluted — 先要過 **dilution test**。Jun 2025 考官報告特別鬧考生以為 options 要 **exercised** 先計入 — 錯！只要 **potentially dilutive** 就要計。另外 options **唔會郁 numerator**，只有 convertible instruments 先 add back after-tax interest/return。

**Table 2: Dilutive vs Anti-dilutive Potential Ordinary Shares**

| | Dilutive | Anti-dilutive |
|---|---|---|
| Test (HKAS 33.43) | Conversion **decreases EPS** or **increases loss per share** from continuing operations | Conversion **increases EPS** or **decreases loss per share** |
| Options/warrants quick test | **Exercise price < average market price** → shares issued for no consideration exist | **Exercise price ≥ average market price** → excluded |
| Convertibles quick test | **Earnings per incremental share < basic EPS** (HKAS 33.50) | Earnings per incremental share ≥ basic EPS |
| Treatment in diluted EPS | **Included** (denominator, + numerator add-back for convertibles) | **Excluded** from calculation, but **disclosed** in notes as potentially dilutive in future (HKAS 33.70) |

**點樣分辨／考試伏位（繁中）：** 多過一類 potential ordinary shares 時要**逐類獨立測試**，由 **earnings per incremental share** 最細（最 dilutive，通常係 options，因為 numerator effect = nil）排到最大；一路加，加到某類令 EPS **回升** 就停，嗰類之後全部 exclude（HKAS 33.44）。伏位：唔好將所有 instruments 一次過**合埋**測；anti-dilutive 嘅嘢 **diluted EPS 唔計，但 notes 要披露**。

## Phase 2 閃卡

### Card 1
**Front:** What is the formula for basic EPS under HKAS 33, and what exactly is the "earnings" figure?

**Back:**
- Basic EPS = Profit or loss attributable to **ordinary shareholders of the parent entity** ÷ WANOS on issue (HKAS 33.31)
- Earnings excludes NCI interests; may be a **loss** (loss per share)
- Deduct the **after-tax** amount of preference share returns (cumulative: declared + undeclared; non-cumulative: declared only) (HKAS 33.12–13)

💬 繁中白話解釋：EPS 個分子係「屬於母公司普通股股東嘅除稅後損益」，NCI 同 preference shareholders 嘅份都要剔走。優先股股息無論喺 HKAS 32 下係負債定權益，計 EPS 時都當費用扣，仲要用 **after-tax** 數。

### Card 2
**Front:** How do cumulative and non-cumulative preference shares differ in the basic EPS earnings adjustment?

**Back:**
- Cumulative: entity must pay whether declared or not → deduct the **after-tax return for the period (declared AND undeclared)**
- Non-cumulative: no obligation if not declared → deduct only the **after-tax return declared in the period** (HKAS 33.12–13 flowchart, Exhibit 17.1)
- If preference shares are classified as **liabilities** under HKAS 32: interest already expensed in P&L → **no further adjustment**

💬 繁中白話解釋：記法好簡單 — cumulative 係「欠住都當洗咗」，無論宣唔宣派都要扣；non-cumulative 就「宣派先扣」。如果已經喺 P&L 度扣咗（負債類），就唔好扣兩次。

### Card 3
**Front:** How is the weighted average number of ordinary shares (WANOS) determined when shares are issued or bought back mid-period at full market price?

**Back:**
- Time-weight shares for the portion of the period on issue (days or months) (HKAS 33.20)
- Weighting runs from when consideration is due — normally the **issue/redemption date** (HKAS 33.21)
- Shares issued as consideration in a **business acquisition**: include from **acquisition date** (HKAS 33.22)
- Issue at full market price → **no restatement** of comparatives

💬 繁中白話解釋：年中發行新股，唔可以全年計晒 — 要按「喺市嘅時間」加權。West Plates 例子：4月1日發行 2m 股，weighting = 275/365 = 75.3%，即只加 1.506m 股。市價發行唔使重述舊年 EPS。

### Card 4
**Front:** A rights issue is made at below market price. How are current and comparative EPS figures adjusted under HKAS 33?

**Back:**
- Rights issue contains a **bonus element** → change in shares without corresponding change in resources
- Theoretical ex-rights price = (FV of shares before exercise + proceeds from exercise) ÷ shares outstanding after exercise
- Adjustment factor = FV per share before rights ÷ theoretical ex-rights price
- Apply factor to WANOS **before the rights issue** (current year pro-rata) **AND restate all comparative periods** (HKAS 33.27, 33.28, 33.A2)

💬 繁中白話解釋：供股價低過市價 = 變相派紅股，股數多咗但資源唔係按比例多。所以舊年度 EPS 都要「加水」重述：舊 EPS ÷ adjustment factor。考試最常考就係計 TERP 同 factor，跟住 restate comparative。

### Card 5
**Front:** How are options and warrants incorporated into diluted EPS?

**Back:**
- Assume dilutive options/warrants are **exercised**
- Deemed proceeds (options × exercise price) treated as buying back shares at **average market price** of the period
- Only **shares issued for no consideration** = (shares under options) − (proceeds ÷ average market price) enter the denominator (HKAS 33.45, 33.46)
- **No adjustment to the numerator**
- Dilutive only when **exercise price < average market price**

💬 繁中白話解釋：諗住公司收到行使價錢會攞去市場買返啲股 — 買得返嗰部分就當冇發行過（fairly priced，唔 dilutive 唔 anti-dilutive），淨係「免費送出」嗰部分股數先加入分母。記住：options **永遠唔郁分子**。

### Card 6
**Front:** How do you test whether convertible bonds/preference shares are dilutive, and what adjustments follow?

**Back:**
- Test: **earnings per incremental share** = after-tax return on the instrument ÷ ordinary shares issuable on conversion; dilutive if **< basic EPS** (HKAS 33.50)
- If dilutive: numerator **+ after-tax interest/dividend** (HKAS 33.33); denominator **+ conversion shares** (deemed converted at start of period or issue date if later, HKAS 33.36)
- If the recomputed EPS **increases** → anti-dilutive → exclude (HKAS 33.41)

💬 繁中白話解釋：convertible 嘅 test 係「每股新增股份帶嚟幾多盈利」同 basic EPS 比。低過就 dilutive：分子加返 after-tax interest（因為轉咗股就唔使付息），分母加轉換股數。West Plates 例子入面 CPS 轉換後 EPS 由 3.84 升到 4.02 → anti-dilutive → 唔計。

### Card 7
**Front:** When several series of potential ordinary shares exist, in what order are they included in diluted EPS?

**Back:**
- Consider **each series separately**, not in aggregate (HKAS 33.44)
- Sequence from **most dilutive to least dilutive** based on **earnings per incremental share**
- Options/warrants usually first (earnings effect = nil → lowest incremental EPS)
- Stop including further series once the next one would **increase** EPS (that series and beyond are anti-dilutive)

💬 繁中白話解釋：FuturePan 例子：options (incremental EPS = 0) → convertible bonds (HK$1.002) → convertible preference shares (HK$2.667)。加到 preference shares 時 EPS 由 2.50 升返 2.52 → 嗰度停，CPS exclude。記住「逐件加、一升即停」。

### Card 8
**Front:** State the presentation and disclosure requirements for EPS under HKAS 33.

**Back:**
- Basic + diluted EPS from continuing operations: **face of SPLOCI, equal prominence, all periods presented**, including loss per share (HKAS 33.66–67)
- Discontinued operations: separate basic + diluted EPS, face **or notes** (HKAS 33.68)
- Disclose: numerators reconciled to profit attributable to parent; denominators (WANOS) reconciled basic → diluted by instrument class (HKAS 33.70)
- Disclose **anti-dilutive instruments excluded** that could dilute in future
- Describe **post-period-end share transactions** that would significantly change share numbers (HKAS 33.70)

💬 繁中白話解釋：記憶口訣「面上一樣搶眼、所有期間、虧損都照披露」；discontinued 可以落 notes。Notes 要 reconcile 分子分母、披露冇計入嘅 anti-dilutive 工具、同年結後大額股份交易。呢啲 disclosure 題考生成日留白 — 係易攞分位。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Potential ordinary share | 潛在普通股 — 將來可能變成普通股嘅工具（options、warrants、convertible bonds） | A convertible bond is a potential ordinary share because it may entitle its holder to ordinary shares. |
| Weighted average number of ordinary shares (WANOS) | 加權平均普通股數 — 按期內「喺市時間」加權嘅股數 | Shares issued on 1 April are included in WANOS at a weighting of 275/365 days. |
| Theoretical ex-rights price | 理論除權價 — 供股後每股理論價值，用嚟計 adjustment factor | The theoretical ex-rights price per share is the fair value of shares before the rights issue plus the proceeds, divided by the shares outstanding after the issue. |
| Bonus element | 紅利成分 — 供股價低過市價嗰部分，等於免費派股 | Because the exercise price was below fair value, the rights issue contained a bonus element requiring restatement of prior-period EPS. |
| Dilutive | 攤薄性 — 轉換後 EPS 下降（或每股虧損上升） | The options are dilutive because their exercise price is below the average market price of the shares. |
| Anti-dilutive | 反攤薄 — 轉換後 EPS 反而上升，計 diluted EPS 時要剔除 | The convertible preference shares were anti-dilutive and therefore excluded from the diluted EPS calculation. |
| Earnings per incremental share | 每股新增股份盈利 — 用嚟排 dilutive 次序嘅 benchmark | Options have nil earnings per incremental share and are therefore considered first in the diluted EPS sequence. |
| Equal prominence | 同等顯眼 — basic 同 diluted EPS 要喺損益表面一齊披露，唔可以一個大一個細 | HKAS 33 requires basic and diluted EPS to be presented with equal prominence on the face of the statement of profit or loss and OCI. |
