# M6 Chapter 10: Financial Assets, Financial Liabilities and Equity Instruments — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. Define a financial asset, a financial liability and an equity instrument in accordance with HKAS 32.
2. Classify financial instruments as financial liabilities or equity instruments from the issuer's perspective.
3. Classify and account for financial assets under the three HKFRS 9 measurement categories (amortised cost, FVOCI, FVTPL) using the business model and SPPI tests.
4. Apply the effective interest method to compute amortised cost and interest revenue/expense, and prepare the related journal entries.
5. Apply the three-stage expected credit loss (ECL) model and explain derecognition and offsetting requirements.

---

### 必背考點

#### A. Recognition 確認

| 考點 | Rule | Reference |
|---|---|---|
| 定義 | A **financial instrument** is any contract that gives rise to a **financial asset** of one entity and a **financial liability or equity instrument** of another entity (雙方要有「對稱」先算 financial instrument). | HKAS 32.11 |
| Financial asset | Cash; an equity instrument of another entity; a contractual right to receive cash/another financial asset or to exchange under potentially favourable conditions; certain contracts settled in the entity's own equity instruments (variable number to receive). | HKAS 32.11 |
| Financial liability | Contractual obligation to deliver cash/another financial asset, or to exchange under potentially **unfavourable** conditions; or a non-derivative settled in a **variable number** of the entity's own equity instruments. | HKAS 32.11 |
| Equity instrument | Any contract evidencing a **residual interest** in assets after deducting all liabilities; must have **no contractual obligation to deliver cash**, and if settled in own shares, the number must be **fixed** (variable number → financial liability). | HKAS 32.11 |
| Initial recognition | Recognise a financial asset/liability **when the entity becomes party to the contractual provisions** of the instrument（通常即簽約日，不是談判或達成口頭協議時）. | HKFRS 9.3.1.1 |

#### B. Measurement 計量

**Initial measurement (financial assets AND financial liabilities):**
- Initially measured at **fair value**. | HKFRS 9.5.1.1
- **Amortised cost / FVOCI** instruments: initial measurement **includes** directly attributable transaction costs.
- **FVTPL** instruments: transaction costs are **expensed to profit or loss immediately**（伏位：考生成日加埋交易成本入 FVTPL 資產）.
- Transaction costs = **incremental** costs directly attributable to acquisition/issue/disposal（內部固定人工如 funding manager salary 唔算 — 非 incremental）.

**Subsequent measurement of financial assets** — 取決於兩個測試 (HKFRS 9.4.1.1)：
1. **Business model test**: hold to collect / hold to collect and sell / not held to collect (HKFRS 9.B4.1.1–B4.1.6)
2. **SPPI test**: contractual cash flows are **solely payments of principal and interest** on principal outstanding（basic lending arrangement; interest 主要補償 time value of money + credit risk）(HKFRS 9.B4.1.7A)

| Category | Conditions | Measurement mechanics | Reference |
|---|---|---|---|
| **Amortised cost** | Business model = **hold to collect** AND cash flows pass **SPPI** | Effective interest method; interest revenue = opening gross carrying amount × EIR; gains/losses to P&L on derecognition / impairment | HKFRS 9.4.1.2; 9.5.7.2 |
| **FVOCI (debt)** | Business model = **hold to collect AND sell** AND passes **SPPI** | Carrying amount = **fair value**; interest revenue still on **amortised cost (EIR)** basis via P&L; FV movements to OCI; impairment gains/losses to P&L | HKFRS 9.4.1.2A; 9.5.7.10 |
| **FVTPL** | **Residual / fall-back** category: fails SPPI, or business model = hold to sell/trade | Fair value; **all** gains/losses (including interest effect) to P&L; transaction costs expensed day 1 | HKFRS 9.4.1.4; 9.5.7.1 |
| **FVOCI election (equity)** | **Irrevocable election at initial recognition** for equity instruments **not held for trading** | All FV changes to OCI; **dividends still to P&L**; **no recycling, no ECL impairment** | HKFRS 9.5.7.5; 9.5.7.1A; 9.B5.7.3 |

