# M8 Chapter 6: Auditing IT Systems — Phase 3 Answers

### Q1 — Answer: B
**Model Answer (EN):** This is **audit software used to perform a substantive procedure**. The auditor is interrogating the client's **actual, complete data file** (all 48,000 real invoices) using the firm's own software to **reperform a calculation** — one of the listed uses of audit software (reperforming calculations such as recasting reports; ensuring information in files is correct). Its purpose is to **detect material misstatement** in the invoiced amounts, not to test whether a control operates. Because the entire population is tested, detection risk is reduced.

**解題思路（繁中）:**
- 關鍵字眼：「extract the client's **complete sales invoice file**」+「**recalculate**」→ 用緊客戶真實數據做 re-performance = audit software 做 substantive procedure。
- **A (test data)** 錯：test data 係擺「假交易」落個系統測 control 有冇運作（test of controls），呢度冇輸入任何 auditor-created data，而係查真數。
- **C (parallel simulation)** 錯：parallel simulation 係核數師建立自己版本嘅系統去 **reprocess 客戶 live data 再比較兩個系統嘅 output**；呢度只係重計 discount，冇複製成個處理程序。
- **D** 錯在「risk assessment procedure」：audit software 重計全個 population 係 substantive procedure（detect material misstatement），唔係用嚟 identify/assess risks。
- 考試伏位：CAATs 大分類 = **test data（tests of controls）vs audit software（substantive procedures）**，呢個係 panelist 點名嘅 MCQ 弱項（Jun 2025: key features of different CAATs）。

**Rule Check:** LP §6.5.2 Audit Software (uses: reperform calculations; substantive procedures; reduces detection risk); §6.5.1 Test Data (tests of control); §6.5.3 Parallel Simulation.

**Common Trap（繁中）:** 見到「用電腦做」就亂揀 CAAT 名。記住口訣：**test data 測 control（放假數）；audit software 做 substantive（查真數）**。

---

### Q2 — Answer: C
**Model Answer (EN):** C is a **range check** — an application control ensuring that data input stays within a reasonable range (here, overtime hours). Application controls operate **within the business application** to ensure data is processed completely, accurately, validly and in a timely manner. Options A, B and D are all **general IT controls**: A is program change control (change management process), B is backup and recovery, and D is physical access control — they concern the overall IT environment in which applications operate.

**解題思路（繁中）:**
- 分辨口訣：「呢個控制係咪只針對某個 application 嘅 data 輸入/處理/輸出？」C 係 payroll 系統入面嘅 **range check**（LP §6.4 明列 application controls 例子之一）→ application control。
- **A** = program change control（HKSA 315 (Revised 2019) App. 6 para. 2(b) change management process）→ general。
- **B** = backup and recovery（App. 6 para. 2(c) IT operations；LP §6.3.3）→ general。
- **D** = physical access to data centre（App. 6 para. 2(a) physical access；LP 明言 physical access may be used to override other controls）→ general。
- 考試伏位：Pilot paper Q2a/2b 同 Q37 都考 general vs application 分類 —— 見到 **backup / program change / physical access / network security** 呢啲「環境級」字眼就係 general controls。

**Rule Check:** HKSA 315 (Revised 2019), Appendix 6, para. 2 (examples of general IT controls); LP §6.4 (application controls: range checks, batch totals, sequence checks etc.).

**Common Trap（繁中）:** 以為「電腦自動做嘅」就係 application control。其實 automated ≠ application：logical access（password）係 automated 但屬 **general** control；而 application controls 亦可以係 manual（例如人手 batch total check）。

---

### Q3 — Answer: B
**Model Answer (EN):** If general controls are ineffective, it is unlikely that application controls will be effective, because general controls have a **pervasive effect** on all application systems. The auditor will therefore place **little (if any) reliance on the IT system** and carry out a **more substantive approach** to auditing the financial statements, since the risk of material misstatement is likely to be high. A disclaimer of opinion is **not** automatic — it would only arise if the auditor were unable to obtain sufficient appropriate audit evidence. Internal audit cannot implement controls (self-review threat).

**解題思路（繁中）:**
- 呢條考 LP Key Learning Point：**general controls ineffective ⇒ application controls generally ineffective ⇒ little/no reliance ⇒ more substantive approach**。B 完全跟返呢個邏輯鏈。
- **A** 錯：application controls「睇落設計得好」都冇用，因為佢哋喺一個失效嘅 IT 環境底下運作，auditor 唔可以靠佢哋嚟減 substantive testing。
- **C** 錯：disclaimer 係「攞唔到 sufficient appropriate evidence 兼且影響 pervasive」先出；general controls 差只係推高 RMM，仲可以靠 substantive procedures 補救 —— **唔係自動 disclaimer**。
- **D** 錯：internal audit **唔可以 implement** internal controls（self-review threat，會變成 review 自己嘅嘢），佢哋只可以 recommend。
- 考試伏位：呢題同時踩兩個 panelist 弱項 —— control risk 同 substantive procedures 嘅關係（Jun 2023 Q1(e)），同 internal audit 嘅 self-review threat。

