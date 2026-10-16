# M8 Chapter 6: Auditing IT Systems — Phase 1 速查表 + Phase 2 閃卡

## Phase 1 速查表

### Learning Objectives
- Explain how the complexities of computerised systems (including IT security risks) affect the audit of financial statements (HKSA 315 (Revised 2019), para. 25).
- Distinguish between general IT controls and application controls (input, processing, output, master file controls) and evaluate their impact on evidence accumulation.
- Distinguish manual controls from automated controls and explain when the auditor may audit only manual controls to assess control risk.
- Illustrate computer-assisted auditing techniques (CAATs): the test data approach, audit software and parallel simulation.
- Describe the auditor's concerns when processing is outsourced to a service bureau (Type 1 / Type 2 reports) and the auditor's role in cybersecurity.

---

### 必背考點

#### A. Procedures（審計程序）

**1. Understanding the IT system — HKSA 315 (Revised 2019), para. 25**
- The auditor MUST obtain an understanding of the entity's **information system and communication** relevant to the preparation of the financial statements, through **risk assessment procedures**:
  - How transactions are **initiated, recorded, processed, corrected, incorporated into the general ledger and reported** in the financial statements;
  - The **accounting records, specific accounts and supporting records** relating to information flows;
  - The **financial reporting process** used to prepare the FS (including disclosures);
  - The entity's **resources, including the IT environment**;
  - How the entity **communicates** significant financial reporting matters (within the entity; management ↔ TCWG; external parties);
  - **Evaluate** whether the information system and communication appropriately support preparation of the FS per the applicable financial reporting framework.

**2. Risk assessment procedures over general controls（防止未授權改動系統）**
LP Apply & Analyse 3 示範程序：
- **Observe** the client's procedures to confirm adequate **segregation of duties**;
- **Review the log of amendments** for evidence changes were made by an appropriate individual;
- Attempt to **log in using credentials of a non-finance staff member** (system should reject access);
- Check **anti-virus systems** are in place and up to date;
- **Review the backup policy** for the accounting system;
- **Inspect logs** of access into the accounting system.

**3. Procedures over backup and recovery（business continuity）**
- Inquire of management / TCWG and **inspect backup procedures** — key check: backups taken **off-site**;
- Inspect **disaster recovery procedures**;
- Inspect **insurance contracts** and **maintenance agreements**;
- Inspect **equipment protection** against hazards (fire, flood).