**Effective interest method (HKFRS 9.App A):**
- EIR = rate that exactly discounts estimated future cash flows over the expected life back to the **gross carrying amount**, adjusted for transaction costs, premiums and discounts.
- **Contractual (coupon) rate** → 決定實收/實付現金流；**EIR** → 決定 P&L 入賬嘅 interest revenue/expense。兩者通常唔同。
- Amortised cost 公式：Closing = Opening + (Opening × EIR) − Cash received/paid。

**Subsequent measurement of financial liabilities:**
- Default = **amortised cost** (effective interest method) | HKFRS 9.4.2.1
- Exceptions measured at **FVTPL**: liabilities designated at FVTPL on initial recognition; liabilities arising when a transfer of a financial asset does not qualify for derecognition; derivatives; financial guarantee contracts; below-market loan commitments; contingent consideration under HKFRS 3（後四項超出 module 範圍）.
- FVTPL-designated liabilities: FV change attributable to **own credit risk** → **OCI**；其餘 → P&L | HKFRS 9.5.7.7

#### C. Impairment — Expected Credit Loss Model 預期信貸虧損

- ECL provision (loss allowance) required for **all financial assets at amortised cost and debt instruments at FVOCI**；**equity instruments designated at FVOCI are exempt**. | HKFRS 9.5.5.1 / 9.5.5.2
- **Credit loss** = difference between contractual cash flows due and cash flows expected, discounted at the **original EIR**. (HKFRS 9.App A)
- Impairment loss/gain = amount needed to adjust the loss allowance to the required amount at the reporting date → recognised in **profit or loss**；SOFP 對應：amortised cost → loss allowance；FVOCI debt → equity. | HKFRS 9.5.5.8
- **Rebuttable presumption**: more than **30 days past due** → significant increase in credit risk. | HKFRS 9.B5.5.17

| Stage | Trigger | Loss allowance | Interest revenue basis |
|---|---|---|---|
| **Stage 1** | No significant increase in credit risk（初始通常入呢度）| **12-month ECL** | **Gross** carrying amount × EIR (HKFRS 9.5.5.3) |
| **Stage 2** | **Significant increase in credit risk**（如 credit rating downgrade、借款人盈利轉差、>30 days past due）| **Lifetime ECL** | **Gross** carrying amount × EIR (HKFRS 9.5.5.5) |
| **Stage 3** | **Credit-impaired**（如違約、破產 — events with detrimental impact on cash flows）| **Lifetime ECL** | **Net** carrying amount × EIR (HKFRS 9.5.5.11; 9.5.4.1(b)) |

考試伏位：Stage 1 即使有 lifetime ECL 估計，都只確認 **12-month ECL**；Stage 2 → Stage 3 唯一改變係 **interest revenue 由 gross 轉 net basis**。

#### D. Derecognition & Presentation 終止確認與列報

**Derecognition of financial assets** (HKFRS 9.3.2.3):
- Derecognise when (i) contractual rights to cash flows **expire**, or (ii) the asset is transferred AND **substantially all risks and rewards of ownership** are transferred. | HKFRS 9.3.2.6(a)
- On derecognition: difference between carrying amount and consideration received → **profit or loss**. | HKFRS 9.3.2.12
- **Transfer NOT qualifying**（e.g. sale with agreement to repurchase at fixed price / with recourse）: keep the asset, recognise a **separate financial liability** for consideration received, **no offsetting**; continue recognising income on asset and expense on liability. | HKFRS 9.3.2.6(b); 9.3.2.15

**Derecognition of financial liabilities**: when obligation is **discharged, expires or is cancelled**；difference between carrying amount and consideration paid → P&L. | HKFRS 9.3.3.1; 9.3.3.3

**Offsetting (Presentation)**:
- HKAS 1 generally **prohibits** offsetting assets and liabilities. | HKAS 1.32
- HKAS 32 requires offsetting (net presentation) only when **BOTH**: (1) a **currently legally enforceable right** to set off（contingent on future default = 唔算 currently enforceable）; AND (2) **intention to settle net**, or to realise the asset and settle the liability **simultaneously**. | HKAS 32.42; 32.43

*註：本章 LP 冇獨立 disclosure 章節；presentation/offsetting 要求（HKAS 32）即本章嘅列報考點。*

#### E. Key Journal Entries 必背分錄

**1. Purchase of bond at amortised cost (with transaction costs)**
```
Dr  Investment in bonds            (fair value + transaction costs)
    Cr  Cash                                    (total paid)
```

