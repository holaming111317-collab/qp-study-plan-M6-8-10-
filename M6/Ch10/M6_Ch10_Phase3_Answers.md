# M6 Chapter 10: Financial Assets, Financial Liabilities and Equity Instruments — Phase 3 Answers

### Q1 — Answer: B
**Model Answer (EN):** The preference shares are financial liabilities. Under HKAS 32, an instrument is a financial liability if the issuer has a contractual obligation to deliver cash or another financial asset to the holder. Crescent Bay Limited has an unconditional obligation to pay the 7% dividend (it cannot elect to withhold payment) and an obligation to redeem the shares at par for cash at a fixed date. Both features are contractual obligations to deliver cash, so the shares are classified as financial liabilities despite their legal form as "shares". Classification follows substance over legal form.

**解題思路（繁中）:** 關鍵係睇實質唔睇名。強制派息（non-discretionary）＋到期強制贖回 = 發行人有 contractual obligation to deliver cash，所以係 financial liability。A 錯：法律形式係「股」但經濟實質係債。C 錯：冇任何 equity 成分 — 股息同本金都係強制現金流出（compound instrument 分拆屬 module 範圍外，但呢度連部分權益都唔存在）。D 錯：由發行人角度，呢啲係 obligations，唔係 assets。考試伏位：discretionary dividend（可選擇唔派、唔累積）+ liquidation 時與普通股同級 → 先至係 equity。

**Rule Check:** HKAS 32.11 (definition of financial liability; equity instrument conditions)

**Common Trap（繁中）:** 見到「preference shares」個「share」字就直覺揀 equity — 考試專登用呢啲名實不符嘅工具考你 substance over form。

### Q2 — Answer: B
**Model Answer (EN):** The shares are equity instruments of another entity, so their cash flows are not solely payments of principal and interest; moreover they are held for trading. They must be measured at fair value through profit or loss (HKFRS 9.4.1.4). For FVTPL assets, initial measurement is at fair value **excluding** transaction costs, which are expensed immediately to profit or loss. Initial carrying amount = 20,000 × HK$12 = **HK$240,000**; the HK$3,000 brokerage fee is recognised in profit or loss.

**解題思路（繁中）:** 兩步：(1) 股票 cash flows 唔係 SPPI，兼且 held for trading → FVTPL；(2) FVTPL 嘅 transaction costs 唔可以資本化，要即時 expense。A 錯：將交易成本**扣除**（HK$240,000 − HK$3,000）— 方向錯，交易成本永遠唔會減少初始賬面值。C 錯：HK$243,000 係 amortised cost / FVOCI 嘅做法（fair value + transaction costs）— 呢個係最常見混淆。D 錯：HK$260,000（20,000 × HK$13）係用年結日公平值，但題目問**初始**確認，唔係後續計量。考試伏位：記住「FVTPL = 費用化；其餘兩類 = 資本化」。

**Rule Check:** HKFRS 9.5.1.1 (initial measurement at fair value); HKFRS 9.4.1.4 (FVTPL classification)

**Common Trap（繁中）:** 睇漏「held for trading」/「actively trading」呢啲字眼，或者背錯邊類先加交易成本 — FVTPL 唔加，amortised cost 同 FVOCI 先加。

### Q3 — Answer: B
**Model Answer (EN):** The bonds are measured at amortised cost (hold-to-collect business model + SPPI cash flows). Amortised cost roll-forward using the effective interest method:

| Year | Opening HK$ | Interest revenue (EIR 6.5%) HK$ | Coupon received (5% × 2,000,000) HK$ | Closing HK$ |
|---|---|---|---|---|
| 20X8 | 1,920,000 | 124,800 | (100,000) | 1,944,800 |
| 20X9 | 1,944,800 | 126,412 | (100,000) | **1,971,212** |

Workings: 20X8 interest = 1,920,000 × 6.5% = 124,800; closing = 1,920,000 + 124,800 − 100,000 = 1,944,800. 20X9 interest = 1,944,800 × 6.5% = 126,412; closing = 1,944,800 + 126,412 − 100,000 = **1,971,212**. The bonds were acquired at a discount, so the carrying amount accretes towards the HK$2,000,000 redemption value.

**解題思路（繁中）:** 貼士：折扣買入嘅債券，amortised cost 每年**上升**行向面值 — 可以即刻 sanity check 答案。A 錯：HK$1,944,800 只係第一年尾嘅結餘，做少咗一年。C 錯：HK$1,974,800 係用 EIR 乘**面值**（2,000,000 × 6.5% = 130,000；1,944,800 + 130,000 − 100,000）— EIR 要乘期初賬面值，唔係面值。D 錯：HK$2,044,800 係將成個 coupon 加落賬面值（1,944,800 + 100,000），冇分清「EIR 利息入 P&L」同「coupon 係現金收回」。考試伏位：coupon rate 決定現金流，EIR 決定 P&L — 兩個率唔好調亂。

