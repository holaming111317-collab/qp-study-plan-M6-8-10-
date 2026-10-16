# M6 Chapter 12: Non-current Assets Held for Sale and Discontinued Operations — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
1. **Describe** the classification criteria for a non-current asset (or disposal group) to be classified as held for sale or held for distribution to owners under HKFRS 5.
2. **Define** a disposal group and distinguish assets within / outside the measurement scope of HKFRS 5.
3. **Apply** the measurement rules of HKFRS 5: measure at the lower of carrying amount and fair value less costs to sell, cease depreciation, and allocate impairment losses / reversals correctly.
4. **Define and identify** a discontinued operation and explain why an abandoned asset is never classified as held for sale.
5. **Present and disclose** non-current assets held for sale and discontinued operations in the statement of financial position and statement of profit or loss and other comprehensive income.

### 必背考點

#### A. Recognition（Classification 分類準則）

| 考點 | 規則 | 出處 |
|---|---|---|
| 核心分類測試 | A non-current asset (or disposal group) is classified as **held for sale** if its carrying amount will be recovered **principally through a sale transaction rather than through continuing use** | HKFRS 5 para. 6 |
| 兩大必須同時符合嘅條件 | (1) **available for immediate sale in its present condition** subject only to terms that are usual and customary for sales of such assets; AND (2) the sale must be **highly probable** | HKFRS 5 paras. 6–7 |
| "Highly probable" 定義 | **Significantly more likely than probable**; "probable" = more likely than not | HKFRS 5 App A（LP Section 12.1.1.1） |
| "Highly probable" 六項準則 | (i) appropriate level of management **committed to a plan to sell**; (ii) **active programme to locate a buyer** initiated; (iii) asset **actively marketed at a price reasonable in relation to current fair value**; (iv) sale expected to complete **within one year** from classification; (v) unlikely significant changes / withdrawal of the plan; (vi) shareholder approval (if required) likely to be obtained | HKFRS 5 para. 8 |
| 超過一年唔使即刻除名 | Extension beyond one year does **not** preclude continued HFS classification if the delay is caused by events/circumstances **beyond the entity's control** and there is sufficient evidence of continued commitment | HKFRS 5 para. 9 |
| 分類日期 | Classify as HFS on the date the criteria are first met（例：Board 批准並啟動賣盤程序當日，並非簽約日） | HKFRS 5 para. 8（LP Illustrative Example 2） |
| To be abandoned | An asset to be **abandoned** is **NOT** classified as held for sale（carrying amount recovered through continuing use）；但若 disposal group 被 abandoned 且符合 discontinued operation 定義，於 **the date it ceases to be used** 列作 discontinued operation | HKFRS 5 para. 13 |
| Held for distribution to owners | 處理方法 essentially the same as HFS；計量用 **fair value less costs to distribute** | HKFRS 5（LP Section 12.1.1.2；詳見 M11 Ch15） |

#### B. Measurement 計量（initial + subsequent）

| 考點 | 規則 | 出處 |
|---|---|---|
| 基本計量 | Measure at the **lower of carrying amount and fair value less costs to sell (FVLCS)** | HKFRS 5 para. 15 |
| Fair value 定義 | The price that would be received to sell an asset or paid to transfer a liability in an orderly transaction between market participants at the measurement date | HKFRS 5 App A（引述 HKFRS 13） |
| Costs to sell 定義 | **Incremental costs directly attributable to the disposal**, excluding finance costs and income tax expense（例：due diligence costs、commissions） | HKFRS 5 App A |
| 停止折舊 | **No depreciation / amortisation** while classified as HFS（或屬於 HFS disposal group）；但 disposal group 負債嘅 interest and other expenses **繼續**確認 | HKFRS 5 para. 25 |
| Measurement scope 豁免（**唔**受 HKFRS 5 計量規定管） | (1) financial assets within HKFRS 9（carried at FV through P&L）; (2) **deferred tax assets**（HKAS 12 — fair value 難以確定）; (3) investment property under **fair value model** of HKAS 40；另外 assets arising from insurance contracts（HKFRS 17）亦被排除 | HKFRS 5 para. 5 |
| Disposal group 三步法 | **Step 1:** 先用各自準則 remeasure 唔屬 HKFRS 5 計量範圍嘅資產（如 HKAS 40 investment property 先重估至 FV）；**Step 2:** 加返入 disposal group 其他 HKFRS 5 範圍內資產嘅 carrying amount；**Step 3:** 比較 disposal group 總 CA vs FVLCS，CA > FVLCS → 確認 impairment loss | HKFRS 5 paras. 18–19（LP Section 12.2.2 三步法） |
| Impairment 分配次序 | 先全數撇銷 disposal group 內 **goodwill**；再按 **pro rata** 分配予其他屬 HKFRS 5 計量範圍嘅 non-current assets；**cash / trade receivables / FV-model investment property 一律唔分**（與 HKAS 36 一致） | HKFRS 5（allocation consistent with HKAS 36，LP Section 12.2.2） |
| Reversal（回升上限） | Subsequent increase in FVLCS → recognise a gain, **capped at the cumulative impairment loss** previously recognised（under HKFRS 5 or previously HKAS 36）；**goodwill 永不 reversal**（HKAS 36）；每項資產嘅 reversal 不得超過該資產累計 impairment | HKFRS 5 paras. 21–22 |