**2. Year-end interest — amortised cost bond bought at a PREMIUM (coupon > EIR interest)**
```
Dr  Cash                            (contractual coupon received)
    Cr  Investment in bonds                  (coupon − EIR interest)
    Cr  Interest revenue                     (opening × EIR)
```
*(If bought at a discount: Dr Cash (coupon), Dr Investment in bonds (EIR interest − coupon), Cr Interest revenue (opening × EIR).)*

**3. Purchase of equity shares at FVTPL**
```
Dr  Investment in shares           (fair value, excluding transaction costs)
Dr  Transaction costs (P&L)        (expensed immediately)
    Cr  Cash                                    (total paid)
```
Year-end FV gain: `Dr Investment in shares / Cr Fair value gain (P&L)`

**4. FVOCI debt — fair value adjustment (after EIR entries)**
```
Dr/Cr  Investment in bonds         (FV adjustment)
    Cr/Dr  Fair value movement (OCI)
```

**5. Raising an ECL loss allowance / stage migration**
```
Dr  Impairment loss (P&L)          (increase in required allowance)
    Cr  Loss allowance                          (SOFP contra to the financial asset)
```

**6. Factoring receivables WITHOUT recourse (qualifies for derecognition)**
```
Dr  Cash                           (consideration received)
Dr  Loss on transfer (P&L)         (carrying amount − consideration)
    Cr  Trade receivables                       (carrying amount)
```

**7. Bank loan drawdown (net of origination fee) and annual repayment**
```
Drawdown:
Dr  Cash                           (gross proceeds − origination fee)
    Cr  Bank loan                               (same amount = initial amortised cost)

Each repayment:
Dr  Interest expense               (opening × EIR)
Dr  Bank loan                      (cash paid − interest expense)
    Cr  Cash                                    (instalment paid)
```

---

### 易混淆概念對比

#### 表一：Amortised cost vs FVOCI (debt) vs FVTPL — financial assets

| 比較點 | Amortised cost | FVOCI (debt) | FVTPL |
|---|---|---|---|
| Business model | Hold to collect | Hold to collect **and sell** | Hold to sell / trading（或 fail SPPI 嘅任何 model）|
| SPPI test | Pass | Pass | **Fail → 必定 FVTPL**（不论 business model）|
| Transaction costs on initial recognition | 加入 carrying amount | 加入 carrying amount | **即時 expense 入 P&L** |
| Carrying amount | Amortised cost (EIR roll-forward) | **Fair value** | Fair value |
| Interest revenue | EIR × gross carrying amount → P&L | EIR × **amortised cost** basis → P&L（與 FV 無關）| 冇分開計；FV 變動已包含 |
| FV movements | 唔認（除 derecognition/impairment）| **OCI** | P&L |
| ECL impairment | Yes — loss allowance | Yes（debt；impairment 入 P&L）| **No**（FV 已反映）|

**點樣分辨（繁中）：** 問自己兩條問題——(1) 現金流係咪 SPPI？唔係就直接 FVTPL，唔使再諗 business model。(2) 係 SPPI 嘅話，睇 entity 係「收息持有」(amortised cost) 定「收息＋會賣」(FVOCI)。考試伏位：FVOCI debt 嘅 **interest revenue 仍然用 amortised cost 計**，唔好用 fair value opening balance 乘 EIR；FVTPL 嘅交易成本**唔可以資本化**。

#### 表二：ECL 三階段 vs Equity instrument FVOCI election

| 比較點 | Stage 1 | Stage 2 | Stage 3 | Equity designated at FVOCI |
|---|---|---|---|---|
| Trigger | 初始確認 / 冇顯著惡化 | Significant increase in credit risk（>30 days past due 有 rebuttable presumption）| Credit-impaired（違約、破產）| Irrevocable election，non-trading equity |
| Loss allowance | **12-month ECL** | **Lifetime ECL** | **Lifetime ECL** | **豁免 — 唔做 ECL** |
| Interest revenue basis | **Gross** carrying amount | **Gross** carrying amount | **Net** carrying amount | 唔適用（股息照入 P&L）|
| 對 P&L 影響 | 只認未來 12 個月預期損失 | 補足至 lifetime，差額入 P&L | 再調整至最新 lifetime 估計 | FV 變動全入 OCI，**永不 recycle** |

