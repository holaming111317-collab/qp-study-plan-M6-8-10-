# M6 Chapter 2: Fair Value Measurement — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. **Define** fair value and **explain** the exit-price, market-based measurement principle in accordance with HKFRS 13.
2. **Determine** the principal (or most advantageous) market and **apply** the correct treatment of transaction costs and transport costs in fair value measurement.
3. **Select** appropriate valuation techniques (market / cost / income approach) and **classify** the inputs within the three-level fair value hierarchy.
4. **Apply** the highest and best use valuation premise to non-financial assets.
5. **Identify** the recurring and non-recurring fair value disclosure requirements of HKFRS 13.

### 必背考點

#### A. Recognition — 呢章其實唔講 recognition！
- **HKFRS 13 只講 "how to measure"，唔講 "when to measure"**：其他 HKFRSs（如 HKFRS 9、HKAS 16、HKAS 40）先決定邊啲資產/負債要按 fair value 計量；HKFRS 13 提供統一嘅計量框架（LP §2.1 引言）。考試問「邊個準則決定要唔要用 fair value」→ 唔係 HKFRS 13。
- **Fair value 定義（HKFRS 13.9）**："the price that would be received to sell an asset (or paid to transfer a liability) in an orderly transaction between market participants at the measurement date"。
- 兩大核心原則：
  - **Exit price**（賣出價），唔係 entry price（買入價）。
  - **Market-based measurement**，唔係 entity-specific measurement — 用 market participants 嘅假設，唔用自己公司嘅假設（無例外）。
- **Unit of account** 由其他準則決定，HKFRS 13 唔指定（stand-alone item vs group of assets/liabilities）。

#### B. Measurement rules（HKFRS 13 核心）
1. **Orderly transaction（HKFRS 13.A）**：假設交易前有一段時間曝光於市場做 marketing activities；**forced liquidation / distress sale 唔算**。
2. **Principal (or most advantageous) market（HKFRS 13.17–18, 13.19）**：
   - Entity 必須能夠 access 該市場 → 所以呢個判斷係 **entity-specific**（唔同公司對同一 item 可以有唔同 principal market）。
   - **Principal market** = greatest volume and level of activity 嘅市場（用 market-based volume，唔係 entity 自己嘅銷量）。
   - 有 principal market → 直接用嗰個市場嘅價；**只有冇 principal market 先**用 **most advantageous market**（扣除 transaction costs + transport costs 後 net proceeds 最高嘅市場）。
3. **Transaction costs vs Transport costs（考試必考伏位）**：
   - **Transaction costs**：**唔扣** — 唔係資產特性，係交易特性（只喺揀 most advantageous market 時先考慮）。
   - **Transport costs**：**要扣** — location 係資產特性（如 commodity）。
4. **Market participants 特徵（HKFRS 13.A）**：independent of each other / knowledgeable / able to enter into a transaction / willing (motivated but not forced)。
5. **Highest and best use（HKFRS 13.27–29）**：只適用於 **non-financial assets**；從 **market participants' perspective** 判斷，可以唔同於 entity 嘅 current use（LP 例子：工業地 HK$3m vs 住宅地 HK$3.6m → FV = HK$3.6m）。
6. **Valuation techniques（HKFRS 13.61–62）**：
   - **Market approach**（HKFRS 13.B5–B7）：comparables、market multiples（e.g. P/E ratio）；適用於 quoted shares、real estates。
   - **Cost approach**（HKFRS 13.B8–B10）：current replacement cost；適用於自用廠房設備（唔獨立產生現金流）；**唔適用於 financial assets**（金融資產唔可以「複製」）。
   - **Income approach**（HKFRS 13.B10–B30）：折現未來現金流（present value techniques）；適用於 unlisted equity、derivatives、investment properties、intangibles；multi-period excess earnings method 屬於 income approach。
   - **Choice（HKFRS 13.63）**：HKFRS 13 **冇**為估值技術設 hierarchy，亦唔指定用邊一種；複雜情況可以用多於一種。原則：**maximise observable inputs, minimise unobservable inputs**（HKFRS 13.61）。
