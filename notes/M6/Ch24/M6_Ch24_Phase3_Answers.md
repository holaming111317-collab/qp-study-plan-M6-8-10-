# M6 Chapter 24: Investments in Associates — Phase 3 Answers

### Q1 — Answer: C

**Model Answer (EN):**
Statement C is correct. Although Kingfisher Limited holds less than 20% of the voting power of Tern Limited (which gives rise to a rebuttable presumption of no significant influence), its board representation and provision of essential technical information are indicators that it has the power to participate in Tern Limited's financial and operating policy decisions. The presumption is rebutted by this evidence.

**解題思路（繁中）:**
- **A 錯**：≥20% 只係 *rebuttable presumption*。被投資公司由 administrator 接管後，參與財務及營運政策決策嘅權力已轉移到 administrator 手上，presumption 被推翻 — 持股不變都可以失去 significant influence。
- **B 錯**：呢個係 **control**（HKFRS 10）嘅定義 — "direct relevant activities"。Significant influence 只係 **participate**，唔係 direct。呢個 definition swap 係經典伏位。
- **C 啱**：<20%  presume 冇 significant influence，但 board representation + provision of essential technical information 係 HKAS 28.6 明列嘅 indicators，足以推翻 presumption。
- **D 錯**：30% 持股 + 可任命 8 席中 6 席董事 = 有能力**主導**財務及營運政策，即係 control，Plover 係 subsidiary 唔係 associate。

**Rule Check:** HKAS 28.3 (definition of significant influence); HKAS 28.5 (rebuttable presumptions); HKAS 28.6 (indicators of significant influence)

**Common Trap（繁中）:** 見到 ">20%" 就即刻答「一定係 associate」— 考官最鍾意用 administrator 接管或者相反證據嚟考你 presumption 係可以推翻嘅；反向（<20% 但有實質影響力證據）一樣考。

---

### Q2 — Answer: B

**Model Answer (EN):**
Under the equity method, a dividend received from an associate is **not** recognised as dividend income. It is recognised as a reduction in the carrying amount of the investment:

| Particular | Debit (HK$) | Credit (HK$) |
|---|---|---|
| Cash | 70,000 | |
| Investment in associate | | 70,000 |

This avoids double-counting: Avocet Limited has already recognised its 35% share of Stilt Limited's profits in its profit or loss; the dividend is simply a distribution of those profits. Only Avocet Limited's **share** of the dividend (35% × HK$200,000 = HK$70,000) is relevant.

**解題思路（繁中）:**
- **A 錯**：equity method 下 associate 嘅利潤已經以 share of profit 入咗 P&L；再認 dividend income 即係雙重計算。
- **B 啱**：DR Cash / CR Investment in associate — 股息係投資賬面值嘅減少（套現已確認嘅利潤份額）。
- **C 錯**：investor 永遠只係處理**自己嗰份**（HK$70,000），唔會認成個股息總額 HK$200,000 — associate 唔係 consolidate，唔會 line-by-line 併入。
- **D 錯**：股息唔係沖減 share of profit — 咁做會令 associate 對本期 P&L 嘅貢獻被錯誤陳述。Share of profit 同 dividend 係兩條獨立嘅調整線（一個入 P&L，一個扣 investment）。

**Rule Check:** HKAS 28.10 (equity method — distributions reduce the carrying amount of the investment)

**Common Trap（繁中）:** 如果公司自己本帳已經記咗 DR Cash / CR Dividend income，consolidation worksheet 要做 pro forma 更正：**DR Dividend income / CR Investment in associate**。考官報告（Jun 2025）特別點名考生「failed to eliminate dividend income recorded by the parent」— 呢個係實戰伏位。

---

### Q3 — Answer: C

**Model Answer (EN):**

Workings:

| | HK$ |
|---|---|
| Coral Limited's reported net profit | 500,000 |
| Less: additional amortisation on fair value uplift of patent (HK$400,000 / 8 years) | (50,000) |
| Coral Limited's adjusted profit for the year | 450,000 |
| Marlin Limited's share (30% × HK$450,000) | **135,000** |

Journal entry:

| Particular | Debit (HK$) | Credit (HK$) |
|---|---|---|
| Investment in associate | 135,000 | |
| Share of associate's profit or loss | | 135,000 |

**解題思路（繁中）:**
- 重點：equity accounting 用嘅 profit **唔係** associate 自己報表嘅 profit。收購日 fair value uplift（未確認專利 HK$400,000）會產生額外攤銷，要先調整 associate 嘅 profit 先至乘以持股比例。
- **A (HK$150,000) 錯**：30% × HK$500,000 — 完全冇扣 FV uplift 攤銷，係最常见錯誤。
- **B (HK$100,000) 錯**：150,000 − 50,000 — 將**全數**攤銷喺乘以 30% **之後**先扣。正確次序係「先調整、後分成」，因為攤銷係成間公司嘅開支調整，唔係只屬於投資者嗰份。
- **C (HK$135,000) 啱**：(500,000 − 50,000) × 30%。
- **D (HK$30,000) 錯**：(500,000 − 400,000) × 30% — 將成個 FV uplift 當一次性開支扣晒，而唔係按 8 年攤銷。