**點樣分辨（繁中）：** 記口訣「**12-Gross / Life-Gross / Life-Net**」。Stage 2 同 Stage 3 嘅 allowance 都係 lifetime ECL，分別只在 **interest revenue 計法**（gross vs net）——呢個係 examiner 最鍾意嘅伏位。另外唔好將「>30 days past due」直接當 Stage 3：佢只係 significant increase in credit risk 嘅 **rebuttable presumption**（Stage 2），除非有證據話已 credit-impaired。

---

## Phase 2 閃卡

### Card 1
**Front:** Define a financial instrument under HKAS 32 and state the three elements it can give rise to.

**Back:**
- Any contract that gives rise to a financial asset of one entity AND a financial liability or equity instrument of another entity (HKAS 32.11).
- Requires "symmetry" between the two parties; without it, not a financial instrument.
- Primary instruments (receivables, payables, bonds, shares) vs derivative instruments (derive value from another variable).

💬 白話解：一張合約要「一邊係資產、另一邊係負債或權益」先叫金融工具。只有一邊有嘢（例如单方面承諾）就唔係。

### Card 2
**Front:** From the issuer's perspective, how do you decide whether an instrument settled in the entity's own shares is equity or a financial liability?

**Back:**
- **Fixed number** of own shares for fixed consideration → **equity instrument** (holder bears residual price risk like ordinary shareholders).
- **Variable number** of own shares (e.g. to always deliver HK$100 worth of shares) → **financial liability** (holder faces no residual risk).
- Also check: any contractual obligation to deliver cash / exchange on potentially unfavourable terms → financial liability (HKAS 32.11).

💬 白話解：關鍵係「股數固定定浮動」。固定股數 = 持有人自己承受股價風險 = equity；浮動股數保證持有人實收金額 = 其實係還錢 = liability。

### Card 3
**Front:** When is a financial asset or financial liability first recognised, and at what amount?

**Back:**
- Recognised when the entity **becomes party to the contractual provisions** of the instrument — usually contract execution date, not during negotiations (HKFRS 9.3.1.1).
- Initial measurement at **fair value** (HKFRS 9.5.1.1).
- Add directly attributable transaction costs — **except** FVTPL instruments, where transaction costs are expensed immediately.

💬 白話解：簽咗約先確認，傾緊偈未算數。初始按公平值計；交易成本只有非 FVTPL 先可以加入去，FVTPL 要即時打落 P&L。

### Card 4
**Front:** State the two tests that determine the subsequent measurement category of a financial asset, and the three resulting categories.

**Back:**
- Test 1 — **Business model**: hold to collect / hold to collect and sell / not held to collect (HKFRS 9.B4.1.1–B4.1.6).
- Test 2 — **Contractual cash flow characteristics**: SPPI (solely payments of principal and interest) (HKFRS 9.B4.1.7A).
- Hold to collect + SPPI → **amortised cost** (HKFRS 9.4.1.2); hold to collect and sell + SPPI → **FVOCI** (HKFRS 9.4.1.2A); everything else → **FVTPL** (fall-back, HKFRS 9.4.1.4).

💬 白話解：先過 SPPI 關（唔過 = 直接 FVTPL），再問你係咪「坐住收息」。 Equity shares 嘅股息唔係 SPPI，所以預設一定係 FVTPL。

### Card 5
**Front:** Explain the difference between the contractual (coupon) interest rate and the effective interest rate (EIR), and how each is used.

**Back:**
- Coupon rate → determines the **cash flows** received/paid.
- EIR → rate that exactly discounts estimated future cash flows over the expected life to the **gross carrying amount**; determines **interest revenue/expense in P&L** (HKFRS 9.App A).
- EIR differs from coupon when the instrument is acquired/issued at a premium/discount or with transaction costs — these are amortised over the life via the EIR.
- Amortised cost roll-forward: Closing = Opening + (Opening × EIR) − Cash flow.

💬 白話解：票面息率管「收幾多現金」，EIR 管「P&L 認幾多息」。買債券有折讓/溢價/手續費，兩個率就會唔同，差額靠 EIR 喺年期內慢慢攤。

### Card 6
**Front:** What is the FVOCI election for equity instruments, and what are its consequences?

