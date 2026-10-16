# M6 Chapter 18: Effects of Changes in Foreign Exchange Rates — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. Define and distinguish **functional currency** and **presentation currency**, and explain the factors in HKAS 21 used to determine an entity's functional currency.
2. Define and classify **monetary items** and **non-monetary items** in accordance with HKAS 21.
3. Account for the **initial recognition** of foreign currency transactions using the spot exchange rate.
4. Apply the correct exchange rates to foreign currency monetary and non-monetary items at **subsequent reporting dates**, and account for the resulting exchange differences.
5. Prepare journal entries for unsettled foreign currency balances and for **settlement** of foreign currency monetary items.

> 範圍提示：LP 明確指出 **foreign operations 及 translation of financial statements into a presentation currency 不在 Module 6 範圍內**；本章焦點係 foreign currency transactions 嘅 recognition 同 measurement。LP 本章亦無講述 HKAS 21 嘅 disclosure requirements，考試準備以 recognition / measurement 規則為主。

### 必背考點

#### A. Recognition — 基本概念與確認

**1. Functional currency（HKAS 21.8）**
- Definition: the currency of the **primary economic environment** in which the entity operates — normally the one in which it **primarily generates and expends cash**.
- 三個 primary factors（HKAS 21.9）:
  1. The currency that **mainly influences sales prices** for goods and services (often the currency in which sales prices are denominated and settled);
  2. The currency of the country whose **competitive forces and regulations** mainly determine sales prices;
  3. The currency that **mainly influences labour, material and other costs** (often the currency in which costs are denominated and settled).
- Additional evidence（HKAS 21.10）: currency in which **financing activities** (debt/equity) are denominated; currency in which **receipts from operating activities are usually retained**.
- 如果 indicators mixed → management judgement（HKAS 21.12），**primary factors (HKAS 21.9) 優先**。

**2. Presentation currency（HKAS 21.8）**
- The currency **in which the financial statements are presented**. An entity may present its financial statements in **any currency** — 同 functional currency 可以唔同。

**3. Foreign currency transaction（HKAS 21.20–21.21）**
- A transaction **denominated in or requiring settlement in a foreign currency** (a currency other than the functional currency). Examples: purchases/sales priced in foreign currency; borrowing/lending denominated in foreign currency; acquisition/disposal of long-term assets in foreign currency; incurrence/settlement of foreign currency liabilities.
- **Initial recognition**: record in the functional currency by applying the **spot exchange rate at the date of the transaction**. Spot rate = exchange rate for **immediate delivery** (HKAS 21.8).

**4. Monetary vs non-monetary items（HKAS 21.8, 21.16）**
- **Monetary items**: units of currency held and assets/liabilities to be received or paid in a **fixed or determinable number of units of currency**. Examples: foreign currency cash holdings, trade and notes receivable/payable, accrued liabilities (interest payable, salaries payable), dividends payable, borrowings.
- **Non-monetary items**: essential feature = **absence** of a right to receive (or obligation to deliver) a fixed or determinable number of units of currency. Examples: prepaid expenses (prepaid rent/insurance), goodwill, intangible assets, inventories, property, plant and equipment, **share investments**, **unearned revenue**（已收錢但欠人服務，唔係欠固定金額）。

#### B. Measurement — Subsequent reporting dates

**1. Monetary items（HKAS 21.23(a), 21.28）**
- Translate at the **closing rate** (spot rate at the end of the reporting period, HKAS 21.8).
- Exchange differences (arising on translation at reporting date **or** on settlement) → **profit or loss** in the period in which they arise. 無論 realised 定 unrealised 都入 P/L。

**2. Non-monetary items（HKAS 21.23）**

| Measurement base | Exchange rate used |
|---|---|
| Historical cost | Rate at the **date of the transaction** (initial recognition) — no exchange difference arises |
| Fair value | Rate at the **date the fair value was measured** (usually closing rate at year-end) |

- Carrying amount 要跟相關準則（如 HKAS 16 cost model vs revaluation model）決定，再套用上述匯率。
- **HKAS 21.30**: when a gain/loss on a non-monetary item is recognised in **OCI** (e.g. revaluation surplus under HKAS 16), the **foreign exchange component** of that gain/loss is also recognised in **OCI**; if the gain/loss goes to **profit or loss**, the exchange component goes to **profit or loss** too（跟住宿主走）.

**3. Carrying amount determined by comparison（HKAS 21.25）— e.g. inventories under HKAS 2 (lower of cost and NRV)**
- Compare: (1) **cost/carrying amount** translated at the rate when that amount was determined (usually acquisition-date rate); vs (2) **NRV/recoverable amount** translated at the rate when that value was determined (usually **closing rate**).
- 結果可能係：外幣角度無減值，但 functional currency 角度要減值（或反之）— 一定要兩個數都轉做 functional currency 先好比較。

#### C. Disclosure
- LP 本章**未涵蓋** HKAS 21 嘅 disclosure requirements（亦無提供 paragraph references），foreign operations translation 同樣 out of scope。考試溫書以 Section A/B 規則為主；如 quiz/exam 問到 disclosure，用「本章 LP 無要求」心態處理，唔好自行吹噓。

