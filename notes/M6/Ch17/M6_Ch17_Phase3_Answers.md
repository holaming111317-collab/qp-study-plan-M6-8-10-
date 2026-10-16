# M6 Chapter 17: Earnings per Share — Phase 3 Answers

### Q1 — Answer: B
**Model Answer (EN):** Earnings for basic EPS = profit attributable to ordinary shareholders of the parent entity, adjusted for the **after-tax** amount of returns on preference shares classified as equity. For **non-cumulative** preference shares, only the dividend **declared** in the period is deducted.

Earnings = HK$8,000,000 − HK$500,000 × (1 − 16.5%) = HK$8,000,000 − HK$417,500 = **HK$7,582,500**

**解題思路（繁中）:** 關鍵兩步：(1) non-cumulative preference shares → 只扣**已宣派**嘅股息（undeclared 唔使扣）；(2) 因為股息由 retained earnings 支付、冇稅務扣減，要**調整稅務影響**，當佢係可扣稅利息咁計 — 所以扣 after-tax 嘅 HK$417,500 而唔係 HK$500,000。
- A 錯：完全冇調整 preference dividend — EPS 係普通股股東角度，其他股東嘅分派要剔走。
- C 錯：扣咗股息但**冇做稅務調整** — LP 明確講「return paid from retained earnings without tax deducted is adjusted for tax」。
- D 錯：方向掉轉，變成**加返** after-tax dividend。

**Rule Check:** HKAS 33.12, HKAS 33.13（after-tax preference dividends deducted from earnings）; Exhibit 17.1 flowchart

**Common Trap（繁中）:** 考生最常犯係記住「扣股息」但**唔記得稅務調整**。記住邏輯：如果得普通股，嗰筆錢會係可扣稅利息開支，所以扣嘅係 after-tax 數。cumulative vs non-cumulative 嘅分別（undeclared 扣唔扣）係另一常見考點。

### Q2 — Answer: C
**Model Answer (EN):** WANOS (monthly weighting):
- 1 Jan – 31 Dec: 8,000,000 × 12/12 = 8,000,000
- Issued 1 Jul: 2,400,000 × 6/12 = 1,200,000
- Bought back 1 Oct: (600,000) × 3/12 = (150,000)
- WANOS = **9,050,000 shares**

Basic EPS = HK$21,900,000 ÷ 9,050,000 = **HK$2.42**

**解題思路（繁中）:** 市價發行／回購只影響 WANOS 嘅**時間加權**，唔使重述比較期間。發行由 1 July 起計 6 個月，回購由 1 October 起計扣 3 個月。
- A 錯（HK$2.23）：用咗**年結日實際股數** 9,800,000（8m + 2.4m − 0.6m）做分母，冇時間加權。
- B 錯（HK$2.38）：加權咗新發行但**漏咗回購**（分母 9,200,000）。
- D 錯（HK$2.74）：完全冇理會年中變動，用期初 8,000,000 股。

**Rule Check:** HKAS 33.20, HKAS 33.21（time-weighting of shares issued/bought back during the period）

**Common Trap（繁中）:** Jun 2025 考官報告特別鬧考生「weighted-average shares for mid-year issue poorly done」。伏位：(1) 用期末股數當 WANOS；(2) 記得加新股但唔記得扣回購。時間加權可以由發行日計到年結（6/12），buy-back 係**減數**，唔係加。

### Q3 — Answer: B
**Model Answer (EN):**
- Theoretical ex-rights price = (4,000,000 × HK$10 + 1,000,000 × HK$6) ÷ 5,000,000 = HK$46,000,000 ÷ 5,000,000 = **HK$9.20**
- Adjustment factor = HK$10 ÷ HK$9.20 = **1.0869565**
- Restated 20X4 WANOS = 4,000,000 × 1.0869565 = 4,347,826 shares
- Restated 20X4 basic EPS = HK$3,600,000 ÷ 4,347,826 = **HK$0.83** (equivalently HK$0.90 ÷ 1.0869565)

**解題思路（繁中）:** 供股價 HK$6 低過市價 HK$10 → 有 **bonus element** → 股數增加但資源唔按比例增加 → **所有比較期間 EPS 都要重述**（乘 adjustment factor 落分母，或者將舊 EPS 除以 factor）。
- A 錯（HK$0.72）：直接用供股後 5,000,000 股做分母 — 舊年度根本唔存在嗰 1,000,000 股。
- C 錯（HK$0.90）：冇重述 — 管理層聲稱「rights issue 對 comparative EPS 冇影響」係**錯**嘅（LP Exam Practice Q1 嘅 management assertion 都係 not true）。
- D 錯（HK$0.98）：將舊 EPS **乘** factor（方向掉轉）— factor 係加喺**股數**度，EPS 要**除**。

**Rule Check:** HKAS 33.27, HKAS 33.28, HKAS 33.A2（theoretical ex-rights price and adjustment factor; restatement of comparatives for the bonus element in a rights issue）

