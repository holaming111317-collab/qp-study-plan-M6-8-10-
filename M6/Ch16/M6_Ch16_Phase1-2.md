# M6 Chapter 16: Income Taxes — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives (3–5, English, action verbs)
1. **Distinguish** current tax from deferred tax, and accounting profit from taxable income, under HKAS 12 *Income Taxes*.
2. **Account for** current tax liabilities and current tax assets, including converting accounting profit to taxable income via adjustments.
3. **Compute** the tax base of assets and liabilities and **identify** taxable and deductible temporary differences.
4. **Calculate and recognise** deferred tax liabilities and deferred tax assets, including the movement (opening → closing balance) and the related journal entries.
5. **Apply** the initial recognition exemption and the rule on measuring deferred tax at enacted or substantively enacted tax rates.

### 必背考點

#### A. Recognition（確認）

**A1. Current tax liabilities and current tax assets**
- Recognise a **current tax liability** for any unpaid current tax from the **current and prior periods** (HKAS 12.12). 考試伏位：唔係淨係計今年，往年未找清嘅稅都要入。
- If the amount **already paid** in respect of current and prior periods **exceeds** the amount due, the excess is recognised as a **current tax asset** (HKAS 12.13).
- A tax loss that can be **carried back** to recover current tax of a previous period is recognised as a **current tax asset**, because the benefit is probable and reliably measurable (HKAS 12.13–14).
- Journal entry (current tax):
  - Dr Income tax expense ｜ Cr Income tax payable （以 taxable income × 現行稅率計）

**A2. Temporary differences — 定義（HKAS 12.5）**
- **Temporary difference** = the difference between the **carrying amount** of an asset or liability in the statement of financial position and its **tax base** (HKAS 12.5).
- Arise from **timing differences** in recognising transactions/events under HKFRSs vs the Inland Revenue Ordinance (IRO); they **reverse over time**.
- Permanent differences（例如 dividend income not taxable under IRO、fines and penalties non-deductible）**never** give rise to temporary differences — 考試年年考呢個分別。

**A3. Deferred tax liabilities — recognition**
- A **deferred tax liability (DTL)** is the income tax payable in respect of a **taxable temporary difference** (HKAS 12.5). An entity recognises a DTL for **all** taxable temporary differences（無 probability 條件 — 呢點同 DTA 唔同，常見伏位）。
- Taxable temporary difference exists when（Exhibit 16.1）：
  - Asset: **Carrying amount > Tax base**；或
  - Liability: **Carrying amount < Tax base**。

**A4. Deferred tax assets — recognition criteria（HKAS 12.24, 34）**
- A **deferred tax asset (DTA)** is income tax recoverable in respect of a **deductible temporary difference**, the **carryforward of unused tax losses**, and the **carryforward of unused tax credits** (HKAS 12.5).
- DTA recognised **only to the extent it is probable** that sufficient future taxable income will be available to utilise the deductible temporary difference / unused tax loss / unused tax credit (HKAS 12.24, 34)。有 probable 測試 — 同 DTL 全面確認唔一樣。
- Deductible temporary difference exists when（Exhibit 16.2/16.6）：
  - Asset: **Carrying amount < Tax base**；或
  - Liability: **Carrying amount > Tax base**。

**A5. Initial recognition exemption（HKAS 12.15(b), 22(c), 24）**
- No DTL or DTA is recognised on a temporary difference arising on **initial recognition** of an asset/liability where the transaction:
  1. **is not a business combination**; and
  2. **affects neither accounting profit nor assessable/taxable profits** at the time of the transaction; and
  3. **does not give rise to equal taxable and deductible temporary differences**.
- Rationale（LP）：recognising deferred tax would adjust the carrying amount of the asset/liability and make the financial statements **less transparent**；禁止於 initial recognition 及其後任何時間確認。
- 經典例子：購入 land，無 capital allowance/depreciation deduction，tax base = Nil → TTD 存在但豁免適用（唔係 business combination、唔影響 accounting/taxable profit）。

#### B. Measurement（計量）