**Rule Check:** LP §6.3 Key Learning Point (ineffective general controls → little reliance → more substantive approach); HKSA 315 (Revised 2019), Appendix 5, para. 18 (risks arising from use of IT); LP §6.1.2 (IA self-review threat).

**Common Trap（繁中）:** 揀 C —— 以為 control 壞咗就一定要 modify opinion。記住：**control weakness 影響 audit approach（做幾多 substantive work），唔直接等於 opinion modification**。Opinion 層面要睇最終攞唔攞到證據。

---

### Q4 — Answer: B
**Model Answer (EN):** A **Type 2 report** covers both the **description and design** of controls at the third party **and the operating effectiveness** of those controls. A Type 1 report focuses only on the description and design of controls, so it would not provide evidence that the payroll controls operated effectively throughout the year. Options C and D are not service-auditor reports: an engagement letter references may be needed for the auditor's own data extraction, and a management representation letter does not provide independent evidence over the service bureau's controls.

**解題思路（繁中）:**
- 口訣：**Type 1 = 設計（design）；Type 2 = 設計 + 運作成效（operating effectiveness）**。題目要求「not only designed but also operated effectively」→ Type 2。
- **A** 錯：Type 1 只講 design，答唔到「成年有冇真係運作」。
- **C** 錯：engagement letter 加 data extraction 條款係 auditor 自己用 audit software 抽客戶數據嘅安排，同 service bureau report 無關。
- **D** 錯：management representation letter 唔係獨立證據，而且 LP 冇提及向 third party 攞 representation letter 嚟評估其 controls；正確做法係攞 Type 1/Type 2 report 或（經 client 同意）直接同 third party 討論。
- 考試伏位：「Type 1 vs Type 2」係 LP Knowledge Check 都有嘅經典位，見到 **operating effectiveness** 呢兩個字就揀 Type 2。

**Rule Check:** LP §6.7 (Type 1 report: description and design of controls; Type 2 report: also covers operating effectiveness; auditor may discuss controls with the third party with client's permission).

**Common Trap（繁中）:** 倒轉咗兩個 report —— 記住數字越大、涵蓋越多：Type 2 包含 Type 1 嘅內容再加 operating effectiveness。

---

### Q5 — Answer: 見 Model Answer
**Model Answer (EN):**

(a) Disadvantages of CAATs (any two):
- High **initial setup costs** and time spent in the first year of use.
- Audit staff require **training** in the use of CAATs (adding to initial costs).
- The auditor's software **may not be compatible** with the client's IT system.
- Risk of **data corruption or loss of the client's live data** (strong controls needed to prevent this).
- Cost-effectiveness depends on the client **not changing its IT system**.

(b) Inherent problems with test data (any two):
- Risk that the **client's system/live data is corrupted** or that test data **cannot easily be removed** — mitigated by using **copy files** (which must be genuine and virus-free).
- Test data only tests the system at a **specific point in time**; processing errors at other times in the reporting period may not be detected.
- Clients may be **nervous/unwilling** to allow the auditor to input data into their live system.

**解題思路（繁中）:**
- (a) 同 (b) 唔好撈亂：CAATs disadvantages 係「成本、培訓、兼容性、數據損毀風險」；test data inherent problems 係「污糟 live data（用 copy files 解決）+ point-in-time 限制」。「point-in-time」係 test data **獨有**嘅弱點，唔好寫落 CAATs disadvantages 度。
- 答「do not change audit scope/objective」係 **唔啱** 嘅 —— 嗰句係 CAATs 嘅特性（中性陳述），唔係 disadvantage。
- 考試伏位：Jun 2025 panelist report 特別點名考生唔識 CAATs 嘅 key features；呢類「list TWO」題型係 Section B 最常見嘅 command word（List），每點一分，寫短 bullet 就得，唔使長篇。

**Rule Check:** LP §6.5 (CAATs advantages and disadvantages); §6.5.1.1 (Inherent Problems with Test Data: corruption of client data → copy files; point-in-time testing only).

**Common Trap（繁中）:** 兩 part 答案交叉寫（例如將「training costs」寫入 test data 嘅 inherent problems）。Test data 嘅 inherent problems 係 **技術性限制**（corruption + point-in-time），成本問題屬 CAATs 整體。