#### D. Key Journal Entries（Dr/Cr，全部平衡）

Mini-scenario: HK company（functional currency HKD）buys goods on credit for **US$20,000** on 1 Nov 20X8 (spot HK$7.80 = US$1). Year-end 31 Dec 20X8: HK$7.85 = US$1. Settled 15 Jan 20X9: HK$7.83 = US$1.

**(1) Initial recognition — 1 Nov 20X8** (spot rate, HKAS 21.21)

| | Dr HK$ | Cr HK$ |
|---|---|---|
| Purchases / Inventories | 156,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;Trade payable (US$) | | 156,000 |

(US$20,000 × 7.80)

**(2) Year-end retranslation of monetary item — 31 Dec 20X8** (closing rate, HKAS 21.23(a), 21.28)
Liability = US$20,000 × 7.85 = HK$157,000 → increase HK$1,000 = exchange loss.

| | Dr HK$ | Cr HK$ |
|---|---|---|
| Loss on foreign exchange difference (P/L) | 1,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;Trade payable (US$) | | 1,000 |

**(3) Settlement — 15 Jan 20X9** (HKAS 21.28)
Pay US$20,000 × 7.83 = HK$156,600; recorded liability HK$157,000 → gain HK$400.

| | Dr HK$ | Cr HK$ |
|---|---|---|
| Trade payable (US$) | 157,000 | |
| &nbsp;&nbsp;&nbsp;&nbsp;Cash | | 156,600 |
| &nbsp;&nbsp;&nbsp;&nbsp;Gain on foreign exchange difference (P/L) | | 400 |

### 易混淆概念對比

**Table 1: Monetary items vs Non-monetary items**

| | Monetary items | Non-monetary items |
|---|---|---|
| Core feature | Right to receive / obligation to deliver a **fixed or determinable** number of currency units | **Absence** of such a right/obligation |
| Examples | Cash, trade receivables/payables, borrowings, interest payable, dividends payable | Inventories, PPE, goodwill, intangibles, prepayments, share investments, unearned revenue |
| Rate at reporting date | **Closing rate** (HKAS 21.23(a)) | Historical cost → transaction-date rate; Fair value → FV-measurement-date rate (HKAS 21.23) |
| Exchange difference | Always to **profit or loss** (HKAS 21.28) | Historical cost → none; FV → follows the gain/loss: OCI→OCI, P/L→P/L (HKAS 21.30) |
| 點樣分辨 / 考試伏位 | 問自己：「到期收到／付出嘅係咪固定金額嘅錢？」是 → monetary。**伏位**：unearned revenue 同 prepaid expenses 涉及現金已收付，但係欠貨/欠服務，屬 non-monetary；share investments 都係 non-monetary（唔係收固定現金嘅權利）。 | Historical cost non-monetary 年結**唔使重譯** — 好多同學誤用 closing rate 重譯存貨/機器，直接錯。 |

**Table 2: Functional currency vs Presentation currency**

| | Functional currency | Presentation currency |
|---|---|---|
| Definition | Currency of the **primary economic environment** in which the entity operates (HKAS 21.8) | Currency **in which the financial statements are presented** (HKAS 21.8) |
| How determined | Judgement based on HKAS 21.9 primary factors (sales prices; competitive forces/regulations; costs) + HKAS 21.10 secondary factors (financing; retained receipts) | **Free choice** — entity may present in any currency |
| Can they differ? | — | Yes — presentation currency may differ from functional currency |
| Role in this chapter | Defines what counts as a "foreign currency"; all transactions translated **into** it | (Translation into presentation currency is out of M6 scope) |
| 點樣分辨 / 考試伏位 | 考試鍾意畀 mixed indicators，記住 **HKAS 21.9 primary factors 優先**於 financing/retained receipts（HKAS 21.10, 21.12）。 | **伏位**：唔好以為「註冊地貨幣」= functional currency；亦唔好以為股東要求用 USD 出報表就改變 functional currency — 嗰個只係 presentation currency 嘅選擇。 |

## Phase 2 閃卡

### Card 1
- **Front:** Define "functional currency" and "presentation currency" under HKAS 21.8.
- **Back:**
  - Functional currency: the currency of the **primary economic environment** in which the entity operates (normally where it primarily generates and expends cash).
  - Presentation currency: the currency **in which the financial statements are presented**; the entity may choose **any** currency.
- 💬 白話：functional currency 係公司日常做生意「真正用緊」嘅錢；presentation currency 純粹係報表用咩錢嚟表達，可以揀，兩者可以唔同。

### Card 2
- **Front:** List the three primary factors in HKAS 21.9 for determining functional currency, and the two additional factors in HKAS 21.10.
- **Back:**
  - Primary (HKAS 21.9): (1) currency mainly influencing **sales prices**; (2) currency of the country whose **competitive forces and regulations** determine sales prices; (3) currency mainly influencing **labour, material and other costs**.
  - Additional (HKAS 21.10): currency of **financing activities**; currency in which **operating receipts are retained**.
  - If mixed → judgement, **primary factors given priority** (HKAS 21.12).