**B1. Accounting profit → Taxable income（轉換公式）**
- Accounting profit
  - **Plus** Non-deductible expenses（會計已計、稅務唔准扣）
  - **Minus** Deductible charges and allowances not recognised in accounting profit（稅務先扣，例如 capital allowance）
  - **Minus** Non-assessable income（會計已計、稅務唔使課稅，例如 dividend income）
  - **Plus** Assessable income not recognised in accounting profit
  - = **Taxable income**
- **Current tax expense = Taxable income × tax rate**（香港 profits tax 例子用 16.5%/15%，題目話事）。

**B2. Tax base（HKAS 12.5 指引）**
- **Asset**: Tax base = Carrying amount − future **Taxable** amounts + future **Deductible** amounts
- **Liability**: Tax base = Carrying amount − future **Deductible** amounts + future **Taxable** amounts
- 記法（LP 例子）：
  - Machine：Tax base = Cost − accumulated capital allowance already deducted（例如 cost 100、已扣 30 → TB 70）。
  - Trade receivables（已課稅銷售）+ ECL provision 20 → TB = 100 − Nil + 20 = **120**（TB > CA → DTD → DTA）。
  - Interest payable（paid 先可扣）→ TB = 100 − 100 = **Nil**。
  - Accrued fines and penalties（永不可扣）→ TB = 100 − Nil = **100**（= CA → **無** temporary difference — permanent difference）。

**B3. Deferred tax 計算 — 記住 closing balance vs movement**
- **DTL = Taxable temporary difference × tax rate**（= CA of asset − TB of asset，或 TB of liability − CA of liability）
- **DTA = Deductible temporary difference × tax rate**（= TB of asset − CA of asset，或 CA of liability − TB of liability）
- 計出嚟嘅係 **closing balance**；journal entry 記 **movement = closing − opening**：
  - DTL 增加 → deferred tax **expense** 增加；DTA 減少 → deferred tax **expense** 增加（相反方向就係 income）。
- **Income tax expense = current tax expense + deferred tax expense**（兩者分開計）。

**B4. Tax rate 選擇**
- Current tax：按 **the end of the reporting period 已生效（in effect）** 嘅稅率計量（HKAS 12.46）。
- Deferred tax：按 **預期資產變現／負債清償期間適用**、且於報告期末已 **enacted or substantively enacted** 嘅稅率計量（HKAS 12.47）。已立法但未來先生效嘅新稅率都要用（例如 15% → 10%，DTL 要重計：64,000 × 10%/15% = 42,667）。

#### C. Presentation & Journal Entries（本章 LP 以確認/計量為主，無獨立披露段落；以下為必考呈報同分錄）

- **Income tax expense = current tax expense + deferred tax expense**，於 statement of profit or loss 呈報；current tax liability/asset 與 deferred tax liability/asset 於 statement of financial position 呈報。
- Journal entries（全部 balance）：

| 情況 | Dr | Cr |
|---|---|---|
| 記 current tax | Income tax expense 140,250 | Income tax payable 140,250 |
| DTL 增加（例：movement 151,000） | Income tax expense – deferred 151,000 | Deferred tax liability 151,000 |
| DTA 增加（例：movement 217,000） | Deferred tax asset 217,000 | Income tax expense – deferred 217,000 |
| 稅率下調，重計 DTL（例：21,333） | Deferred tax liability 21,333 | Income tax expense – deferred 21,333 |
| 稅率下調，重計 DTA | Income tax expense – deferred | Deferred tax asset |

### 易混淆概念對比

**對比一：Accounting profit vs Taxable income**

| | Accounting profit | Taxable income |
|---|---|---|
| 計算依據 | HKFRSs（會計準則） | Inland Revenue Ordinance（稅例） |
| 報告去邊 | Financial statements（畀 investors/creditors） | Tax return（交畀 Inland Revenue Department） |
| Dividend income | Recognised when earned | Not taxable under IRO → 永久差異，**不會**產生 temporary difference |
| Warranty expense | Accrual basis（估計即入賬） | Deductible only **when paid** → timing 差異，產生 deductible temporary difference |
| Depreciation vs capital allowance | 按 useful life 折舊 | 按稅例 capital allowance → 差額屬 temporary difference，會 reverse |
| 考試伏位（點樣分辨） | 見到「never assessable / never deductible」= **permanent**，無 deferred tax | 見到「deductible when paid/incurred/written off」= **temporary**，要計 DTA/DTL |

