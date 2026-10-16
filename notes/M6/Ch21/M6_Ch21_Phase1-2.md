# M6 Chapter 21: Statement of Cash Flows — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. Explain the difference between operating, investing and financing activities in accordance with HKAS 7.
2. Describe the components of cash and cash equivalents and apply the definitions to classify items.
3. Calculate cash flows from operating activities under both the direct method and the indirect method.
4. Calculate cash flows relating to investing and financing activities (including disposals, acquisitions, borrowings and dividends).
5. Prepare a complete statement of cash flows for a single entity, including the required note disclosures for non-cash transactions.

### 必背考點

#### A. Recognition / Scope — 點解要有 Statement of Cash Flows
- **HKAS 1.10**: The statement of cash flows is a required component of a **complete set of financial statements**. 現金流量表係法定完整財報一部分，唔可以唔交。
- **HKAS 7 (objective)**: requires information about the **historical changes in cash and cash equivalents**, classified into **operating, investing and financing activities**. 考試伏位：佢係用 **cash basis**，其他財報用 accrual basis — accrual accounting choices (e.g. depreciation methods) 會 mask 咗賺錢能力，SCF 就係拆穿呢樣嘢。
- **HKAS 7.6 — definitions（必背原文）**:
  - **Cash** comprises **cash on hand and demand deposits**.
  - **Cash equivalents** are **short-term, highly liquid investments** that are **readily convertible to known amounts of cash** and subject to an **insignificant risk of changes in value**.
  - 白話：要「隨時攞到」+「金額肯定」+「價值唔會大上大落」。Listed shares、gold bullion、high-return money market fund 全部 **唔係**（price volatility = significant risk of value change）；3-month government bond / treasury bills / commercial papers / deposits at call 先係。
- **HKAS 7.6 — three categories**:
  - **Operating activities** — the **principal revenue-producing activities** of the entity and other activities that are **not** investing or financing.
  - **Investing activities** — acquisition and disposal of **long-term assets** and other investments **not included in cash equivalents** (examples: HKAS 7.16).
  - **Financing activities** — activities that result in changes in the **size and composition of the contributed equity and borrowings**.
  - 記憶法：Operating = 做生意本業；Investing = 長期資產/投資買賣；Financing = 股本+借貸變動（含 lease liability principal repayment）。

#### B. Measurement / Computation rules（逐條公式背）
**Direct method (HKAS 7.18–7.19)** — disclose major classes of gross cash receipts and payments:
- Cash receipts from customers = Net sales + Opening AR − Closing AR **(adjusted for bad debt write-offs — add back write-offs to closing AR)**
- Cash payments to suppliers = Net purchases + Opening AP − Closing AP，其中 Net purchases = COGS + Closing inventory − Opening inventory
- Cash payments to employees = Wages expense + Opening wages payable − Closing wages payable
- HKAS 7.19: **both methods permitted**, but the **direct method is encouraged**（考試鍾意出「required / mandatory」做錯誤選項）。

**Indirect method (HKAS 7.18)** — start from **profit before tax**, adjust for:
- **Add back non-cash expenses** (depreciation, amortisation)
- **Add back losses / deduct gains from non-operating activities** (e.g. disposal of PPE — the cash proceeds go to investing, so the gain/loss must be stripped out of operating)
- **Decrease in current operating assets → add; Increase → deduct**（receivables, inventory, prepayments）
- **Increase in current operating liabilities → add; Decrease → deduct**（payables, wages payable）
- ⚠️ **Interest payable and tax payable 唔計入 working capital 調整** — interest expense 同 interest paid、tax expense 同 tax paid 分開處理：
  - Indirect method: profit before tax **add back interest expense**，之後喺「Cash generated from operations」下面 separate line 扣 **interest paid** 同 **income tax paid**（LP Apply & Analyse 2 / 3 格式）。