**4. Testing manual controls**
- Manual controls = operated by employees (e.g. approvals, reconciliations, follow-up of reconciling items, manual data entry controls such as pre-numbering source documents).
- Manual controls are **inherently riskier** than automated controls (human error / override) → auditor selects a **sample of transactions** to confirm the control operated as expected; inconsistent operation → **deviation/exception**.
- Auditor may choose to **audit only manual controls** to assess **control risk** where appropriate (HKSA 315 (Revised 2019), Appendix 5, para. 1 acknowledges the mix of manual and automated elements varies with the entity's use of IT).

#### B. Evidence（審計證據 — CAATs）

**1. CAATs 總論**
- CAATs use computers to perform audit procedures but **do NOT change the overall scope or objective of the audit**.
- Two common types: **audit software** and **test data**.
- Uses: tests of details on transactions/balances; analytical review (e.g. gross profit margins vs prior year); designing sample sizes & sampling; reperforming calculations; **tests of controls** over general and application controls.
- **Advantages:** time efficiency; test **larger sample sizes**; trace key controls/processes otherwise impossible manually; **cost-effective long-term** (if client doesn't change IT system).
- **Disadvantages:** initial setup cost & staff training time; possible **incompatibility** with client's system; risk of **data corruption / loss of client's live data**.

**2. Test data（測試數據）**
- Used for **tests of controls (compliance tests)**: auditor enters a sample of transactions into the client's system and **compares results with pre-determined results**.
- Examples: process a sale taking a customer **over its credit limit** → system should reject; input a **non-existent customer account number** → system should reject; enter an **inappropriately large bonus** for junior staff → payroll should flag exception; create a **dummy employee** to test mandatory fields.
- **Inherent problems (6.5.1.1):**
  - Risk of **corrupting the client's system** / difficulty removing test data → use **copy files** instead of live data (must be satisfied copy files are **genuine** and virus-free);
  - Tests the system only at a **specific point in time** — processing at other times of the period is not covered.

**3. Audit software（審計軟件）**
- Used to carry out **substantive procedures** to detect material misstatement (general or customised packages).
- Uses: analytical procedures (AR/AP days, year-on-year comparisons); **designing & extracting samples**; **reperforming calculations** (e.g. recasting inventory valuation report); checking file data (e.g. invoice prices agree to sales master file); preparing **confirmation letters**; scanning files for large/unusual items and completeness of document ranges.
- Reduces **detection risk** (gives more resources to analyse data and investigate unusual items). ⚠️ It does NOT reduce inherent risk or control risk — those are not under the auditor's control.
- Consider requesting **client permission** before extracting data; may need to reference data extraction in the **engagement letter**.

**4. Parallel simulation（平行模擬）**
- Auditor creates programmed procedures to **duplicate part of the client's IT system**; takes **live data** processed by the client's system and **reprocesses it through the auditor's version**; compares outputs.
- Advantages: facilitates substantive testing of balances; evidence on controls in application programs; tests accuracy of large volumes; focuses attention on differences.
- Disadvantage: **expensive to implement**, especially for complex calculations.

**5. PCs as an audit tool**
- Speed and accuracy; embedded checks identify inordinate transactions/balances; detect calculation errors.
- ⚠️ Using PCs **does NOT remove the need** for normal audit procedures (e.g. verifying receivables valuation, payables completeness still required).

#### C. Ethics（專業道德 — Internal Audit 角色）

- Internal audit (IA) is part of the entity's **system of internal control** and may evaluate IT controls.
- IA **CANNOT implement internal controls** — doing so creates a **self-review threat** (reviewing their own work) and destroys independence/objectivity. IA can only **recommend** improvements and test operating effectiveness of controls implemented by management.
- External auditors **may choose to rely on** IA's work (see Chapter 4 for the detailed criteria).

#### D. Report modifications（報告修改 — IT 失效嘅後果）

- **Ineffective general controls** → application controls unlikely to be effective → auditor places **little/no reliance on the IT system** → adopt a **more substantive approach** (risk of material misstatement likely high). 呢個係 extent of testing 嘅問題，**唔係自動 modify opinion**。
- **Inadequate backup / loss of accounting data** → auditor may be **unable to obtain sufficient appropriate audit evidence** → if so serious that the auditor cannot form an opinion → **disclaimer of opinion** (see Chapter 9).
- Disaster without continuity controls may threaten **going concern** → disclosure required; if FS prepared on going concern basis but basis inappropriate → **modified opinion** (see Chapter 9).
- Cybersecurity breach / unauthorised access may cause **material misstatement** and is a **fraud risk factor** — but does NOT automatically lead to a disclaimer; unmodified opinion still possible if reasonable assurance obtained.

---

### 易混淆概念對比

**Table 1: General IT Controls vs Application Controls**

| | General IT Controls | Application Controls |
|---|---|---|
| Definition | Controls over the **environment** within which the computer system is developed, maintained and operated | Controls operating **within the business application** to ensure data is processed completely, accurately, validly and timely |
| Scope | **Pervasive** — affect ALL application systems | Specific to individual transaction processing (e.g. sales, payroll, purchases) |
| Examples | Program change control; logical access controls (passwords, user ID); backup & recovery; systems development controls; IT operations controls; physical access to data centre | Batch total checks; sequence checks; arithmetic checks; range checks; existence checks; authorisation checks; exception reporting; check digit / hash total verification |
| LP reference | HKSA 315 (Revised 2019) App. 5 para. 18 (risks from IT); App. 6 para. 2 (examples: access management, change management, IT operations) | LP §6.4 (input / processing / output / master file controls) |
| 點樣分辨 | 問自己：呢個控制係咪「成個 IT 環境」都受影響？係 → general。只係針對某個 application 嘅 data input/processing/output → application | 考試伏位：考官審計順序係 **先 general 後 application** —— general controls ineffective ⇒ application controls generally ineffective ⇒ more substantive approach。Password/user ID 屬 **general (logical access)**，唔好當 application control |

**Table 2: Test Data vs Audit Software vs Parallel Simulation**

| | Test Data | Audit Software | Parallel Simulation |
|---|---|---|---|
| Purpose | **Tests of controls** (compliance tests) | **Substantive procedures** (detect material misstatement) | Both: substantive testing + evidence on application controls |
| Mechanism | Auditor **inputs fictitious transactions** into client's system; compares results with pre-determined results | Auditor's own software **interrogates client's real data files** (analyse, sample, recalculate) | Auditor **reprocesses client's live data** through auditor's replica of part of the system; compares outputs |
| Data used | Auditor-created data (valid + invalid) | Client's actual data | Client's live data, run through both systems |
| Risk reduced / key issue | Does not directly reduce detection risk; tests whether controls operate | Reduces **detection risk** (larger coverage, faster analysis) | Expensive to implement; best for complex calculations |
| 點樣分辨 | 口訣：**Test data 測 control，audit software 做 substantive**。見到「input dummy/fictitious data to see if system rejects」= test data；見到「extract / recalculate / scan client's file」= audit software；見到「reprocess live data through auditor's version & compare」= parallel simulation | 考試伏位：(1) audit software reduces **detection risk only**，唔可以話佢 reduce inherent/control risk；(2) test data 兩大 inherent problems = corrupt client data + point-in-time only；(3) CAATs **唔會改變 audit scope/objective** |

---

## Phase 2 閃卡

### Card 1
**Front:** According to HKSA 315 (Revised 2019) para. 25, what must the auditor understand about the entity's information system relevant to financial reporting?

**Back:**
- How transactions are initiated, recorded, processed, corrected, incorporated into the general ledger and reported in the FS
- The accounting records, specific accounts and supporting records
- The financial reporting process (including disclosures)
- The entity's resources, including the IT environment
- How significant matters are communicated (within entity; management ↔ TCWG; external parties)
- Evaluate whether the system supports FS preparation per the applicable framework

💬 白話解釋：呢段係 risk assessment 嘅基本功——核數師要由「交易點樣入系統、點樣流到落 FS」成條鏈都要明白，仲要評估個系統撐唔撐到份報表。考試常見伏位係以為淨係要識 IT，其實連 communication 同 evaluation 都係 para. 25 要求。

### Card 2
**Front:** Define "general IT controls" and give FOUR examples.

**Back:**
- Definition: controls over the **environment** within which the computer system is developed, maintained and operated, and within which application controls operate
- Examples: program change control; logical access controls (user ID/password); backup and recovery; systems development controls; IT operations controls; data and program security
- They have a **pervasive effect** on all application systems

💬 白話解釋：General controls 係「大環境」嘅控制，唔係針對個別交易。記住審計次序：general controls 差 → application controls 都靠唔住 → 唯有做多啲 substantive procedures。

### Card 3
**Front:** What are the FOUR categories of application controls, and what is each designed to ensure?

**Back:**
- **Input controls** — data input is accurate (e.g. check digit verification, hash totals, input verification by second person)
- **Processing controls** — data is processed correctly and files updated timely (e.g. re-entry verification of rejected data, parallel run of new system)
- **Output controls** — output is correct and distributed only to authorised individuals (e.g. batch control totals, exception report review)
- **Controls over master file information** — standing data protected from unauthorised changes (passwords, logs of amendments, segregation of duties)

💬 白話解釋：跟住數據流向記：Input → Processing → Output，外加 master file（standing data 如薪金率、客戶 credit limit）。Master file 俾人亂改 = 長期性錯誤，係 auditor 嘅 major concern。

### Card 4
**Front:** Distinguish between manual controls and automated controls. Which is inherently riskier and why?

**Back:**
- **Automated control**: built into the IT system (e.g. system rejects customer over credit limit)
- **Manual control**: operated by an employee (e.g. sales director overrides a system rejection; approvals; reconciliations)
- Manual controls are **inherently riskier** — susceptible to human error, erroneous or fraudulent operation, and override
- HKSA 315 (Revised 2019) App. 5 para. 2: automated controls may be more reliable because they cannot be as easily bypassed, ignored or overridden, and are less prone to simple errors; more effective for high-volume recurring transactions

💬 白話解釋：記住「人會攰、會呃、會撳錯掣；機器唔會」——但機器可以俾人 override，所以兩者都要 test。Manual control 要靠 sample testing 去 confirm 有持續運作。

### Card 5
**Front:** What is the "test data" approach, and what are its TWO inherent problems?

**Back:**
- Test data: auditor enters a sample of transactions (valid and invalid) into the client's IT system and compares the results with **pre-determined results** — a **test of control**
- Example: input a sale taking a customer over its credit limit → system should reject
- Inherent problems:
  1. Risk of **corrupting the client's system / live data** → use copy files (verified genuine and virus-free)
  2. Tests the system only at a **specific point in time** — other periods not covered

💬 白話解釋：Test data = 擺啲假交易落客個系統度，睇佢擋唔擋到。兩個弱點：污糟咗人哋啲 live data 點算（所以用 copy files）；同埋你只係測嗰一刻，唔代表成年都 work。

### Card 6
**Front:** List FIVE procedures an auditor can perform using audit software, and state which component of audit risk it reduces.

**Back:**
- Analytical procedures (e.g. AR/AP days, current vs prior year comparisons)
- Designing and extracting **samples** for substantive testing
- **Reperforming calculations** (e.g. recasting the inventory valuation report)
- Checking data accuracy (e.g. invoice prices agree to sales master file)
- Preparing **confirmation letters**; scanning files for gaps in document sequences and large/unusual items
- Reduces **detection risk** only — inherent risk and control risk are not within the auditor's control

💬 白話解釋：Audit software 係幫你「查數」——搵 sample、重計、做 ratio。考試經典伏位：佢 reduce detection risk，**唔係** inherent/control risk（RoMM = IR × CR，呢啲係 client 嘅嘢，auditor 控制唔到）。

### Card 7
**Front:** What are a Type 1 report and a Type 2 report in the context of a service bureau (third-party computer processing company)?

**Back:**
- **Type 1 report**: focuses on the **description and design** of controls at the third party
- **Type 2 report**: also covers the **operating effectiveness** of those controls
- Obtained with the client's permission; auditor may also discuss controls directly with the third party (backups, access rights, cybersecurity, standing data changes)

💬 白話解釋：口訣「**Type 1 = 設計，Type 2 = 設計 + 運作成效**」。Client 外咗包 IT 俾人，auditor 唔可以求其信——要攞 service auditor report 或者直接同 third party 傾。

### Card 8
**Front:** Explain the audit consequences if a client has inadequate backup and recovery procedures and accounting data is irrecoverably lost.

**Back:**
- Auditor may be **unable to obtain sufficient appropriate audit evidence** over areas of the FS
- If so serious that an opinion cannot be formed → **disclaimer of opinion**
- Lack of continuity controls after a disaster may also threaten **going concern** → disclosure; if going concern basis inappropriate but used → **modified opinion**
- Risk assessment must reflect inadequate backup → more substantive approach likely

💬 白話解釋：數據冇咗 = 冇證據 = 出唔到意見 → disclaimer。呢個係 evidence insufficiency 嘅極端例子。但記住：backup 不足本身唔會即刻觸發 disclaimer，要睇實際係咪失去咗證據。

---

## 本章急救詞彙

| EN Term | 繁中白話 | English Model Sentence |
|---|---|---|
| General IT controls | 籠統嘅 IT 環境控制，影響晒所有應用系統 | "General IT controls include program change control, logical access controls, and backup and recovery controls." |
| Application controls | 針對個別應用系統嘅輸入/處理/輸出控制 | "Batch total checks are application controls that ensure supplier invoices are input completely and accurately." |
| Logical access control | 用 user ID + password 限制邊個可以入邊個範圍 | "A logical access control requires user identification, checks authenticity, and restricts access to authorised areas only." |
| CAATs (computer-assisted auditing techniques) | 用電腦幫手做審計程序嘅技術 | "CAATs do not change the overall scope or objective of the audit." |
| Test data | 擺假數落客個系統，測 control 擋唔擋到 | "The auditor used test data to confirm that the system rejects sales orders exceeding a customer's credit limit." |
| Audit software | 用核數師自己嘅軟件查客戶真數據 | "Audit software was used to reperform the inventory valuation and extract a sample of trade receivables." |
| Parallel simulation | 用核數師版本嘅系統 reprocess 客戶 live data 再對 output | "Parallel simulation involves reprocessing the client's live data through the auditor's own program and comparing the outputs." |
| Service bureau | 第三方電腦處理公司（外判 IT） | "Where a service bureau processes the client's data, the auditor may request a Type 2 report on the operating effectiveness of controls." |