**對比二：Taxable temporary difference vs Deductible temporary difference**

| | Taxable temporary difference (TTD) | Deductible temporary difference (DTD) |
|---|---|---|
| 未來效果 | 未來 taxable income ↑ → 未來多交稅 | 未來 taxable income ↓ → 未來慳稅 |
| Asset 情況 | Carrying amount **>** Tax base | Carrying amount **<** Tax base |
| Liability 情況 | Carrying amount **<** Tax base | Carrying amount **>** Tax base |
| 確認 | Deferred tax **liability**（全數確認，無 probable 測試） | Deferred tax **asset**（**only to the extent probable** 有足夠 future taxable income 可用，HKAS 12.24, 34） |
| 典型例子 | Capitalised development costs（稅務已全扣，TB = Nil）；accelerated capital allowance > depreciation | ECL allowance、warranty provision、annual leave provision（paid/incurred 先可扣） |
| 考試伏位 | 同學最易調亂 liability 方向：liability CA > TB 其實係 **DTA**（唔係 DTL） | 記住 JE 方向：DTL↑ 要 Cr DTL / Dr expense；DTA↑ 要 Dr DTA / Cr expense |

## Phase 2 閃卡

### Card 1
**Front:** Under HKAS 12, when must an entity recognise a current tax liability, and when a current tax asset?
**Back:**
- Current tax liability: for any **unpaid current tax** from the **current and prior periods** (HKAS 12.12).
- Current tax asset: when the amount **paid exceeds** the amount due for those periods (excess → current tax income); also for a **tax loss carried back** to recover current tax of a previous period (HKAS 12.13–14).
💬 白話：未找清嘅稅（唔單止今年，舊年欠嘅都計）就係 current tax liability；交多咗、或者 tax loss 可以 carry back 拎返舊稅，就係 current tax asset。

### Card 2
**Front:** What is the formula for the tax base of an asset? Apply it to trade receivables of HK$100 with a general ECL provision of HK$20 (provision not yet tax deductible; revenue already taxed).
**Back:**
- Tax base (asset) = Carrying amount − future taxable amounts + future deductible amounts.
- Trade receivables: HK$100 − Nil + HK$20 = **HK$120**.
- CA (100) < TB (120) → deductible temporary difference → deferred tax asset.
💬 白話：資產嘅 tax base 即係「將來稅務上仲有幾多可以扣」。ECL 而家唔准扣、將來 write off 先扣，所以 TB 高過賬面值 20，係 DTA。

### Card 3
**Front:** What is the formula for the tax base of a liability? Apply it to (i) interest payable of HK$100 deductible when paid, and (ii) accrued fines of HK$100 that are never deductible.
**Back:**
- Tax base (liability) = Carrying amount − future deductible amounts + future taxable amounts.
- (i) Interest payable: 100 − 100 = **Nil** → CA > TB → deductible temporary difference → DTA.
- (ii) Accrued fines: 100 − Nil = **HK$100** → CA = TB → **no temporary difference** (permanent difference).
💬 白話：負債 tax base = 賬面值減將來可扣嘅數。罰款永遠唔准扣，所以 TB 照等於 100，無差異 — 呢個係 permanent difference，考試好鍾意用嚟做 distractor。

### Card 4
**Front:** Complete the four identification rules: (a) asset CA > TB; (b) asset CA < TB; (c) liability CA > TB; (d) liability CA < TB.
**Back:**
- (a) Asset CA > TB → **taxable** temporary difference → DTL.
- (b) Asset CA < TB → **deductible** temporary difference → DTA.
- (c) Liability CA > TB → **deductible** temporary difference → DTA.
- (d) Liability CA < TB → **taxable** temporary difference → DTL.
💬 白話：資產睇 CA 大細好直覺；負債要反轉諗 — liability 賬面值大過 tax base 其實代表你將來有得扣（例如 provision），所以係 DTA。呢格係 panel report 年年話弱嘅位。