**Rule Check:** HKAS 28.32 (share of profit or loss adjusted for depreciation/amortisation arising from acquisition-date fair value adjustments); HKAS 28.10 (equity method)

**Common Trap（繁中）:** 兩個次序錯誤最致命：(1) 忘記 FV uplift 攤銷；(2) 次序倒轉（先 ×% 後扣全數調整）。記住口訣：**「調整先做，分成後行」**。如果 uplift 係土地或無限期資產就唔使攤銷 — 睇清楚題目 useful life。

---

### Q4 — Answer: A

**Model Answer (EN):**
This is an **upstream** transaction (associate Puffin Limited sold to investor Gull Limited). The unrealised gain is HK$200,000 − HK$140,000 = HK$60,000, all unrealised because Gull Limited still holds the goods. Only the investor's share is eliminated: 25% × HK$60,000 = HK$15,000.

Under Approach 2 (the Learning Pack's approach — the entity recording the gain is the associate, and the entity holding the inflated asset is the investor), the pro forma journal entry is:

| Particular | Debit (HK$) | Credit (HK$) |
|---|---|---|
| Share of associate's profit or loss (25% × HK$60,000) | 15,000 | |
| Inventory | | 15,000 |

**解題思路（繁中）:**
- **A 啱**：upstream = associate 賺咗 gain、investor 揸住 inflated inventory，所以調整 **Share of associate's profit or loss**（借方，減少應佔利潤）同 **Inventory**（貸方，還原成本）。金額 = gain × 25% = HK$15,000。
- **B 錯**：消除金額係 **investor's share**（HK$15,000），唔係全數 gain HK$60,000 — 同 subsidiary 嘅 full elimination 唔同，associate 只係 eliminate to the extent of the investor's interest，其餘 75% 屬於 unrelated investors，已實現。
- **C 錯**：呢個係 **downstream**（investor 賣畀 associate）嘅 Approach 2 分錄 — DR Cost of sales / CR Investment in associate。方向調轉咗。
- **D 錯**：借貸方向完全倒轉 — 咁做會**增加**投資賬面值同應佔利潤，即係將未實現利潤當成額外收益，邏輯相反。

**Rule Check:** HKAS 28.28 (gains and losses from upstream/downstream transactions recognised only to the extent of unrelated investors' interests in the associate)

**Common Trap（繁中）:** 兩大伏位：(1) 將 subsidiary consolidation 嘅 **full elimination** 習慣搬過嚟（associate 只消除自己嗰份）；(2) upstream/downstream 方向搞亂 — 記住 upstream = associate 係賣方，所以扣 share of profit、扣 investor 手上嘅資產。如果題目話貨已經賣咗出去畀第三方，就唔使消除（已實現）。

---

### Q5 — Answer: D

**Model Answer (EN):**

Step 1 — Goodwill/(discount) on acquisition:

| | HK$ |
|---|---|
| Net fair value of Harrier Limited's identifiable net assets (3,800,000 + 200,000) | 4,000,000 |
| Kestrel Limited's share (40%) | 1,600,000 |
| Cost of investment | 2,000,000 |
| Implicit goodwill (included in carrying amount; no separate recognition, no P&L impact) | 400,000 |

Step 2 — Share of adjusted profit:

| | HK$ |
|---|---|
| Harrier Limited's reported net profit | 700,000 |
| Less: amortisation of licence fair value uplift (HK$200,000 / 5 years) | (40,000) |
| Adjusted profit | 660,000 |
| Kestrel Limited's share (40%) | 264,000 |

Step 3 — Equity accounted carrying amount at 31 December 20X4:

| | HK$ |
|---|---|
| Cost | 2,000,000 |
| Add: share of associate's net profit for the year | 264,000 |
| Less: dividends received (40% × HK$100,000) | (40,000) |
| **Carrying amount** | **2,224,000** |

**解題思路（繁中）:**
- 呢題係完整 equity method 流程： goodwill/discount 判斷 → FV uplift 攤銷調整 → 減股息。Implicit goodwill HK$400,000 只係藏在 carrying amount 度，**唔使再調整**（唔似 discount 要落 P&L）。
- **A (HK$2,240,000) 錯**：2,000,000 + (40% × 700,000) − 40,000 — 忘記扣 licence uplift 攤銷。
- **B (HK$2,264,000) 錯**：2,000,000 + 264,000 — 忘記股息要扣減 carrying amount（股息唔係 income！）。
- **C (HK$2,164,000) 錯**：扣咗**成個**股息 HK$100,000 — investor 只係收到自己 40% 嗰份（HK$40,000）。
- **D (HK$2,224,000) 啱**。

**Rule Check:** HKAS 28.10 (equity method mechanics; distributions reduce carrying amount); HKAS 28.12, 28.32 (implicit goodwill not separately recognised; FV adjustment depreciation)

**Common Trap（繁中）:** 三步缺一不可：FV 攤銷、股息扣減、用自己嗰份股息。如果 cost 低過 share of net FV（discount on acquisition），記住 discount 要**加入**收購期 share of profit，而 goodwill 就咩都唔使做。呢類 multi-step carrying amount 題係 Jun 2023 / Jun 2025 Section B 嘅必考元素，OTQ 化之後一樣要識逐步計。