- 💬 白話：記口訣「賣嘢收咩錢、邊度競爭規管、成本使咩錢」，三個主要因素唔一致就用 judgement，但主要因素優先；融資貨幣只係輔助證據。

### Card 3
- **Front:** How is a foreign currency transaction recorded on initial recognition (HKAS 21.21)?
- **Back:**
  - Record in the **functional currency**;
  - Apply the **spot exchange rate at the date of the transaction**;
  - Spot rate = rate for **immediate delivery** (HKAS 21.8).
- 💬 白話：落簿嗰刻就用當日即期匯率折做 functional currency，唔好用年結率、唔好用平均率（M6 層面）。

### Card 4
- **Front:** Define monetary items (HKAS 21.8) and give four examples; give three examples of non-monetary items.
- **Back:**
  - Monetary: units of currency held + assets/liabilities receivable/payable in a **fixed or determinable number of units of currency**.
  - Examples: cash in foreign currency, trade receivables/payables, borrowings, dividends payable.
  - Non-monetary: inventories, PPE, goodwill/intangibles, prepaid expenses, unearned revenue, share investments.
- 💬 白話：分水嶺係「係咪收/付固定金額嘅錢」。Unearned revenue 同 prepayment 雖然涉及現金，但將來交嘅係貨/服務，所以係 non-monetary — 考試大伏。

### Card 5
- **Front:** State the accounting treatment of foreign currency monetary items at each reporting date (HKAS 21.23(a), 21.28).
- **Back:**
  - Translate using the **closing rate** (spot rate at end of reporting period);
  - Exchange differences → **profit or loss** in the period they arise;
  - Same P/L treatment for differences arising **on settlement**.
- 💬 白話：monetary item 年結要「重估」做 closing rate，匯兌差額（包括未實現）直接入 P/L；到真正找數嗰日再計一次差額，一樣入 P/L。

### Card 6
- **Front:** Which exchange rates are used for non-monetary items at subsequent reporting dates (HKAS 21.23)?
- **Back:**
  - Carried at **historical cost** → rate at the **date of the transaction** (no exchange difference arises);
  - Carried at **fair value** → rate at the **date the fair value was measured** (usually closing rate).
- 💬 白話：歷史成本項目「一鎚定音」，用買入日匯率，之後唔郁；fair value 項目就跟估值日匯率。考試最常考：cost model 嘅機器/存貨年結唔使重譯。

### Card 7
- **Front:** A revalued foreign-currency building (HKAS 16 revaluation model) increases in value, partly due to exchange rate movement. Where does the exchange component go (HKAS 21.30)?
- **Back:**
  - Revaluation gain/loss recognised in **OCI** → exchange component also in **OCI**;
  - Gain/loss recognised in **profit or loss** → exchange component also in **profit or loss**;
  - Exchange difference "follows" the recognition of the underlying gain/loss.
- 💬 白話：匯兌成分係「跟班」— 宿主（重估盈虧）去 OCI 佢就去 OCI，宿主去 P/L 佢就去 P/L，唔會自己獨立揀路。

### Card 8
- **Front:** Under HKAS 21.25, how is the carrying amount of foreign-currency inventory (lower of cost and NRV, HKAS 2) determined?
- **Back:**
  - Translate **cost** at the rate when that amount was determined (usually acquisition-date rate);
  - Translate **NRV** at the rate when that value was determined (usually **closing rate**);
  - Compare in functional currency → write-down may arise even if NRV > cost in foreign currency (or vice versa).
- 💬 白話：兩個數用唔同日嘅匯率各自折做 HKD 先好比較。外幣睇唔蝕唔代表 HKD 睇唔蝕 — 匯率跌可以「製造」一個減值，LP 嘅 EUR 存貨例就係咁。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Functional currency | 公司主要經濟環境日常用嘅貨幣（收支以咩錢為主） | The functional currency is the currency of the primary economic environment in which the entity operates (HKAS 21.8). |
| Presentation currency | 財務報表揀嚟表達嘅貨幣，可自由選擇 | An entity may present its financial statements in any presentation currency. |
| Spot exchange rate | 即期匯率，即時交收嘅匯價 | A foreign currency transaction is initially recorded using the spot exchange rate at the date of the transaction (HKAS 21.21). |
| Closing rate | 報告期末嘅即期匯率 | Foreign currency monetary items are translated at the closing rate at the end of the reporting period (HKAS 21.23(a)). |
| Monetary items | 將來收/付固定或可確定金額貨幣嘅項目 | Trade payables and borrowings are monetary items because they will be settled in a fixed number of currency units. |
| Non-monetary items | 冇固定貨幣收付權利/義務嘅項目 | Inventories and property, plant and equipment are non-monetary items under HKAS 21. |
| Exchange difference | 因匯率變動產生嘅折算差額 | Exchange differences on monetary items are recognised in profit or loss in the period in which they arise (HKAS 21.28). |
| Foreign currency transaction | 以功能貨幣以外貨幣計價或結算嘅交易 | A foreign currency transaction is denominated in, or requires settlement in, a currency other than the entity's functional currency. |