**Key journal entries（Dr/Cr 必須平衡）**

例：Machine CA HK$1,000,000；分類為 HFS 時 FVLCS = HK$850,000（FV 900,000 − selling costs 50,000）。

```
(1) 初步分類為 held for sale（重列）
Dr  Non-current asset held for sale      1,000,000
    Cr  Property, plant and equipment                1,000,000

(2) 撇減至 FVLCS（HK$150,000 impairment）
Dr  Impairment loss (profit or loss)       150,000
    Cr  Non-current asset held for sale                150,000
    （之後停止折舊 —— 再無 depreciation journal）

(3) 後續 FVLCS 回升至 HK$920,000（reversal 上限 = 累計 impairment 150,000；實際升 70,000）
Dr  Non-current asset held for sale         70,000
    Cr  Gain on reversal of impairment (P&L)            70,000

(4) 最終以 HK$930,000 售出（出售時 CA = 920,000）
Dr  Cash                                   930,000
    Cr  Non-current asset held for sale                920,000
    Cr  Gain on disposal (profit or loss)               10,000
```

#### C. Disclosure / Presentation 披露及列報

| 考點 | 規則 | 出處 |
|---|---|---|
| SFP 單獨列示 | HFS 資產（及 disposal group 資產）與其他資產**分開**列示；disposal group 負債與其他負債**分開**列示；**assets and liabilities shall NOT be offset**（唔可以 net off） | HKFRS 5 para. 38 |
| 比較期間 | 初步分類為 HFS 時，**唔准** reclassify / re-present prior-period comparatives（無追溯重列） | HKFRS 5 para. 40 |
| OCI 累計項目 | 與 HFS 資產有關、曾於 OCI 確認嘅累計 income/expense（如 HKAS 16 revaluation surplus）須單獨列示 | HKFRS 5 para. 38 |
| Discontinued operations 於 P&L | 單一金額（single amount）＝ post-tax profit/loss of discontinued operations ＋ post-tax gain/loss on measurement to FVLCS or disposal；與 continuing operations **分開列示** | HKFRS 5 paras. 30, 33(a)(i)–(ii) |
| 分析披露 | Para. 33(a) 金額須分析為 revenue、expenses、pre-tax profit/loss、FVLCS/disposal gain or loss、及各自 income tax（P&L 或 notes） | HKFRS 5 para. 33(b) |
| 現金流披露 | Net cash flows attributable to **operating / investing / financing** activities of discontinued operations | HKFRS 5 para. 33(c) |
| 母公司擁有人應佔 | Income from continuing operations and from discontinued operations attributable to **owners of the parent** | HKFRS 5 para. 33(d) |
| 唔屬 discontinued operation 嘅 HFS 撇減 | Gain/loss on remeasurement 計入 **profit or loss from continuing operations**（唔好放入 discontinued operations） | HKFRS 5 para. 37 |
| 額外 notes 披露（分類/出售當期） | (1) description of the asset (or disposal group); (2) facts and circumstances of the sale, expected manner and timing; (3) impairment loss on write-down to FVLCS or gain on subsequent increase | HKFRS 5（LP Section 12.4.3） |

**Discontinued operation 定義（必背）**：a **component of an entity** that has been disposed of **or is classified as held for sale**, AND: (a) represents a **separate major line of business or geographical area of operations**; (b) is part of a **single co-ordinated plan** to dispose of such a line/area; or (c) is a **subsidiary acquired exclusively with a view to resale**（HKFRS 5 para. 32）。Component = operations and cash flows clearly distinguishable；held for use 期間須曾為 CGU 或 group of CGUs（HKFRS 5 para. 31）。**注意**：未出售都可以是 discontinued operation —— classified as held for sale 已足夠（HKFRS 5 para. 32；LP 明確指出 "discontinuing" 先啱但都叫 discontinued）。

### 易混淆概念對比

**Table 1：Held for Sale vs Held for Distribution to Owners vs To Be Abandoned**