**Common Trap（繁中）:** 三個伏位：(1) TERP 公式分子係「舊股公平值 **+ 供股所得款項**」，唔好漏咗 proceeds；(2) factor = 市價 ÷ TERP，唔好倒轉；(3) 重述係**舊 EPS ÷ factor**，唔係 ×。Bonus issue / share split 同樣要重述，但市價發行就唔使。

### Q4 — Answer: A
**Model Answer (EN):** The exercise price (HK$15) is **above** the average market price for the period (HK$12). If exercised, the assumed proceeds (600,000 × HK$15 = HK$9,000,000) would repurchase 750,000 shares at the average market price — more than the 600,000 shares issuable — so no shares would be issued for no consideration. The options would **increase EPS** (or have no dilutive effect) and are therefore **anti-dilutive**: excluded from diluted EPS (HKAS 33.41, 33.43, 33.45) but disclosed in the notes as instruments that could potentially dilute basic EPS in the future (HKAS 33.70).

**解題思路（繁中）:** Options 嘅 dilution test 好直接：**exercise price < average market price → dilutive；exercise price ≥ average market price → anti-dilutive → exclude**。呢度 HK$15 > HK$12，holder 用 HK$15 買股仲貴過市價，冇「免費股份」產生。
- B 錯：唔係所有 options 都要計入 — 必須先過 dilution test，而且就算 dilutive 都係只加 **shares for no consideration**，唔係全部 600,000 股。
- C 錯：600,000 × (HK$15 − HK$12) ÷ HK$12 = 150,000 係**亂套公式** — 分子分母調轉兼無視咗 exercise price 高過市價嘅事實，套出嚟嘅「free shares」根本唔存在。
- D 錯：**「未行使所以唔計」係大錯** — Jun 2025 考官報告專登批評考生以為 options 要 exercised 先計入。diluted EPS 計嘅係 **potential** dilution；呢啲 options 唔計入係因為 **anti-dilutive**，唔係因為未行使。

**Rule Check:** HKAS 33.41（anti-dilutive shares excluded）, HKAS 33.43（dilutive = decreases EPS from continuing operations）, HKAS 33.45–46（options assumed exercised; shares for no consideration）, HKAS 33.70（disclosure of excluded potentially dilutive instruments）

**Common Trap（繁中）:** 兩大伏位都係考官報告點名嘅：(1) 以為 options 要行使咗先影響 diluted EPS；(2) 唔比較 exercise price 同 **average market price** 就亂加股數。仲有：anti-dilutive 唔等於唔使理 — notes 要披露。

### Q5 — Answer: B
**Model Answer (EN):**
- Step 1 — Dilution test: earnings per incremental share = after-tax interest ÷ conversion shares = HK$167,000 ÷ 1,000,000 = HK$0.167 < basic EPS of HK$2.00 (HK$10,000,000 ÷ 5,000,000) → **dilutive**, include.
- Step 2 — Adjusted earnings: interest add-back = 40,000 × HK$100 × 5% × (1 − 16.5%) = HK$200,000 × 0.835 = HK$167,000 → adjusted earnings = HK$10,000,000 + HK$167,000 = **HK$10,167,000**
- Step 3 — Adjusted shares: 5,000,000 + (40,000 × 25) = 5,000,000 + 1,000,000 = **6,000,000**
- Diluted EPS = HK$10,167,000 ÷ 6,000,000 = **HK$1.69**

**解題思路（繁中）:** Convertible bonds 標準三步：test → add back after-tax interest 落分子 → 加 conversion shares 落分母。轉換後 EPS 由 2.00 跌到 1.69 → 的確 dilutive，計法成立。
- A 錯（HK$1.67）：分母加咗 1,000,000 股但**分子冇 add back interest**（10,000,000 ÷ 6,000,000）— 轉咗股就唔使付息，分子分母要**一齊郁**。
- C 錯（HK$1.70）：add back 咗**稅前** interest HK$200,000（10,200,000 ÷ 6,000,000）— 必須用 after-tax，因為利息慳返嘅同時稅都會多交。
- D 錯（HK$2.00）：即係 basic EPS，完全冇理會 convertible bonds（或者錯誤判斷為 anti-dilutive）。

**Rule Check:** HKAS 33.33（after-tax adjustment to earnings for interest on dilutive potential ordinary shares）, HKAS 33.36（conversion deemed at beginning of period）, HKAS 33.50（convertible instruments dilutive only if earnings per incremental share < basic EPS）

**Common Trap（繁中）:** 三個經典錯：(1) 只做分母唔做分子；(2) 唔記得 interest add-back 要 **× (1 − tax rate)**；(3) 唔做 dilution test 就當 convertible 一定 dilutive（LP West Plates 例子入面 CPS 就係 anti-dilutive）。記住 diluted EPS 係「worst-case warning sign」— 計出嚟**一定唔可以高過** basic EPS；如果高過就係 anti-dilutive 要 exclude。