- Cash paid for interest = Interest expense + Opening interest payable − Closing interest payable
- Cash paid for income taxes = Income tax expense + Opening income tax payable − Closing income tax payable（有 deferred tax 時要先拆出 current tax portion，見 LP Illustrative Example 8）
- **兩個 method 計出嚟嘅 net operating cash flow 一定相同**（LP: HK$716,350 兩邊一樣）。

**Investing (HKAS 7.16)**:
- Cash receipts from disposal of NCAs = NBV of disposed NCAs +/− Gains/(Losses) on disposal + Opening related receivable − Closing related receivable
- Cash payments for acquisition of NCAs = Closing NCA − Opening NCA (net of cost of disposals) − NCA acquired through non-cash transactions + Opening related payable − Closing related payable − Revaluation increases
- 伏位：**revaluation increase 同 share-for-asset acquisition 係 non-cash，要剔除**；lessee 嘅 new lease（ROU asset）亦係 non-cash。

**Financing**:
- Increase in share capital / borrowings accounts → cash inflow；decrease → repayment outflow；**interest accretion 係 non-cash**（要喺 reconciliation 剔返出嚟）。
- Cash paid for dividends = Opening RE +/− Net profit/(loss) − Closing RE + Opening dividends payable − Closing dividends payable − **Non-cash dividends (e.g. dividend reinvestment plan)**
- Lessee: cash payments for the **reduction of the outstanding lease liability** = **financing activities**（LP Exam Practice Q2；唔係 free choice）。

#### C. Disclosure requirements
- **HKAS 7.31**: Cash flows from **interest and dividends received and paid** shall each be **disclosed separately**, and classified **consistently from period to period**.
- **HKAS 7.33–7.34 — classification flexibility（非金融機構）**:
  | Item | Allowed classification |
  |---|---|
  | Interest paid | Operating **or** Financing |
  | Interest received | Operating **or** Investing |
  | Dividends paid | Operating **or** Financing |
  | Dividends received | Operating **or** Investing |
  （Financial institutions: interest paid/received & dividends received 通常全部歸 operating。）
- **HKAS 7.35**: Income tax cash flows → **operating activities**, unless specifically identifiable with financing/investing activities; **separately disclosed**.
- **HKAS 7.43**: Investing and financing transactions that **do not require the use of cash** (e.g. acquiring assets via a lease, acquiring an entity by issuing shares, debt-to-equity conversion) are **excluded from the statement of cash flows**, but relevant information must be **disclosed elsewhere (notes)**（HKAS 7.44 相關披露）。

#### D. Key journal entries（Dr/Cr 必須平衡）
1. **Cash purchase of PPE (investing outflow)**:
   - Dr Property, Plant and Equipment 500,000 / Cr Cash 500,000
2. **Disposal of equipment at a loss** (cost 500,000; accumulated depreciation 320,000; cash proceeds 150,000 → loss 30,000):
   - Dr Cash 150,000; Dr Accumulated Depreciation 320,000; Dr Loss on Disposal (P&L) 30,000 / Cr Equipment 500,000
   - SCF 影響：investing inflow = **cash proceeds HK$150,000**（唔係 NBV 180,000）；indirect method 要 add back loss 30,000。
3. **Dividend declared then paid**:
   - On declaration: Dr Retained Earnings 200,000 / Cr Dividends Payable 200,000（**no cash flow yet**）
   - On payment: Dr Dividends Payable 200,000 / Cr Cash 200,000（financing 或 operating outflow，視乎 policy）
4. **Issue of shares for cash (financing inflow)**: Dr Cash 800,000 / Cr Share Capital 800,000

### 易混淆概念對比

**Table 1 — Direct Method vs Indirect Method (HKAS 7.18–7.19)**