7. **Fair value hierarchy（HKFRS 13.72–90, B35–B36）**：
   - **Level 1**：unadjusted quoted prices in active markets for **identical** assets/liabilities（**唔准調整**）。
   - **Level 2**：observable inputs other than Level 1（similar assets in active market、identical in inactive market、interest rates/yield curves）。
   - **Level 3**：unobservable inputs（e.g. entity's own cash flow projections）。
   - **分級規則**：成個 measurement 按 **lowest level of input that is significant to the entire measurement** 分類 — 用咗 Level 2 + 重大 Level 3 inputs → 成個歸 **Level 3 in entirety**；若 unobservable adjustment 唔重大 → 仍可歸 Level 2。
8. **Present value technique 元素（Exhibit 2.5）**：estimate future cash flows → expectations about variations in amount and timing → time value of money (risk-free rate) → price for bearing uncertainty (risk premium)。LP 例：expected cash flows HK$10,400 ÷ (1 + 2.5% + 1.5%) = **HK$10,000**。

**Key journal entries（注意：HKFRS 13 本身唔產生 journal entries；以下係其他準則要求按 FV 計量後嘅後續調整）**

| 情境 | Dr | Cr | 依據 |
|---|---|---|---|
| FVTPL 股票投資 FV 升 HK$200,000 | Dr Financial asset at FVTPL 200,000 | Cr Gain on fair value change (P&L) 200,000 | HKFRS 9 |
| Investment property FV 升 HK$500,000（fair value model） | Dr Investment property 500,000 | Cr Gain on fair value change (P&L) 500,000 | HKAS 40 |
| Investment property FV 跌 HK$300,000 | Dr Loss on fair value change (P&L) 300,000 | Cr Investment property 300,000 | HKAS 40 |

（每條 Dr = Cr，已平衡。FV 金額本身由 HKFRS 13 框架計量。）

#### C. Disclosure requirements（HKFRS 13.93）
- 區分 **recurring**（每個報告日都要計 FV）vs **non-recurring**（特定情況先觸發）fair value measurement。
- 兩者都要披露：period-end FV、所屬 hierarchy level、（Level 2 & 3）valuation techniques 及 inputs 描述、Level 3 quantitative information about significant unobservable inputs、Level 3 valuation processes description、non-financial asset highest and best use 同實際用途唔同嘅原因。
- **只有 recurring** 先額外要：Level 3 **reconciliation of opening to closing balances**、（Level 3 financial assets/liabilities only）quantitative effect of changes in unobservable inputs。
- **原則：Level 3 披露要求最重** — 愈靠 unobservable inputs，披露愈多。

### 易混淆概念對比

#### 對比一：Principal market vs Most advantageous market

| | **Principal market** | **Most advantageous market** |
|---|---|---|
| 定義（EN） | Market with the greatest volume and level of activity for the asset/liability | Market that maximises the amount received to sell (net of transaction costs AND transport costs) |
| 幾時用 | 只要存在就一定要用（priority） | **只有 absence of principal market 先用** |
| 考慮 transaction costs? | 搵市場時唔使 | 搵市場時要扣 |
| 點樣分辨（繁中） | 睇「邊個市場最旺」（market-based volume，唔係自己銷量） | 睇「邊個市場落袋最多」（net proceeds） |
| 考試伏位 | 題目俾咗交易量 → 一定有 principal market，即使另一市場價錢更好都唔准轉；計 FV 時記住 price − transport costs（唔扣 transaction costs） | 同學成日直接用淨價最高市場嘅 net proceeds 做 FV — 錯！揀市場先扣 transaction costs，計 FV 嗰陣唔扣 |

#### 對比二：Fair Value Hierarchy — Level 1 vs Level 2 vs Level 3

