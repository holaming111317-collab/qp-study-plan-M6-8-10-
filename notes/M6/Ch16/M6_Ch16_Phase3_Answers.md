# M6 Chapter 16: Income Taxes — Phase 3 Answers

### Q1 — Answer: D
**Model Answer (EN):**
Tax base of a liability = Carrying amount − future deductible amounts + future taxable amounts.
- Carrying amount = HK$360,000; future deductible amount = HK$360,000 (deductible only when paid); future taxable amount = Nil.
- Tax base = HK$360,000 − HK$360,000 + Nil = **Nil**.
- Consequently, carrying amount (360,000) > tax base (Nil) gives a deductible temporary difference of HK$360,000, giving rise to a deferred tax asset.

**解題思路（繁中）:** 負債嘅 tax base 公式係「Carrying amount − 將來可扣 + 將來應課稅」。Warranty 將來付款先扣得，所以將來可扣 = 360,000，TB 變 Nil。A 係直接抄賬面值，冇扣將來可扣數 — 係最常見錯誤（panel report 話 tax base of a liability 年年弱就係呢度）。B 係將可扣數加埋落去（方向調轉）。C 係無啦啦除以二，無依據。

**Rule Check:** HKAS 12.5 (definition of tax base and temporary difference); LP §16.2.2.2 liability tax base formula.

**Common Trap（繁中）:** 唔好以為 liability 嘅 tax base 永遠等於賬面值。口訣：「負債將來有得扣，tax base 即刻縮水」。同時留意：TB = Nil 代表成個 provision 都係 deductible temporary difference → DTA（唔係 DTL）。

---

### Q2 — Answer: C
**Model Answer (EN):**
Conversion of accounting profit to taxable income (HK$):

| | HK$ |
|---|---|
| Accounting profit before tax | 4,200,000 |
| Add: Fines and penalties (non-deductible) | 80,000 |
| Add: Depreciation expense | 250,000 |
| Less: Capital allowance deduction | (400,000) |
| Less: Dividend income (non-assessable) | (60,000) |
| Taxable income | 4,070,000 |

Current tax expense = HK$4,070,000 × 16.5% = **HK$671,550**.

**解題思路（繁中）:** 公式：Accounting profit + non-deductible expenses − deductible allowances not in accounts − non-assessable income = taxable income。Distractor 逐個拆：
- A (693,000) = 直接將 4,200,000 × 16.5%，完全冇做任何稅務調整。
- B (681,450) = 4,130,000 × 16.5%，即係漏咗扣 non-assessable 嘅 dividend income（dividend 喺香港唔使課稅，要扣走）。
- D (803,550) = 4,870,000 × 16.5%，即係將 capital allowance 加返入去而唔係扣（方向錯）。

**Rule Check:** HKAS 12.12; LP §16.1.1.1 accounting-profit-to-taxable-income conversion formula.

**Common Trap（繁中）:** 三件事最易亂：(1) depreciation 要 add back、capital allowance 要 deduct — 方向相反；(2) dividend income 喺香港 non-assessable，係 permanent difference，但計 taxable income 時一樣要剔走；(3) 罰款 non-deductible 要 add back。

---

### Q3 — Answer: B
**Model Answer (EN):**
Tax base of the interest receivable (asset) = Carrying amount − future taxable amounts + future deductible amounts = HK$120,000 − HK$120,000 + Nil = **Nil** (the interest will be taxed when received in the future).
- Carrying amount (120,000) > tax base (Nil) → a **taxable temporary difference** of HK$120,000.
- Deferred tax liability = HK$120,000 × 16.5% = **HK$19,800**.

**解題思路（繁中）:** Interest income 喺會計上 earned 即認，但稅務上收到現金先課稅 → 將來收錢嗰陣會多交稅，所以係 taxable temporary difference → DTL。Distractor 拆：
- A 將方向調轉：CA > TB 對資產嚟講係 taxable（唔係 deductible），所以唔係 DTA。
- C 混淆咗「已入賬」同「無差異」— 正正因為會計早過稅務確認，先會有 timing difference。
- D 差異類型講啱但結果錯：taxable temporary difference 只會產生 DTL，唔會產生 DTA。

**Rule Check:** HKAS 12.5 (taxable temporary difference); LP §16.2.1 (interest income timing example) and §16.2.3.1–16.2.3.2 (Exhibit 16.1: asset CA > TB → taxable temporary difference; DTL = TTD × tax rate).