| | Held for Sale | Held for Distribution to Owners | To Be Abandoned |
|---|---|---|---|
| Carrying amount 收回方式 | Through a sale transaction | Through distribution to owners | Through continuing use（用到完/關閉唔賣） |
| HFS classification? | Yes | 會計處理 essentially the same as HFS | **No — never classified as HFS** |
| 計量 | Lower of CA and FVLCS | FVLCS 對應版：**fair value less costs to distribute** | 繼續按原準則（如 HKAS 16）折舊計量 |
| 折舊 | Cease upon classification | Cease | **Continue depreciating**（一直用到 economic life 尾） |
| Discontinued operation 可能性 | 符合 para. 32 即可 | 符合即可 | 只可以喺 **ceases to be used 當日**先至列作 discontinued operation |

點樣分辨：關鍵問「部資產嘅 carrying amount 點收回？」—— 賣 → HFS；送畀股東 → held for distribution；丟/閂 → abandoned，**永遠唔入 HFS**。考試伏位：見到 "close down / abandon / use until end of life" 就**唔好**分類 HFS，但如果係成個 disposal group 關閉，記住 abandoned group 都可能要喺停用日做 discontinued operation 披露（HKFRS 5 para. 13）。

**Table 2：HKFRS 5 Measurement Scope — 適用 vs 豁免資產**

| 屬於 HKFRS 5 計量範圍（用 lower of CA & FVLCS） | **唔**屬於（先用自己嘅準則 remeasure） |
|---|---|
| Property, plant and equipment（HKAS 16 cost model） | Financial assets within HKFRS 9（cash、trade receivables、FVTPL investments） |
| Intangible assets（HKAS 38，包括 goodwill 分配減值） | Deferred tax assets（HKAS 12） |
| Land、buildings、machinery、motor vehicles | Investment property under **HKAS 40 fair value model** |
| | Assets arising from insurance contracts（HKFRS 17） |

點樣分辨：口訣「**金融、稅、投資物業、保險**」四大豁免。考試伏位：做 disposal group 減值題時，豁免資產**第一步先按自己準則 remeasure**（例：HKAS 40 investment property 先撇至 FV），然後先至比較成個 group 嘅 CA vs FVLCS；而 impairment 分配時 **cash 同 receivables 永遠唔使分**——呢個係 panelist 年年話弱嘅位（HKFRS 5 measurement 連續三年被點名）。

## Phase 2 閃卡

### Card 1
**Front:** Under HKFRS 5, what are the two conditions that must BOTH be met for a non-current asset to be classified as held for sale?

**Back:**
- Available for immediate sale in its present condition, subject only to usual and customary terms (HKFRS 5 para. 7)
- The sale must be highly probable (HKFRS 5 para. 8)
- Overarching test: carrying amount recovered principally through sale, not continuing use (para. 6)

💬 白話解釋：兩個條件缺一不可——「而家即刻賣得」加「好大機會賣成」。淨係「probable」（過半機會）都未得，要 "highly probable"（significantly more likely than probable）。

### Card 2
**Front:** List the six HKFRS 5 criteria for a sale to be considered "highly probable".

**Back:**
- Appropriate level of management committed to a plan to sell
- Active programme to locate a buyer initiated
- Actively marketed at a price reasonable relative to current fair value
- Sale expected to complete within one year of classification
- Unlikely the plan will be significantly changed or withdrawn
- Shareholder approval (if required) likely to be obtained
- (HKFRS 5 para. 8)

💬 白話解釋：記憶口訣「Management 有心、搵客程序已啟動、開價貼市、一年內搞掂、計劃唔會縮沙、股東會過關」。考試鍾意抽一兩項問你仲未符合 highly probable。

### Card 3
**Front:** Can a non-current asset that management intends to ABANDON be classified as held for sale? Explain.

**Back:**
- No — never classified as HFS, because the carrying amount is recovered through continuing use (HKFRS 5 para. 13)
- Includes assets used to the end of their economic life and assets closed rather than sold
- BUT: an abandoned disposal group meeting the definition is presented as a discontinued operation from the date it ceases to be used

💬 白話解釋：「唔賣就唔係 HFS」係鐵律。但留意個伏位：abandon 成個業務組合，停用當日一樣可能要當 discontinued operation 披露，兩件事唔好撈亂。

### Card 4
**Front:** State the measurement rule for non-current assets (or disposal groups) classified as held for sale, and the depreciation treatment.

**Back:**
- Measure at the **lower of carrying amount and fair value less costs to sell** (HKFRS 5 para. 15)
- **Cease depreciation / amortisation** from the date of HFS classification (para. 25)
- Interest and other expenses on liabilities of a HFS disposal group continue to be recognised