| | **Level 1** | **Level 2** | **Level 3** |
|---|---|---|---|
| Inputs（EN） | Unadjusted quoted prices in active markets for **identical** items | Observable inputs other than Level 1 (similar items / inactive markets / interest rates, yield curves) | Unobservable inputs (entity's own data, cash flow projections) |
| 可否調整 | **No adjustment allowed** | 可以調整（condition/location），但若調整基於重大 unobservable input → 降做 Level 3 | N/A |
| 典型例子 | HKEX 上市股票報價 | 同區類似物業每平方呎價、唔活躍市場嘅 identical item 報價 | Multi-period excess earnings method 嘅 forecast income 及 asset-specific discount rate |
| 披露要求 | 最輕 | 中（techniques + inputs） | 最重（reconciliation、quantitative info、valuation processes） |
| 考試伏位 | Real estate 幾乎永遠唔係 Level 1（冇 identical property）；「in entirety」規則 — 混用 inputs 時成個 measurement 歸最低而重大嘅 level，唔准拆開 | | |

## Phase 2 閃卡

### Card 1
**Front:** Define fair value in accordance with HKFRS 13, and state the two key principles derived from the definition.
**Back:**
- "The price that would be received to sell an asset (or paid to transfer a liability) in an orderly transaction between market participants at the measurement date" (HKFRS 13.9)
- Principle 1: fair value is an **exit price**, not an entry price
- Principle 2: fair value is a **market-based** measurement, not an entity-specific measurement
💬 白話解釋：Fair value = 「賣出去收到幾多錢」，唔係「買入嚟俾咗幾多」；而且要用市場參與者嘅諗法，唔可以用自己公司一廂情願嘅假設。

### Card 2
**Front:** What is an "orderly transaction" under HKFRS 13, and which transactions fail this test?
**Back:**
- A transaction that assumes **exposure to the market for a period before the measurement date** to allow for marketing activities (HKFRS 13.A)
- Fails: forced liquidation; distress sale (e.g. seller near bankruptcy); forced sale to meet regulatory requirements; outlier transaction prices
💬 白話解釋：「Orderly」即係有足夠時間慢慢搵買家；急住賤賣（near bankruptcy、被監管機構逼住賣）就唔係 fair value。

### Card 3
**Front:** How does an entity determine which market's price to use for fair value measurement?
**Back:**
- Step 1: consider only markets the entity **can access** at the measurement date (HKFRS 13.19) — entity-specific
- Step 2: identify the **principal market** = greatest volume and level of activity (market-based volume, not the entity's own volume) (HKFRS 13.17)
- Step 3: only if **no principal market exists**, use the **most advantageous market** = highest net proceeds after transaction costs and transport costs (HKFRS 13.18)
- Fair value = price in the selected market
💬 白話解釋：先問「我入到邊啲市場」，再問「邊個最旺」；最旺嗰個就係答案，就算隔籬市場價錢更靚都唔可以貪心轉場。

### Card 4
**Front:** How are transaction costs and transport costs treated in (a) identifying the most advantageous market and (b) measuring fair value?
**Back:**
- **Transaction costs** (e.g. brokerage fees): considered when **identifying** the most advantageous market, but **NOT adjusted** in measuring fair value — not a characteristic of the asset; transaction-specific
- **Transport costs**: considered in both — **adjusted** in measuring fair value because location is a characteristic of the asset
💬 白話解釋：口訣 —「運輸扣得，佣金唔扣得」。佣金係你點樣做交易嘅成本，同資產本身無關；搬運費就同資產喺邊度有關，所以要扣。

### Card 5
**Front:** What is the "highest and best use" premise, and to which assets does it apply?
**Back:**
- Applies to **non-financial assets only** (HKFRS 13.27)
- Fair value reflects a market participant's ability to generate economic benefits by using the asset in its **highest and best use** (or selling it to another market participant who would)
- Determined from **market participants' perspective** — may differ from the entity's current use (HKFRS 13.29)
- E.g. land used as factory worth HK$3m; worth HK$3.6m as residential site → FV = HK$3.6m
💬 白話解釋：塊地而家攞嚟起廠唔緊要，市場參與者覺得起樓最值錢，就按起樓嘅價值計 — 「物盡其用」嘅市場版。

### Card 6
**Front:** Name the three valuation approaches in HKFRS 13 and one typical application of each.
**Back:**
- **Market approach** — prices/multiples from transactions of identical or comparable items (e.g. quoted shares; P/E multiple for private company) (HKFRS 13.B5–B7)
- **Cost approach** — current replacement cost of service capacity (e.g. own-use plant and equipment); not applicable to financial assets (HKFRS 13.B8–B10)
- **Income approach** — convert future cash flows/income to a single current amount (e.g. present value of rental income for investment property) (HKFRS 13.B10–B30)
- HKFRS 13 sets **no hierarchy of techniques**; more than one technique may be used (HKFRS 13.63)
💬 白話解釋：三招 —「人哋賣幾錢」（market）、「重造要幾錢」（cost）、「將來賺幾錢折返今」（income）。準則唔逼你用邊招，但要盡用 observable inputs。

### Card 7
**Front:** Explain the three levels of the fair value hierarchy and the "in entirety" classification rule.
**Back:**
- **Level 1**: unadjusted quoted prices in active markets for identical items (no adjustment allowed)
- **Level 2**: observable inputs other than Level 1 (similar assets in active markets; identical items in inactive markets; interest rates, yield curves)
- **Level 3**: unobservable inputs (own cash flow projections)
- **In entirety rule**: if a measurement uses both Level 2 and significant Level 3 inputs → classify the **whole measurement as Level 3**; if the unobservable adjustment is insignificant → Level 2 (HKFRS 13.72–90)
- Priority: maximise observable inputs, minimise unobservable inputs (HKFRS 13.61)
💬 白話解釋：好似污染咁 — 一啲重大嘅 Level 3 不確定因素，足以令成個估值「降級」做 Level 3，唔可以話「一半 Level 2 一半 Level 3」。

### Card 8
**Front:** Distinguish recurring vs non-recurring fair value measurement disclosures under HKFRS 13.93.
**Back:**
- **Recurring** = FV measurement required at **each reporting date**; **non-recurring** = triggered only in particular circumstances
- Both: period-end FV; hierarchy level; valuation techniques/inputs (Levels 2–3); quantitative info on significant unobservable inputs (Level 3); valuation processes (Level 3); reasons if highest and best use differs from actual use
- **Recurring only**: Level 3 **reconciliation of opening to closing balances**; quantitative effect of changes in unobservable inputs (Level 3 financial assets/liabilities)
- More disclosure required for Level 3 measurements
💬 白話解釋：「次次都要計」嘅 FV 要多啲交代（特別係 Level 3 嘅期初對期末 reconciliation）；「偶然先計一次」嘅可以少啲。越靠估（Level 3），披露越多。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Fair value | 賣出價／有序交易下市場參與者之間嘅價 | Fair value is the price that would be received to sell an asset in an orderly transaction between market participants at the measurement date. |
| Exit price | 「離場價」（賣出收幾多），相對 entry price（買入俾幾多） | Fair value is an exit price, not the price paid to acquire the asset. |
| Orderly transaction | 有充足時間做市場推廣嘅正常交易，唔係割價求售 | A distress sale is not an orderly transaction and therefore does not reflect fair value. |
| Principal market | 成交量同活躍度最高嘅市場 | The principal market is the market with the greatest volume and level of activity for the asset. |
| Most advantageous market | 扣除交易及運輸成本後淨收入最高嘅市場（冇 principal market 先用） | In the absence of a principal market, fair value is measured using the price in the most advantageous market. |
| Highest and best use | 從市場參與者角度最有價值嘅用途（只限非金融資產） | The highest and best use of the land is residential development, which differs from its current industrial use. |
| Observable inputs | 有市場數據支持嘅輸入（Level 1–2） | Quoted prices for similar properties in an active market are observable inputs. |
| Unobservable inputs | 冇市場數據、靠自己內部估計嘅輸入（Level 3） | The entity's own cash flow projections are unobservable inputs classified within Level 3. |
