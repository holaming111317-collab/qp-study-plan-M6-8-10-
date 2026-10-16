# M8 Chapter 7: Audit Procedures for Specific Balances and Transactions — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. **Apply** tests of control and substantive procedures (tests of details and substantive analytical procedures) to each major business cycle — revenue, purchases, payroll, inventory, receivables, bank and cash, payables, non-current assets, provisions, leases and related parties.
2. **Map** each audit procedure to the financial statement assertion(s) it verifies, and identify the direction of testing (existence vs completeness).
3. **Evaluate** the design of external confirmation requests (trade receivables, trade payables, bank) in accordance with HKSA 505 *External Confirmations*, including follow-up procedures for non-responses and doubts over reliability.
4. **Explain** the auditor's responsibilities when attending a physical inventory count under HKSA 501 *Audit Evidence – Specific Considerations for Selected Items*.
5. **Determine** the audit implications (including potential modification of the auditor's opinion) when accounting treatments contravene HKFRS 15, HKAS 2, HKFRS 9, HKAS 16, HKAS 38, HKAS 37, HKFRS 16 or HKAS 24 (Revised).

---

### 必背考點

#### A. Assertions — 每個 major balance 嘅 key assertions（背熟！考試年年考 mapping）

| Balance / Transaction | Key Assertions | 主要測試方向 |
|---|---|---|
| Revenue (HKFRS 15) | Cut-off, Accuracy, Completeness, Occurrence | 主要防 overstated revenue（fraud risk：bonus、covenants） |
| Purchases / Expenses | Completeness（最主要）、Accuracy、Cut-off | 防 understated purchases/expenses → cost of sales understated |
| Payroll | Accuracy, Completeness, Occurrence | Fraud risk：'ghost' employees；年結 accrual（paid in arrears） |
| Inventories (HKAS 2) | **Valuation, Existence, Completeness, Rights and obligations** | 主要防 overvalued → overstated current assets + gross profit |
| Receivables (HKFRS 9 ECL) | **Valuation and Existence** | 防 overstatement（連帶 revenue overstatement — Dr Receivables Cr Revenue） |
| Bank and Cash | **Existence and Valuation** | Window dressing 令 bank + payables understated |
| Tangible non-current assets (HKAS 16) | Existence, Valuation, Completeness, Rights and obligations | 防 incorrectly capitalised / under-depreciation / revaluation 出錯 |
| Intangible assets (HKAS 38) | Existence, Valuation | 防 contravene HKAS 38 而 capitalise（如 internally generated goodwill） |
| Payables and Accruals | **Completeness**（liabilities 嘅焦點永遠係 completeness） | 防 understated liabilities → overstated profit |
| Provisions (HKAS 37) | Completeness, Valuation, Rights and obligations, Presentation | 防 understated / incomplete；disclosure 唔足 |
| Non-current liabilities | Completeness, Classification (current vs non-current split per HKAS 1) | Loan split 錯 → current 同 non-current 齊齊 misstated |
| Leases (HKFRS 16) | Valuation, Completeness, Presentation and disclosure | ROU asset / lease liability 計錯；interest rate implicit in the lease 用錯 |
| Related parties (HKAS 24 (Revised) / HKSA 550) | Presentation and disclosure, Completeness | 防 non-disclosure / concealment（fraud risk factor） |

**點樣記：** Liabilities 永遠主攻 **completeness**（怕少記）；Assets 永遠主攻 **existence + valuation**（怕多記/值錯）；Revenue 主攻 **occurrence + cut-off**（怕假數/跳期）。

#### B. Audit Procedures — assertion ↔ procedure mapping（核心考點）

**B1. Revenue（HKFRS 15）**
- Inspect a sample of GDNs immediately **before and after year-end** → recorded in correct accounting period（**cut-off**）。
- Recalculate sales discounts and sales tax on a sample of sales invoices（**accuracy**）。
- Select a sample of GDNs → agree to sales invoices → follow through to inclusion in the sales day book（**completeness**）。
- Inspect **post-year-end credit notes**, trace to GDN and invoice; if relates to pre-year-end sale, ensure reversed（**occurrence**）。
- Recalculate **contract liability**（unearned service revenue）at year-end and agree with the statement of financial position（**completeness and accuracy**）。Service revenue 只可以喺 contractual obligations 履行時先 recognise。
- Analytical：compare revenue with prior year / budget / industry；calculate **gross profit margin (gross profit/sales × 100)** and investigate significant fluctuations；**proof in total**。
- Tests of control：credit limit checks、fictitious order rejection、GDN matched to invoice before invoicing、invoice approval、standing data amendment authorisation。

**B2. Purchases / Expenses**
- Inspect **GRNs** immediately pre- and post-year-end → correct period（**cut-off**）。
- Sample of purchase orders → agree to GRNs and purchase invoices → through to inclusion in the purchases day book（**completeness**）。
- Recalculate invoice values including discounts / sales tax（**accuracy**）。
- Inspect **unmatched GRNs not yet invoiced** → agree to schedule of accruals（**completeness**）— goods received but not invoiced 要做 accrual。
- Analytical：category-by-category comparison with prior year and budget；gross profit margin + operating margin cross-check（margin 一升一跌可能代表 classification error：overheads 誤入 cost of sales 或 capital items 誤入 repairs）。
- Gross profit margin 異常上升嘅原因：revenue overstated（cut-off 錯）、purchases incomplete、closing inventory overvalued、opening inventory 錯。

**B3. Payroll and Directors' Emoluments**
- Agree total wages and salaries per payroll system with trial balance / general ledger / financial statements（**completeness and presentation**）。
- Cast monthly payroll reports；recalculate gross and net pay for a sample（**accuracy**）。
- Sample of joiners and leavers → agree start/leave dates with first/last payroll run（**accuracy**）。
- Reperform employment tax calculations（**accuracy**）；agree year-end tax accrual with payroll records and post-year-end payment（**occurrence**）。
- Agree total net pay per payroll records with bank transfer listing and cash book（**occurrence**）。
- Analytical：**proof in total**（prior year payroll + joiners/leavers + annual pay increase）vs actual。
- Tests of control：authorisation of time sheets/overtime、log of amendments to standing data、Board minutes approval of bonuses、segregation of duties、supervised clocking-in/out。
- Directors' emoluments：schedule split into wages/bonuses/benefits/pension → agree with FS disclosures；inspect Board minutes；obtain **written representation** that all emoluments disclosed（**completeness**）。Disclosure 唔足 → opinion 可能要 modified。

**B4. Inventories（HKAS 2 — lower of cost and NRV）**
- Attend the year-end inventory count（**HKSA 501** requires attendance where inventory is material, unless impracticable）。
- Sample from **count sheets → physical inventory**（**existence**）；sample from **physical inventory → count sheets**（**completeness**）。
- Agree sample of inventory items to purchase invoices for cost（**valuation**）。
- Inspect **post-year-end sales invoices** to determine NRV; compare NRV with cost → lower of cost and NRV（**valuation**）。
- Use CAATs to age inventory → identify slow-moving items needing allowance（**valuation**）。
- Trace goods received immediately pre-year-end to payables and inventory records；trace goods despatched pre-year-end OUT of inventory（**completeness and existence** — cut-off）。
- Third-party inventory：obtain external confirmation of quantity and condition（**rights and obligations**）；if material, attend the third party's count（**existence and completeness**）。
- Analytical：inventory days / inventory turnover vs prior year；gross profit margin vs prior year。
- Standard costs (HKAS 2 allows)：obtain breakdown, agree sample to invoices, discuss update frequency, inspect variance reports。
- **Consignment stock**：legal ownership stays with the **principal**；agent's FS 唔可以 include；risk = client includes stock it does not own → overstated inventory。Auditor enquires how consignment stock is segregated。

**Inventory count 三階段（HKSA 501）：**
- **Before**：obtain count instructions and assess effectiveness；review prior-year working papers；establish locations and third-party holdings；consider circularising third-party warehouses；consider need for experts。
- **During — Tests of control**：non-warehouse staff count（segregation of duties）；counted items flagged；no movements during count（24/7 client → segregate despatches/deliveries to a different location and count separately）；count sheets in numerical sequence；two people per team；damaged/obsolete items segregated；count sheets must NOT show expected quantities。
- **During — Substantive**：test counts both directions；inspect condition for damage/obsolescence（valuation）；record last deliveries pre-year-end。
- Auditor's objectives：**evaluate management's instructions and procedures; observe the count; inspect the condition of inventory; perform test counts**。注意：count 係 client 嘅責任，auditor 唔係去幫手數！
- **Perpetual inventory counts**：全年輪住數；auditor 要 attend at least one count、inspect exceptions、仍要做 cut-off + NRV 測試。

**B5. Receivables and Prepayments（HKFRS 9 ECL）**
- Obtain aged receivables listing, cast, agree total with FS（**valuation and presentation**）；agree receivables ledger control account with list of balances（**completeness and existence**）。
- **Inspect post-year-end cash receipts** → trace to pre-year-end balances（**rights and obligations and existence**）— 亦係 valuation 嘅 key evidence。
- Assess reasonableness of **expected credit loss allowance** per HKFRS 9；discuss aged balances with credit control manager（**valuation**）。
- Sample of year-end balances → agree back to GDNs and sales orders（**existence**）。
- Inspect customer correspondence for disputed items（**existence, valuation, rights and obligations**）。
- Inspect listing for **credit balances** → reclassify to payables（**classification**）。
- Analytical：**trade receivables days** vs prior year（**completeness and valuation**）。
- **Trade receivables confirmation**（HKSA 505）：
  - Client prepares letter on **client's letterhead**；**auditor sends it**；customer replies **directly to the auditor**。
  - **Positive** request：reply whether agree or disagree。**Negative** request：reply only if disagree — 只係 **risk of material misstatement is low** 先用得。
  - ⚠️ Confirmation **does NOT test valuation** — 只 verify **existence and rights and obligations**。就算 customer 確認咗都唔代表佢找得起 → 要做 post-year-end cash receipts testing 補 valuation。
  - **Follow-up**：non-response → second letter / phone call (with client's permission) / alternative procedures（post-year-end cash receipts testing）。
  - Doubts about reliability（HKSA 505.A11）：response not received directly / not from intended party → obtain further evidence（e.g. telephone the respondent to verify an email response）。**Oral responses are NOT external confirmations** — request written response direct to auditor; if none, seek other evidence。
- Prepayments：inspect cash book/bank statements that payment made；inspect invoices that goods/services not yet received；recalculate prepaid amount；compare with prior year。

**B6. Bank and Cash**
- Two key sources of evidence：**bank confirmation letter** + **year-end bank reconciliation**。
- Obtain all bank reconciliations, cast, agree cash book balance with TB/FS（**accuracy, valuation and allocation**）。
- Agree bank confirmation letter balance with year-end reconciliation；agree bank statement balance with original statement（**accuracy, valuation and allocation**）。
- Trace **outstanding payments** to post-year-end bank statement and note clearing date（**+ completeness**）；trace **outstanding lodgements** to pre-year-end cash book and post-year-end statement（**+ existence**）。
- Examine **old unpresented cheques** — write back if no longer valid（**completeness**）。
- Inspect bank confirmation letter for **security pledged / legal right of set-off**（**presentation and rights and obligations**）；亦可以發現 unrecorded loans（**completeness of liabilities**）。
- **Window dressing**：payment made immediately AFTER year-end 當作 year-end 前已付 → bank balance 同 payables 齊齊 understated。Auditor 要求 client add back to payables and remove from the bank reconciliation；唔改 + material → **modified opinion**。
- Bank confirmation request contents：company name; details of current/deposit/loan accounts; account numbers; currency; collateral; contingent liabilities; year-end (audit confirmation) date; authority to disclose date; contact name (engagement partner); audit firm contact details。Bank 要 client permission；auditor 喺 year-end 前提早幾星期直接寄畀 bank。
- Physical cash count（if cash material）：count petty cash, agree with FS（**accuracy, valuation, existence**）；check insurance cover for large cash balances。

**B7. Financial Instruments and Investments**
- Fair value exercise 高風險；auditor 唔可以幫 client 做 valuation，但要 evaluate 估值者嘅 **qualifications, experience, competence, independence and objectivity**；assumptions/methodologies 同往年一致；controls over the valuation。
- 有疑慮 → use an auditor's expert per **HKSA 620 *Using the Work of an Auditor's Expert***。
- Derivatives（e.g. forward foreign currency contracts）：remeasure to fair value through profit or loss；agree contracted rates with the contract；agree FV gain/loss with P&L；check no set-off of financial assets/liabilities unless legal right of set-off。
- Financial liabilities：confirm material loans with lender；recalculate interest accruals；examine loan agreements for covenant compliance；inspect security。

**B8. Tangible Non-current Assets（HKAS 16）**
- Cast non-current assets register, agree totals with FS, agree opening balances b/f（**completeness, classification, presentation**）。
- Sample **from register → physically inspect** assets（**existence**）；sample **physical assets → register**（**completeness**）。Inspect for damage/impairment indicators（**valuation**）。
- Additions：agree cost to supplier invoice（**valuation**）；invoice in company's name（**rights and obligations**）；confirm capital in nature not repairs（**existence**）。
- Properties：inspect **title deeds** in company's name（**rights and obligations**）。
- Revaluation：inspect valuation report; agree to GL/FS; ensure **all assets in the same asset class revalued** — no cherry-picking；**HKAS 16.31** requires revaluations with sufficient regularity that carrying amount does not differ materially from fair value。Revaluation gain → **revaluation reserve via OCI**，唔係 P&L。
- Depreciation：recalculate charge for a sample；**proof in total** per asset category（analytical）；review profits/losses on disposal — large loss suggests **under-depreciation**（policy too long）；assess useful lives vs asset replacement cycle。
- Tests of control：Board authorisation of capital expenditure；approval of disposals；reconciliation of register reviewed；insurance cover adequate。

**B9. Intangible Assets（HKAS 38）**
- Recognition criteria（**HKAS 38.21(a), (b)**）：(a) **probable** that expected future economic benefits will flow to the entity；(b) **cost can be measured reliably**。
- **Internally generated goodwill 永遠唔可以 recognise**（no active market → cost cannot be reliably measured）。
- **Research costs must always be expensed**；只有 development costs 符合 criteria 先可以 capitalise。
- Procedures：inspect purchase documentation / licence agreements（existence, rights and obligations, valuation）；inspect specialist valuer's reports；assess indicators of impairment；for development costs — discuss project with management, inspect project plans and budgets, inspect Board minutes；recalculate amortisation。

**B10. Payables and Accruals**
- Obtain trade payables listing, cast, agree with GL and FS；reconcile purchase ledger control account with listing（**completeness**）。
- **Supplier statement reconciliations** — key completeness procedure; supplier statement 係 external evidence，可靠。
- Inspect **post-year-end payments** relating to current year → agree to purchase ledger / accruals schedule（**completeness**）。
- Review **post-year-end invoices** relating to current year → agree to accruals schedule（**completeness**）。
- Sample of GRNs immediately pre- and post-year-end → pre-year-end included in payables, post-year-end excluded（**completeness of payables and cut-off of purchases**）。
- Inquire of management re unrecorded liabilities（**completeness**）。
- Inspect purchase ledger for **debit balances** → consider reclassification to receivables/prepayments（**classification**）。
- **Trade payables confirmation**：verifies **completeness and existence**；less common than receivables confirmation（因為 supplier statements 已係好證據）；懷疑 unrecorded liabilities 時要 include **regular suppliers with small or nil balances**；confirmation **唔可以單獨作為 sufficient appropriate evidence**。
- Analytical：total payables vs prior year；trade payables days vs prior year。

**B11. Provisions（HKAS 37）**
- Recognition criteria（**HKAS 37.10**）：(1) **present obligation as a result of a past event**；(2) payment **probable**（more likely than not）；(3) amount can be **estimated reliably**。全部符合先 recognise provision。
- Payment 只係 **possible** → **contingent liability**：disclose in notes（唔入帳）；remote → 唔使披露。
- **Reimbursement asset**：只有 receipt **virtually certain** 先可以 recognise（higher hurdle than probable）；probable → disclose contingent asset。
- Rare exception（**HKAS 37.92**）：disclosure would seriously prejudice the entity in a dispute → disclose general nature of dispute + fact and reason for non-disclosure（extremely rare）。
- Procedures：obtain breakdown of provisions, cast, agree to GL/FS；discuss with directors / inspect supporting docs for present obligation；inspect Board minutes for probability；recalculate provision components；review post-year-end cash book for payments；**obtain confirmation from lawyers**（with client's permission）or inspect legal correspondence；review legal expenses account in GL for unidentified claims；review FS disclosures for HKAS 37 compliance；obtain **written representation** that provision appropriately valued and complete。
- 應 recognise 而無 recognise / 應 disclose 而無 disclose，material → modified opinion（qualified 'except for' if material but not pervasive）。

**B12. Non-current Liabilities**
- Split loan between current（≤1 year）and non-current（>1 year）per **HKAS 1**；split 錯 → current liabilities overstated、non-current understated、distorts liquidity ratios（current ratio）。
- Recalculate interest charge and accrual；inspect cash book for repayments；agree balances with original loan statement and **bank confirmation letter**（completeness — 可以發現 unrecorded loans）；inspect loan agreements for **restrictive covenants** — breach 可能令 loan immediately repayable → reclassify to current。

**B13. Capital and Reserves**
- 香港公司喺 Companies Ordinance 下 **no longer have share premium**（無面額制度）— shares issued above former par value → 全部入 share capital。
- Revaluation gain：Dr Property, plant and equipment / Cr Revaluation reserve。
- **Dividends**：只在 **legal obligation** 存在時（declared at or before reporting date）先可以 recognise as liability；declared after year-end → 唔可以認；dividends 永遠係 movement on reserves（statement of changes in equity），**唔係 P&L expense**。
- Procedures：agree share capital with statutory documents；agree share issue proceeds with cash book/bank statements；inspect Board minutes for share issues and dividend declarations；recalculate dividend based on dividend per share；agree dividend to post-year-end cash book。

**B14. Leases（HKFRS 16）**
- Lessee：recognise **right-of-use (ROU) asset + lease liability** at commencement；exemption（optional）for **short-term (<12 months)** and **low-value** leases（tablets, PCs, small office furniture, telephones）。
- ROU asset = lease liability at initial measurement + payments at/before commencement − lease incentives received + initial direct costs + estimated dismantling costs。
- Lease liability = PV of unpaid lease payments using **interest rate implicit in the lease**；subsequent：b/f + interest − payments ± remeasurement。
- ROU asset depreciated per **HKAS 16 cost model** over earlier of end of useful life and end of lease term。
- Procedures：agree prior-year lease liabilities b/f；cast lease schedule；obtain lease agreements and **recalculate ROU asset and lease liability**；reperform closing liability roll-forward（opening − payments + interest at implicit rate）；agree depreciation charge with P&L；review disclosures for HKFRS 16 and HKFRS 7 compliance。

**B15. Related Parties（HKAS 24 (Revised) / HKSA 550）**
- HKSA 550.2：related-party relationships/transactions may give rise to **higher risks of material misstatement** than unrelated parties — complex structures；systems ineffective at identifying related-party transactions；transactions may not be at market terms（甚至無 consideration）。
- Risk assessment stage：engagement team discussion；inquire of management（identity of related parties, nature of relationships, transactions, controls）；professional scepticism throughout。
- During audit：agree sample of transactions to supporting docs and check **market rates**；review prior-year working papers；review **public register** for directors' other interests；review accounting records for large/unusual transactions around year-end；review loan confirmations for related-party guarantors；review tax returns and lawyers' correspondence；inspect bank confirmation letter。
- **Previously unidentified related party discovered** → inform the engagement team as soon as possible；request management identify all transactions with them；inquire why controls failed；perform substantive procedures；revisit risk assessment；if intentional non-disclosure → **fraud risk factor**（HKSA 240）。
- **Written representation**（must obtain）：management have disclosed the identity of all related parties and all related-party relationships/transactions of which they are aware, and have appropriately accounted for and disclosed them per HKAS 24 (Revised)。

#### C. Evidence — 邊啲 evidence 最強
- **External confirmations**（HKSA 505）：trade receivables / trade payables / bank confirmation letters — 由第三方直接回覆 auditor，可靠性高；auditor 必須 maintain control（見 Card 5）。
- **Supplier statements**：external evidence，比 client 內部記錄可靠。
- **Written representations**（directors' emoluments、provisions、related parties）：internal evidence，只係補充，唔可以取代其他 procedures。
- 如果 procedures 攞唔到 sufficient appropriate evidence，alternative procedures 又唔得 → **limitation of scope** → 可能 modify opinion。

#### D. Ethics 相關要點（本章範圍）
- Payroll 係 sensitive area — auditor 必須保持 **confidentiality**。
- Auditor **must not carry out the fair value valuation for the client**（只能 evaluate 證據）— 避免 self-review 威脅；需要時用 auditor's expert（HKSA 620）。
- 使用 client 嘅 investment manager / valuer 嘅工作前，必須評估其 **independence and objectivity**、qualifications、competence。
- Related-party 非自願披露 / 管理層刻意隱瞞 → fraud risk factor → HKSA 240。

#### E. Report Modifications 觸發點（本章情境）
| 情境 | 結果 |
|---|---|
| Material misstatement 唔肯改（e.g. 唔肯做 ECL allowance、window dressing 唔改、HKAS 37 應披露唔披露、related party 唔披露） | Modified opinion — 通常 **qualified 'except for'**（material but not pervasive）+ Basis for Modified Opinion paragraph after Opinion paragraph |
| Directors' emoluments disclosure 唔符合準則/法例 | Auditor's opinion may be modified |
| 攞唔到 sufficient appropriate evidence + 無 alternative procedures | Limitation of scope → modified opinion |

---

### 易混淆概念對比

#### 對比 1：Existence vs Completeness — 測試方向倒轉就零分

| | Existence | Completeness |
|---|---|---|
| 問題 | 帳面記錄係咪真係存在？（防 overstatement） | 存在嘅嘢係咪全部入咗帳？（防 understatement） |
| 測試方向 | **Records → Physical/Source**（由帳面揀 sample 追到實物/原始文件） | **Physical/Source → Records**（由實物/原始文件追返入帳） |
| Inventory count | Sample from **count sheets → physical inventory** | Sample from **physical inventory → count sheets** |
| Non-current assets | Sample from **register → physically inspect asset** | Sample **physical assets → inspect register** |
| Receivables | Year-end balances → agree to GDNs/sales orders；confirmation | Control account vs listing；receivables days analytical |
| Payables | Supplier statement reconciliation | GRNs pre-year-end → included in payables；post-year-end payments/invoices testing |
| 點樣分辨 | 問自己：「起點係帳面定實物？」帳面出發 = existence | 實物/文件出發 = completeness |
| 考試伏位 | Panelist 年年鬧 mismatch：用 physical → records 答 existence 係錯；liabilities 主攻 completeness，唔好寫 existence procedures 落 payables | Confirmation of receivables **唔 test valuation**；唔好以為確認咗餘額 = 收得返 |

#### 對比 2：Provision vs Contingent Liability vs Contingent Asset / Reimbursement（HKAS 37）

| | Provision | Contingent Liability | Contingent Asset / Reimbursement |
|---|---|---|---|
| 門檻 | Present obligation from past event + payment **probable**（more likely than not）+ **reliable estimate**（HKAS 37.10） | Payment only **possible**，或唔能夠 reliably measure | Inflow **probable** → disclose；recognise reimbursement asset 只在 **virtually certain** |
| 處理 | **Recognise** in the statement of financial position | **Disclose** in notes（remote 就唔使披露） | Probable → **disclose** only；virtually certain → **recognise** asset |
| 考試伏位 | 唔可以為未來支出設 provision（無 past event obligation）；35%/40% 勝算唔係 probable → 唔可以 recognise | Material 而唔披露 → qualified 'except for' opinion；HKAS 37.92 嘅 non-disclosure exception 係 extremely rare | 「virtually certain」門檻高過「probable」；provision 同 reimbursement asset **唔可以 offset** |

---

## Phase 2 閃卡

### Card 1
**Front:** What are the four key assertions for revenue, and which single procedure verifies cut-off?

**Back:**
- Assertions: **cut-off; accuracy; completeness; occurrence**.
- Cut-off procedure: **inspect a sample of goods despatched notes (GDNs) immediately before and after year-end and ensure they have been recorded in the correct accounting period**.
- Related risk: overstated revenue via premature recognition or fictitious sales (fraud risk — bonuses, loan covenants).

💬 白話解釋：Revenue 嘅四大 assertion 要背到好似自己名咁。Cut-off 測試一定係攞年結前後嘅 GDN 嚟睇，唔係睇 invoice date——因為 HKFRS 15 係睇 control 幾時轉移。記住「GDN 前後對」五個字。

### Card 2
**Front:** When must the auditor attend the client's physical inventory count, and what are the auditor's four primary objectives at the count?

**Back:**
- **HKSA 501** requires attendance when inventory is **material** to the financial statements (unless impracticable).
- Objectives: (1) **evaluate management's instructions and procedures** for the count; (2) **observe** the client's staff performing the count; (3) **inspect the condition** of the inventory; (4) **perform test counts**.
- The count itself is the **client's responsibility** — the auditor never performs the count.

💬 白話解釋：考試常見伏位係「auditor 去盤點係為咗做盤點」——錯！Auditor 係去評估 client 嘅指示同程序、觀察、檢查存貨狀況、做 test counts。盤點永遠係管理層嘅責任。

### Card 3
**Front:** During an inventory count, the auditor (i) selects items from the count sheets and traces them to the physical inventory, and (ii) selects physical items and traces them to the count sheets. Which assertion does each direction verify?

**Back:**
- (i) Count sheets → physical inventory: **existence**（帳面有嘅嘢真係存在）。
- (ii) Physical inventory → count sheets: **completeness**（實物有嘅嘢全部入咗帳）。
- Same logic applies to non-current assets (register → asset = existence; asset → register = completeness).

💬 白話解釋：口訣：「由紙到貨 = existence；由貨到紙 = completeness」。起點決定 assertion，呢個係 examiner 最鍾意玩嘅 direction trap。

### Card 4
**Front:** Which assertions does a trade receivables confirmation verify, which assertion does it NOT verify, and what compensating procedure addresses that gap?

**Back:**
- Verifies: **existence and rights and obligations** only.
- Does **NOT** verify: **valuation** — a customer agreeing the balance is owed does not mean the customer can pay.
- Compensating procedure: **post-year-end cash receipts testing** (inspect post-year-end cash receipts and trace to pre-year-end balances); also assess the **expected credit loss allowance per HKFRS 9** and discuss aged balances with the credit controller.

💬 白話解釋：客人認數 ≠ 客人找得起數。所以 confirmation 永遠唔可以單獨依靠，一定要配搭期後收款測試同 ECL 評估。呢個係 LP 嘅 Key Learning Point，考試好鍾意考「NOT」題。

### Card 5
**Front:** Per HKSA 505, how does the auditor maintain control over external confirmation requests?

**Back (HKSA 505.7 — four elements):**
1. **Determining the information** to be confirmed or requested;
2. **Selecting the appropriate confirming party**;
3. **Designing the confirmation requests**, including determining that requests are properly addressed and contain return information for responses to be sent **directly to the auditor**;
4. **Sending the requests**, including follow-up requests when applicable, to the confirming party.

Extra points: the letter is prepared by the client on the client's letterhead but sent by the auditor; replies go direct to the auditor, never via the client (reduces risk of client interference). Doubts about reliability (HKSA 505.A11) → obtain further evidence, e.g. telephone the respondent to verify an emailed response; oral responses are NOT external confirmations.

💬 白話解釋：成個 confirmation 過程 auditor 要「揸 fit」：揀人、設計封信、親自寄、直接收回。Client 只負責出信紙。任何經 client 手嘅回覆都不可靠，要再攞證據。

### Card 6
**Front:** What is 'window dressing' in the audit of bank and cash, and how should the auditor respond?

**Back:**
- Definition: treating a payment made **immediately after the reporting date** as if it was made **at or before year-end** (e.g. included as an unpresented payment in the year-end bank reconciliation).
- Effect: **understates** a positive bank balance (or overstates an overdraft) **and understates trade payables** — the statement of financial position looks healthier than reality.
- Auditor's response: ask the client to **add the payment back into trade payables and remove it from the bank reconciliation**; if refused and material → **modified auditor's opinion** (material misstatement).
- Detection: review the cash book for large or unusual items around year-end; trace outstanding payments to post-year-end bank statements and note clearing dates.

💬 白話解釋：Window dressing 即係「扮靚個年結」——將 1 月先過數嘅 payment 當 12 月已付，銀行存款同應付賬齊齊縮水。記住調整方向：payables 加返上去，reconciliation 剔走。

### Card 7
**Front:** State the HKAS 37 recognition criteria for a provision, and the different thresholds for a contingent liability and a reimbursement asset.

**Back:**
- Provision (recognise): **present obligation as a result of a past event** + payment **probable** (more likely than not) + amount can be **estimated reliably** (HKAS 37.10).
- Contingent liability: payment only **possible** (or not reliably measurable) → **disclose in notes**; remote → no disclosure.
- Reimbursement asset: recognise only if receipt is **virtually certain** (higher hurdle than probable); if probable → disclose as a contingent asset.
- Provision and reimbursement asset must **not be offset**.
- HKAS 37.92: disclosure may be withheld only in **extremely rare** cases where it would seriously prejudice the entity in a dispute — disclose general nature + fact/reason for non-disclosure.

💬 白話解釋：三級門檻：probable → 入帳；possible → 披露；virtually certain → 先可以認資產。記住資產嘅門檻係最高嘅，因為會計上對收益/資產保守啲。35% 勝訴率 = possible，只可以披露 contingent liability。

### Card 8
**Front:** What are the HKAS 38 recognition criteria for an intangible asset, and which common item is specifically prohibited from recognition?

**Back:**
- Recognition criteria (HKAS 38.21(a), (b)): (a) it is **probable** that the expected future economic benefits attributable to the asset will flow to the entity; and (b) the **cost of the asset can be measured reliably**.
- **Internally generated goodwill** can **never** be recognised — no active market exists, so cost cannot be reliably measured.
- **Research costs must always be expensed**; only development costs meeting the criteria may be capitalised.
- Audit procedures: inspect purchase documentation/licence agreements (existence, rights and obligations, valuation); assess impairment indicators; recalculate amortisation over useful economic life.

💬 白話解釋：HKAS 38 兩道閘：經濟利益 probable + 成本可靠計量。Internally generated goodwill 因為無 active market 計唔到可靠成本，所以永遠禁認。Research 一律費用化，development 達標先可以資本化——呢個對比係必考位。

---

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Goods despatched note (GDN) | 出貨單——證明貨已送出嘅文件，cut-off 測試主角 | The auditor inspected GDNs immediately before and after year-end to verify the cut-off assertion for revenue. |
| Goods received note (GRN) | 收貨單——採購/應付賬 completeness 測試嘅起點 | Unmatched GRNs not yet invoiced were agreed to the schedule of accruals to verify completeness. |
| External confirmation | 外部確認函——第三方直接回覆 auditor 嘅證據 | Under HKSA 505, the auditor must maintain control over external confirmation requests, including sending the requests. |
| Cut-off | 截數分期——交易有冇記喺正確會計期間 | Tracing GDNs around year-end to sales invoices provides evidence that sales were recorded in the correct accounting period. |
| Window dressing | 粉飾年結——將期後付款假裝成年結前付款 | Including a post-year-end payment run as an unpresented payment understates both the bank balance and trade payables. |
| Net realisable value (NRV) | 可變現淨值——存貨按 cost 同 NRV 孰低計量 | The auditor compared post-year-end selling prices with cost to ensure inventory was held at the lower of cost and NRV per HKAS 2. |
| Proof in total | 整體合理性測算——用預期值同實際數比較嘅分析程序 | The auditor performed a proof in total of the payroll expense, incorporating joiners, leavers and the annual pay increase. |
| Supplier statement reconciliation | 供應商對賬單調節——外部證據，驗證應付賬 completeness | Supplier statement reconciliations were agreed with the purchase ledger balances and reconciling items were investigated. |