| 項目 | Direct method | Indirect method |
|---|---|---|
| Presentation | Major classes of **gross cash receipts and payments** (e.g. receipts from customers, payments to suppliers) | Starts from **profit before tax**, adjusted for non-cash items, non-operating gains/losses, working capital changes |
| Information shown | 逐條實收實付 | Reconciliation between profit 同 operating cash flow |
| HKAS 7 態度 | **Encouraged**（HKAS 7.19，資訊更有用）but **not mandatory** | Permitted alternative |
| Net operating cash flow 結果 | 兩者**一定相同** | 兩者**一定相同** |
| 考試伏位 | 記得 AR 要 adjust for bad debt write-offs；purchases 要由 COGS + Δinventory 推返 | Interest/tax payable **唔係** working capital 調整；gain on disposal 係 **deduct**（唔係 add back）；FVTPL fair value changes 係 non-cash（Jun 2025 panel 報告考生常錯） |

**Table 2 — Cash and Cash Equivalents vs 似是而非項目 (HKAS 7.6)**

| Item | Cash / Cash equivalent? | 點樣分辨（繁中） |
|---|---|---|
| Cash on hand / demand deposits / deposits at call | ✅ Cash | 隨時攞得，無價值變動風險 |
| 3-month treasury bills / short-term government bonds / commercial papers | ✅ Cash equivalent | Short-term + highly liquid + **insignificant** risk of value change |
| Listed equity shares | ❌ | 易賣 ≠ cash equivalent；股價波動 = significant risk of value change |
| Gold bullion / high-return money market fund | ❌ | 市場活躍但價格大幅波動 |
| Trade receivables / long-term bond investments | ❌ | 唔係 readily convertible to **known** amounts / 唔 short-term |
| 考試伏位 | — | 「Highly liquid」單獨一個條件**唔足夠**；必須同時滿足 short-term、convertible to known amounts、insignificant risk 三個條件 |

## Phase 2 閃卡

### Card 1
**Front:** According to HKAS 7.6, how are "cash" and "cash equivalents" defined?
**Back:**
- Cash = cash on hand + demand deposits
- Cash equivalents = short-term, highly liquid investments, readily convertible to **known** amounts of cash, subject to an **insignificant risk of changes in value**
💬 白話解釋：Cash 就係手頭現金同活期存款；cash equivalents 係嗰啲短期、隨時變返已知金額、價值又唔會大上大落嘅投資，例如 3 個月國庫券。記住三個條件要**同時**成立。

### Card 2
**Front:** How does HKAS 7.6 define the three categories of cash flows in a statement of cash flows?
**Back:**
- Operating activities — principal revenue-producing activities + anything not investing/financing
- Investing activities — acquisition/disposal of long-term assets and other investments not included in cash equivalents
- Financing activities — changes in size and composition of contributed equity and borrowings
💬 白話解釋：做生意本業收付 = operating；買賣固定資產同投資 = investing；發股、借錢、還債 = financing。分類睇**來源**，唔係淨睇流入定流出。

### Card 3
**Front:** What is the difference between the direct method and the indirect method under HKAS 7.18–7.19, and which does the standard encourage?
**Back:**
- Direct method: discloses major classes of gross cash receipts and payments (e.g. cash received from customers)
- Indirect method: adjusts profit or loss for non-cash transactions, deferrals/accruals, and items of income/expense associated with investing or financing cash flows
- Both permitted; **direct method is encouraged** (HKAS 7.19); net operating cash flow is identical under both
💬 白話解釋：Direct 係「流水賬」逐條列實收實付；indirect 係由利潤「還原」返做現金。考試陷阱：encouraged ≠ required，兩個方法答案一樣。

### Card 4
**Front:** Under the indirect method, what are the four types of adjustments made to profit before tax?
**Back:**
- Add back non-cash expenses (e.g. depreciation, amortisation)
- Add back losses / deduct gains from non-operating activities (e.g. disposal of PPE)
- Decrease in current operating assets → add; increase → deduct
- Increase in current operating liabilities → add; decrease → deduct
- (Interest payable and tax payable are NOT working capital adjustments — dealt with separately)
💬 白話解釋：口訣「非現金開支加返、非經營盈虧反轉、資產同現金反向、負債同現金同向」。Interest payable 同 tax payable 留返喺後面 separate lines 處理。