**Back:**
- **Irrevocable election at initial recognition** for investments in equity instruments **not held for trading** (HKFRS 9.5.7.5).
- Initial measurement = fair value **plus** transaction costs; all subsequent FV changes → **OCI** (HKFRS 9.5.7.1A).
- **Dividends** received still recognised in **profit or loss** (HKFRS 9.B5.7.3).
- **Exempt from ECL impairment**; no recycling of gains/losses.

💬 白話解：想避開 P&L 波動可以揀 FVOCI，但一揀唔准反口，而且只限唔係攞嚟買賣嘅股票。記住：股息照入 P&L，減值唔使做。

### Card 7
**Front:** Summarise the three stages of the HKFRS 9 expected credit loss model (trigger, loss allowance, interest revenue basis).

**Back:**
- **Stage 1**: no significant increase in credit risk → **12-month ECL**; interest on **gross** carrying amount (HKFRS 9.5.5.3).
- **Stage 2**: significant increase in credit risk (e.g. rating downgrade, deteriorating results, >30 days past due — rebuttable presumption, HKFRS 9.B5.5.17) → **lifetime ECL**; interest on **gross** carrying amount (HKFRS 9.5.5.5).
- **Stage 3**: credit-impaired (default, bankruptcy) → **lifetime ECL**; interest on **net** carrying amount (HKFRS 9.5.5.11; 9.5.4.1(b)).
- Movement in allowance → impairment loss/gain in P&L (HKFRS 9.5.5.8).

💬 白話解：口訣「12-Gross / Life-Gross / Life-Net」。Stage 轉換時 P&L 只認 allowance 嘅**變動額**，唔係成個 lifetime ECL。

### Card 8
**Front:** When may a transferred financial asset be derecognised, and what happens if the transfer does not qualify? When must financial assets and liabilities be offset?

**Back:**
- Derecognise when cash flow rights **expire**, or the transfer passes the **risks and rewards** test (substantially all transferred, e.g. factoring **without recourse**) — difference between carrying amount and consideration → P&L (HKFRS 9.3.2.3; 9.3.2.6(a); 9.3.2.12).
- Not qualified (e.g. sale with fixed-price repurchase / with recourse): **keep the asset**, recognise a **separate financial liability** for consideration received, **no offsetting** (HKFRS 9.3.2.6(b); 9.3.2.15).
- Offsetting only when **both**: (1) **currently** legally enforceable right of set-off; (2) intention to settle **net** or simultaneously (HKAS 32.42). HKAS 1.32 otherwise prohibits offsetting.

💬 白話解：賣斷（冇追索權）先可以 derecognise；有追索權 = 其實借錢，資產留低、另認負債。Offsetting 要「而家」就有法律權利＋真係打算淨額交收，得其一唔得。

---

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Financial instrument | 令一邊有金融資產、另一邊有金融負債或權益嘅合約 | A financial instrument is any contract that gives rise to a financial asset of one entity and a financial liability or equity instrument of another entity. |
| SPPI (solely payments of principal and interest) | 現金流純粹係本金加利息，即基本借貸安排 | The bonds pass the SPPI test because their contractual cash flows are solely payments of principal and interest on the principal amount outstanding. |
| Business model | Entity 管理金融資產嘅方式：收息持有、收息兼賣、定純粹買賣 | Because the entity holds the bonds to collect contractual cash flows, the business model test supports amortised cost measurement. |
| Effective interest rate (EIR) | 將未來現金流折返到賬面值嘅實際利率，用嚟計 P&L 利息 | The effective interest rate exactly discounts the estimated future cash flows to the gross carrying amount of the financial asset. |
| Amortised cost | 用 EIR 滾存嘅成本：期初＋EIR利息−現金流 | The closing amortised cost equals the opening balance plus interest at the effective interest rate less the coupon received. |
| Expected credit loss (ECL) | 按違約概率加權嘅預期現金短欠，按原 EIR 折現 | The entity recognised a loss allowance equal to 12-month expected credit losses at initial recognition. |
| Credit-impaired | 已發生對現金流有不利影響嘅事件（如違約、破產），即 Stage 3 | When the borrower entered bankruptcy, the loan became credit-impaired and was transferred to Stage 3. |
| Derecognition | 將已確認嘅資產/負債從財務狀況表移除 | The receivables were derecognised because substantially all risks and rewards of ownership were transferred to the factor. |