**Rule Check:** HKFRS 9.4.1.2 (amortised cost criteria); HKFRS 9.App A (effective interest method definitions)

**Common Trap（繁中）:** 用 coupon rate 計 interest revenue，或者忘記第二年要用第一年嘅 closing balance 做 opening — 呢類 roll-forward 題一定要逐年推。

### Q4 — Answer: A
**Model Answer (EN):** The transfer qualifies for derecognition: Maple Grove Limited has transferred its rights to the cash flows and the bank assumes the full risk of non-collection with no recourse, so substantially all risks and rewards of ownership have been transferred (HKFRS 9.3.2.6(a)). On derecognition, the difference between the carrying amount and the consideration received is recognised in profit or loss (HKFRS 9.3.2.12):

- Dr Cash HK$760,000
- Dr Loss on transfer (profit or loss) HK$40,000
- Cr Trade receivables HK$800,000

(Dr total = Cr total = HK$800,000 — the entry balances.)

**解題思路（繁中）:** 無追索權（no recourse）= 銀行承受收唔到錢嘅風險 = risks and rewards 已轉移 = derecognise。B 錯：只留下 HK$40,000 應收喺賬上，冇反映成個轉讓，虧損冇入賬。C 錯：Dr Cash / Cr Loan 係「唔符合 derecognition」（例如有追索權、fixed-price repurchase）嘅處理 — 保留資產兼另認負債；但呢個 case 係無追索權，所以唔啱用呢個方法，呢個係最危險嘅 distractor。D 錯：現金實收只有 HK$760,000，唔可能 Dr Cash 800,000。考試伏位：見「with recourse / 須償還墊款」→ 唔 derecognise；見「no recourse / 對方承受壞賬風險」→ derecognise 兼認 loss/gain。

**Rule Check:** HKFRS 9.3.2.3; HKFRS 9.3.2.6(a); HKFRS 9.3.2.12 (derecognition and P&L on transfer); HKFRS 9.3.2.6(b) (transfers not qualifying)

**Common Trap（繁中）:** 混淆 qualifying 與 non-qualifying transfer 嘅分錄 — non-qualifying 係 Cr financial liability 兼唔准 offset；qualifying 係成個 Cr Trade receivables 走數，差額入 P&L。

### Q5 — Answer: C
**Model Answer (EN):** Statement C is correct. In Stage 1 (no significant increase in credit risk since initial recognition), the loss allowance is measured at an amount equal to **12-month expected credit losses**, and interest revenue is calculated by applying the effective interest rate to the **gross carrying amount** (before deducting the loss allowance). Statement A is wrong: Stage 2 requires lifetime ECL (not 12-month ECL) and interest is still on the gross carrying amount. Statement B is wrong: in Stage 3 interest revenue is calculated on the **net** carrying amount (gross less loss allowance). Statement D is wrong: the >30-days-past-due rule is only a **rebuttable presumption** of a significant increase in credit risk (Stage 2), not automatic credit-impairment (Stage 3).

**解題思路（繁中）:** 用口訣「12-Gross / Life-Gross / Life-Net」可以秒殺呢類題：Stage 1 = 12-month ECL + gross basis；Stage 2 = lifetime ECL + gross basis；Stage 3 = lifetime ECL + net basis。A 將 Stage 2 嘅 allowance 同 interest basis 都講錯。B 係 Stage 3 嘅 allowance 啱但 interest basis 錯（net 先啱）。D 係典型伏位：30 日逾期只係 significant increase in credit risk 嘅 **rebuttable presumption**，即預設入 Stage 2 而唔係 Stage 3；credit-impaired 要有實際違約/破產等 detrimental events。記住 Stage 2 同 Stage 3 唯一分別係 interest revenue 嘅計算基礎。

**Rule Check:** HKFRS 9.5.5.3 (Stage 1: 12-month ECL); HKFRS 9.5.5.5 (Stage 2: lifetime ECL); HKFRS 9.B5.5.17 (30 days past due rebuttable presumption); HKFRS 9.5.5.11 / 9.5.4.1(b) (Stage 3: interest on net carrying amount)

**Common Trap（繁中）:** (1) 以為 Stage 2 起 interest 就用 net basis — 其實 Stage 3 先轉 net；(2) 將 30 日逾期直接等同 credit-impaired；(3) 忘記 Stage 1 即使有 lifetime ECL 估計都只確認 12-month ECL。