### Card 5
**Front:** How may interest paid, interest received, dividends paid and dividends received be classified under HKAS 7.31–7.34 (for non-financial institutions)?
**Back:**
- Interest paid: operating **or** financing
- Interest received: operating **or** investing
- Dividends paid: operating **or** financing
- Dividends received: operating **or** investing
- Each must be **disclosed separately** and classified **consistently** from period to period (HKAS 7.31)
💬 白話解釋：HKAS 7 喺利息同股息上有彈性，但兩大底線：分開披露、前後一致。Financial institutions 通常全部歸 operating。

### Card 6
**Front:** How are income tax cash flows classified under HKAS 7.35, and how is cash paid for income taxes computed?
**Back:**
- Classified as **operating activities**, separately disclosed, unless specifically identified with financing/investing activities
- Cash paid for income taxes = Income tax expense + Opening income tax payable − Closing income tax payable
- With deferred tax: strip deferred tax movement out of total tax expense first to get current tax
💬 白話解釋：稅預設歸 operating。有 deferred tax 嗰陣，total tax expense 入面嘅 deferred portion 係 non-cash，要剔走先計到真係交咗幾多稅。

### Card 7
**Front:** How are non-cash investing and financing transactions treated under HKAS 7.43? Give three examples.
**Back:**
- **Excluded** from the statement of cash flows
- Disclosed elsewhere in the financial statements (notes)
- Examples: acquisition of assets by entering into a lease; acquiring an entity/assets by issuing shares; conversion of debt to equity
💬 白話解釋：冇現金郁動就唔可以入 SCF，但係要喺 notes 話俾人知。考試常見：新租賃嘅 ROU asset、以股換資產，記住喺計 purchase of PPE 時要剔除。

### Card 8
**Front:** State the formulas for (a) cash receipts from disposal of non-current assets and (b) cash paid for dividends.
**Back:**
- (a) Cash receipts from disposal = NBV of disposed NCAs +/− Gain/(Loss) on disposal + Opening related receivable − Closing related receivable
- (b) Cash paid for dividends = Opening retained earnings +/− Net profit/(loss) − Closing retained earnings + Opening dividends payable − Closing dividends payable − Non-cash dividends
💬 白話解釋：賣資產收幾多錢 = 賬面值加減盈虧，再調整未收到嘅 receivable；派息要先由 retained earnings 推返「宣派咗幾多」，再扣未付嘅 payable 同以股代息。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Statement of cash flows | 現金流量表：講解期內現金及現金等價物點樣變動 | The statement of cash flows classifies cash flows during the period into operating, investing and financing activities. |
| Cash equivalents | 現金等價物：短期、高流動性、價值變動風險極低嘅投資 | A three-month treasury bill qualifies as a cash equivalent under HKAS 7.6. |
| Operating activities | 經營活動：公司本業嘅創收活動 | Cash received from customers is classified as a cash flow from operating activities. |
| Investing activities | 投資活動：買賣長期資產同其他投資 | Cash paid to purchase property, plant and equipment is an investing cash outflow. |
| Financing activities | 融資活動：改變股本同借貸規模嘅活動 | Proceeds from the issue of shares are presented as cash flows from financing activities. |
| Direct method | 直接法：逐項列出大額現金收入同支出 | Under the direct method, major classes of gross cash receipts and payments are disclosed. |
| Indirect method | 間接法：由稅前利潤調整返去經營現金流 | Under the indirect method, depreciation is added back to profit before tax because it is a non-cash expense. |
| Non-cash transactions | 非現金交易：唔涉及現金，唔入 SCF 但要喺附註披露 | Acquiring equipment by issuing shares is a non-cash transaction excluded from the statement of cash flows under HKAS 7.43. |