### Card 5
**Front:** What are the recognition criteria for a deferred tax asset under HKAS 12.24 and 12.34? How does this differ from a deferred tax liability?
**Back:**
- DTA recognised for deductible temporary differences, carryforward of unused tax losses and unused tax credits — **only to the extent it is probable** that sufficient future taxable income will be available to utilise them.
- DTL: recognised for **all** taxable temporary differences — no probability condition.
💬 白話：DTA 係「有望先好認」— 要 probable 有未來應課稅利潤先用得著；DTL 就「凡有 TTD 必認」，唔使過 probable 關。

### Card 6
**Front:** State the three conditions for the initial recognition exemption under HKAS 12.15(b), 22(c) and 24.
**Back:**
The transaction on initial recognition of the asset/liability:
1. is **not a business combination**;
2. affects **neither accounting profit nor assessable/taxable profits**; and
3. does **not give rise to equal taxable and deductible temporary differences**.
→ No DTL/DTA recognised, on initial recognition or subsequently.
💬 白話：三個條件齊中先豁免。經典考法：買 land 無得扣稅（TB = Nil），明明有 TTD，但因為唔影響會計/應課稅利潤又唔係 business combination，所以一世唔准認 DTL。

### Card 7
**Front:** At what tax rates are current tax and deferred tax measured under HKAS 12.46 and 12.47?
**Back:**
- Current tax: the rate **in effect at the end of the reporting period** (HKAS 12.46).
- Deferred tax: the rates **expected to apply** when the asset is realised / liability settled, based on rates **enacted or substantively enacted** by the end of the reporting period (HKAS 12.47).
- Rate change → restate deferred balances (e.g. DTL 64,000 at 15% → 64,000 × 10%/15% = 42,667 at 10%).
💬 白話：current tax 用「而家生效」嘅率；deferred tax 用「將來變現嗰陣」嘅率，但必須已經立法或實質立法。稅率變咗，舊嘅 DTA/DTL 要按比例重計。

### Card 8
**Front:** Give the journal entries for (a) an increase in a deferred tax liability of HK$151,000 and (b) an increase in a deferred tax asset of HK$217,000. What amount does the entry record — balance or movement?
**Back:**
- (a) Dr Income tax expense – deferred 151,000 ｜ Cr Deferred tax liability 151,000
- (b) Dr Deferred tax asset 217,000 ｜ Cr Income tax expense – deferred 217,000
- The entry records the **movement** (closing balance − opening balance), not the closing balance.
💬 白話：公式計出嚟係 closing balance，入賬記「變動」。方向口訣：DTL 升＝使多咗稅＝Dr expense；DTA 升＝慳咗稅＝Cr expense。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Current tax | 今期實際要交嘅稅（按 taxable income 計） | Current tax is the income tax payable on the taxable income for the current period. |
| Deferred tax | 因 timing 差異而產生嘅未來稅務後果 | Deferred tax captures the future tax consequences of recovering assets or settling liabilities. |
| Temporary difference | 賬面值同 tax base 嘅差異，會隨時間 reverse | A temporary difference is the difference between the carrying amount of an asset or liability and its tax base. |
| Tax base | 資產/負債喺稅務上嘅「賬面值」 | The tax base of the machine is its cost less accumulated capital allowances deducted. |
| Taxable temporary difference | 將來會令你多交稅嘅差異 → DTL | The excess of the carrying amount over the tax base of an asset is a taxable temporary difference. |
| Deductible temporary difference | 將來會令你慳稅嘅差異 → DTA | A warranty provision gives rise to a deductible temporary difference because the deduction arises only when paid. |
| Initial recognition exemption | 初次確認時符合三條件就唔准認 DTA/DTL | The initial recognition exemption prohibits recognising deferred tax on the acquisition of the land. |
| Enacted or substantively enacted rate | 已立法（或實質立法）嘅稅率 | Deferred tax is measured at tax rates enacted or substantively enacted by the end of the reporting period. |