**Common Trap（繁中）:** 考試見到「taxable when received / deductible when paid」就要即刻諗 tax base：資產將來要被課稅 → TB 縮細 → CA > TB → DTL。唔好一見「income」就以為係 DTA。

---

### Q4 — Answer: A
**Model Answer (EN):**
Workings (HK$):
- Carrying amount at 31 March 20X9 = 2,000,000 − (2,000,000 ÷ 4) = **1,500,000**.
- Tax base at 31 March 20X9 = 2,000,000 − 1,000,000 (capital allowance) = **1,000,000**.
- Taxable temporary difference = 1,500,000 − 1,000,000 = **500,000**.
- Closing deferred tax liability = 500,000 × 16.5% = **82,500**. Opening DTL = Nil → movement = increase of 82,500.

Journal entry:

| Dr | Income tax expense – deferred | 82,500 |
|---|---|---|
| Cr | Deferred tax liability | 82,500 |

(An increase in a deferred tax liability gives rise to deferred tax expense.)

**解題思路（繁中）:** 三步曲：CA vs TB → TTD → DTL closing balance → 減 opening 得 movement → 先至寫 JE。Distractor 拆：
- B 方向反轉：DTL 增加要 **Cr** DTL、Dr expense；Dr DTL 係 DTL 減少先啱。
- C 直接將 taxable temporary difference (500,000) 入賬，冇乘稅率 — 記住 JE 記嘅係 tax effect，唔係 temporary difference 本身。
- D 用咗 15% 稅率（500,000 × 15% = 75,000）— 題目明明話 16.5%，考試要睇清楚。

**Rule Check:** HKAS 12.5; LP §16.2.2.1 (tax base of machine = cost − accumulated capital allowance); §16.2.3.2 (DTL = TTD × tax rate; movement entry: Dr Income tax expense – deferred / Cr Deferred tax liability).

**Common Trap（繁中）:** 兩大伏位：(1) closing balance vs movement — 公式計出嚟係 closing balance，opening 為零先可以照入，否則一定要減 opening；(2) Dr/Cr 方向 — DTL 升＝未來多交稅＝ expense 增加（Dr expense）。

---

### Q5 — Answer: A
**Model Answer (EN):**
Tax base workings (HK$):

| Item | Carrying amount | Tax base | Temporary difference |
|---|---|---|---|
| Trade receivables (net) | 1,910,000 | 2,000,000 (gross; sales already taxed; ECL deductible on write-off) | DTD 90,000 |
| Provision for warranties | 140,000 | Nil (deductible when incurred) | DTD 140,000 |
| Property, plant and equipment | 3,000,000 | 2,400,000 (given) | TTD 600,000 |

- Total deductible temporary differences = 90,000 + 140,000 = 230,000 → **Deferred tax asset = 230,000 × 15% = HK$34,500** (probable future taxable income available).
- Total taxable temporary difference = 600,000 → **Deferred tax liability = 600,000 × 15% = HK$90,000**.

**解題思路（繁中）:** 逐項砌 tax base：
- Trade receivables：CA = 2,000,000 − 90,000 = 1,910,000；TB = 1,910,000 − Nil + 90,000 = 2,000,000（銷售已課稅，將來 taxable = Nil；ECL 將來 write off 可扣 90,000）→ CA < TB → DTD 90,000。
- Warranty provision：TB = 140,000 − 140,000 = Nil → CA > TB → DTD 140,000。
- PPE：CA (3,000,000) > TB (2,400,000) → TTD 600,000 → DTL。
Distractor 拆：
- B 冇乘 15% 稅率，直接報 temporary differences (230,000 / 600,000)。
- C 將 DTA 同 DTL 嘅數調轉咗 — 記住 TTD → liability（大數 600,000 係 PPE，係 DTL）。
- D 只計咗 ECL 嘅 DTA（90,000 × 15% = 13,500），漏咗 warranty provision 嘅 DTD。

**Rule Check:** HKAS 12.5; HKAS 12.24 (DTA recognised only to the extent probable future taxable income is available); LP §16.2.2 tax base formulas and §16.2.4.3 (DTA = DTD × tax rate; DTL = TTD × tax rate).

**Common Trap（繁中）:** 多項目題要分開兩堆：DTA 一堆（receivables ECL + provisions）、DTL 一堆（PPE），唔好 net off，亦唔好漏項。記住 DTA 有 probable 條件 — 題目話明「probable sufficient future taxable income」先可以全數認。呢種「tax base of an asset/liability」題型係 panel report 連續三年點名嘅弱項，務必練熟。