💬 白話解釋：由分類嗰刻起個資產「凍結」——唔再折舊，因為你唔係再用佢，係等緊賣佢。考試伏位：好多人忘記停折舊，繼續計全年 depreciation，即刻錯。

### Card 5
**Front:** Which assets are EXCLUDED from the measurement requirements of HKFRS 5 (HKFRS 5 para. 5)?

**Back:**
- Financial assets within the scope of HKFRS 9 (e.g. carried at FV through P&L)
- Deferred tax assets (HKAS 12)
- Non-current assets under the fair value model of HKAS 40 Investment Property
- (Also assets arising from insurance contracts — HKFRS 17)
- Note: classification & presentation rules still apply; only the measurement rules are excluded

💬 白話解釋：口訣「金融、稅、投資物業、保險」。呢啲資產本身已經按 fair value 或專屬準則計量，再用 lower-of 測試會衝突，所以 HKFRS 5 放手。

### Card 6
**Front:** Describe the THREE steps to determine the impairment loss of a disposal group held for sale, and the allocation order of any write-down.

**Back:**
- Step 1: Remeasure disposal-group assets outside HKFRS 5's measurement scope under their own standards
- Step 2: Add remeasured amounts to carrying amounts of in-scope assets
- Step 3: Compare total CA vs FVLCS of the group; CA > FVLCS → impairment loss
- Allocation: first to **goodwill**, then **pro rata** to other in-scope non-current assets (consistent with HKAS 36)
- Cash and trade receivables are never allocated any write-down

💬 白話解釋：口訣「先執豁免貨、再埋單比較、goodwill 先孭鑊」。Pilot paper 出過 3 分題考呢個 allocation，cash/receivables 唔郁係最常見得分/失分位。

### Card 7
**Front:** What is the ceiling on recognising a gain when the FVLCS of a held-for-sale asset subsequently increases?

**Back:**
- Gain recognised only up to the **cumulative impairment loss** previously recognised (under HKFRS 5 or previously under HKAS 36) (HKFRS 5 paras. 21–22)
- Treated as a **reversal** of impairment
- **No reversal ever allocated to goodwill** (HKAS 36)
- Per-asset cap: reversal on each asset cannot exceed that asset's own cumulative impairment

💬 白話解釋：「撇咗幾多，最多賺返幾多」。Goodwill 一撇永撇，永不回頭 —— 同 HKAS 36 impairment reversal 個 cap 概念一脈相承。

### Card 8
**Front:** Define a "discontinued operation" under HKFRS 5 and state how its results are presented.

**Back:**
- A component of an entity (CGU or group of CGUs; operations & cash flows clearly distinguishable) disposed of **or** classified as held for sale (para. 32)
- AND: separate major line of business / geographical area; part of a single co-ordinated disposal plan; or a subsidiary acquired exclusively with a view to resale
- Presentation: single amount in SPLOCI = post-tax profit/loss + post-tax measurement/disposal gain/loss, separate from continuing operations (paras. 30, 33(a))
- Non-qualifying HFS remeasurement gains/losses stay in continuing operations (para. 37)

💬 白話解釋：「未賣得都可以係 discontinued」係最易錯位——classified as HFS 已經合格。但唔係個個 HFS 都係 discontinued：細微資產（如一層寫字樓）唔代表 major line of business，就留返喺 continuing operations。

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| Disposal group | 一籃子一單過賣嘅資產（連埋直接相關負債） | A disposal group is a group of assets to be disposed of together as a group in a single transaction, including directly associated liabilities. |
| Highly probable | 「非常有可能」，比 probable 再高一级 | A sale is highly probable when it is significantly more likely than probable, which itself means more likely than not. |
| Fair value less costs to sell (FVLCS) | 公平價值減賣嘢成本，計量下限比較嘅一邊 | The machine is measured at the lower of its carrying amount and fair value less costs to sell. |
| Costs to sell | 直接因出售而多咗嘅增量成本（唔包 finance costs 同稅） | Broker commissions and legal fees are costs to sell, whereas finance costs are excluded. |
| Component of an entity | 營運同現金流可以清清楚楚同其他業務分開嘅部分 | The retail division is a component of the entity because its operations and cash flows are clearly distinguishable. |
| Discontinued operation | 已出售或已分類 HFS 嘅主要業務線/地區 | The disposal of the entire European division is presented as a discontinued operation. |
| Cash-generating unit (CGU) | 最細嗰組自己產生獨立現金流嘅資產 | While held for use, a component of an entity will have been a cash-generating unit or a group of cash-generating units. |
| Reversal of impairment loss | 減值回升，但最多賺返之前撇過嘅數 | The gain on the increase in FVLCS is capped at the cumulative impairment loss previously recognised on that asset. |
