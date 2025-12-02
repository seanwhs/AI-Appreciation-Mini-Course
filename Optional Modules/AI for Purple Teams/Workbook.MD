# 🟣 **AI for Purple Teams** — **WORKBOOK**

**Goal of This Module**
Equip learners to understand how AI can elevate **collaborative defense**, **red-blue workflows**, and **continuous improvement** through faster, data-driven, and more accurate processes.

---

### **TABLE OF CONTENTS**

1. **Pre-Assessment**
2. **Section 1: Overview of AI in Purple Teaming**
3. **Section 2: AI-Enhanced Purple Team Operations**
4. **Section 3: Hands-On Exercises & Playbooks**
5. **Section 4: Ethical Considerations & Governance**
6. **Section 5: Final Assessment & Application**
7. **Templates & Cheat Sheets**

---

### 📝 **1. PRE-ASSESSMENT**

#### **1.1 Self-Assessment**

Rate your current knowledge on the following topics (1 = None, 5 = Strong):

| Skill Area                              | Rating (1–5) |
| --------------------------------------- | ------------ |
| Purple Teaming Fundamentals             |              |
| MITRE ATT&CK Framework                  |              |
| Red/Blue Team Collaboration             |              |
| Use of AI for Detection Engineering     |              |
| Correlation of Logs/Telemetry           |              |
| Scenario Planning & TTP Mapping         |              |
| Report Generation & Executive Briefings |              |

---

#### **1.2 Knowledge Check**

Circle YES or NO based on your experience:

1. Have you participated in a purple-team exercise before? (YES/NO)
2. Do you regularly collaborate with red and blue teams for detection improvement? (YES/NO)
3. Are you familiar with using MITRE ATT&CK for mapping detection gaps? (YES/NO)
4. Have you used AI tools for detecting coverage gaps or suggesting detection rules? (YES/NO)
5. Do you use AI-assisted platforms for generating reports or summaries? (YES/NO)

---

### 🧠 **2. SECTION 1 — AI IN PURPLE TEAMING: THE BIG PICTURE**

#### **2.1 AI’s Role in Purple Teaming**

### **Activity: AI’s Role in Purple Team Tasks**

Review the following purple-team tasks and decide whether they are best suited for **AI support** or **human expertise**:

| Task                                         | AI Support | Human Expertise | Why?                                                                        |
| -------------------------------------------- | ---------- | --------------- | --------------------------------------------------------------------------- |
| Test planning & scenario design              | Yes        | Yes             | AI can assist with scenario generation but humans define final tests.       |
| Correlating red actions with blue detections | Yes        | No              | AI can automate correlation but humans must validate and interpret results. |
| Detection engineering & tuning               | Yes        | Yes             | AI can suggest rule drafts, but humans perform final validation and tuning. |
| Post-test analysis & report generation       | Yes        | Yes             | AI generates drafts, but humans validate findings.                          |

---

#### **2.2 Purple Teaming Workflow with AI**

**AI enhances these key areas of purple-team operations:**

* **Scenario Design & Test Planning**: AI helps generate test cases based on real-world threats.
* **Detection Validation**: AI correlates red and blue actions to validate detection performance.
* **Gap Analysis**: AI identifies missing detection coverage, guiding improvements.
* **Collaboration**: AI provides insights and templates that enhance communication between red and blue teams.

---

#### **2.3 Key Tools and Platforms for AI-Driven Purple Teaming**

Here are some tools that support AI-driven purple teaming:

| Tool/Platform     | Functionality                              | AI Capabilities                                     |
| ----------------- | ------------------------------------------ | --------------------------------------------------- |
| **MITRE Caldera** | Adversary emulation & attack path modeling | AI-driven scenario creation, attack path suggestion |
| **PlexTrac**      | Red/blue team collaboration & reporting    | Automated TTP mapping and detection validation      |
| **Elastic AI**    | Detection and telemetry analysis           | Automated log correlation, detection gaps analysis  |
| **Splunk AI**     | SIEM & detection rule creation             | AI-based detection rule drafting and analysis       |

---

### 🔧 **3. SECTION 2 — AI-ENHANCED PURPLE TEAM OPERATIONS**

---

#### **3.1 Test Planning & Scenario Design**

### **AI-Assisted Test Design Exercise**

Given a new red-team engagement scenario, use AI tools to:

1. **Generate Threat Scenarios**: Based on threat intelligence, use AI to create realistic attack paths aligned with MITRE ATT&CK.
2. **Map TTPs**: Use AI to map corresponding tactics, techniques, and procedures (TTPs) to each stage of the attack.
3. **Align with ROE**: Ensure that all generated scenarios fit within the defined rules of engagement (ROE).

| Scenario                    | TTPs Mapped (ATT&CK IDs) | Safe for Testing? (Yes/No) | Risk Level |
| --------------------------- | ------------------------ | -------------------------- | ---------- |
| Exploit web application     | T1071, T1190             | Yes                        | High       |
| Brute-force VPN credentials | T1110, T1040             | No                         | Medium     |
| Lateral movement via SMB    | T1021, T1071             | Yes                        | Low        |

---

#### **3.2 Mapping Red Actions to Blue Detections**

### **AI-Assisted Action-Deduction Mapping**

Use AI to correlate red-team actions with blue-team logs. For each of the following red actions, use the AI to match the corresponding detections.

| Red Action                    | Corresponding Detection (Blue Team Log) | Detection Fired? (Yes/No) | Gaps/Improvements          |
| ----------------------------- | --------------------------------------- | ------------------------- | -------------------------- |
| Exploit web app vulnerability | HTTP Logs, Application Firewall Logs    | Yes                       | None                       |
| Brute-force VPN login         | VPN Logs, Auth Logs                     | No                        | Add multi-factor detection |
| Lateral movement via SMB      | SMB Logs, Network Traffic Logs          | Yes                       | Tuning needed              |

---

#### **3.3 Detection Gap Analysis**

### **AI-Driven Gap Analysis Exercise**

Using an AI-powered platform (like Chronicle AI or Elastic Detection AI), conduct a detection gap analysis on the following exercise scenario. Identify key coverage areas missing from the red-team actions and blue-team detections.

| Red Action                   | Missing Coverage/Gap in Detection       | Suggested Detection Rule                  |
| ---------------------------- | --------------------------------------- | ----------------------------------------- |
| Phishing email delivered     | Email filtering logs not collected      | Create rule for phishing URLs             |
| SMB lateral movement         | Lack of SMB traffic analysis            | Add rule to detect SMB anomalies          |
| Privilege escalation via SSH | Missing SSH event logging in cloud logs | Implement cloud-based SSH event detection |

---

#### **3.4 Automated Log Correlation & Telemetry Analysis**

### **AI Telemetry Correlation Exercise**

Use AI tools (e.g., Microsoft Defender AI, Chronicle SecOps AI) to correlate logs from a simulated purple-team engagement.

1. **Action Log**: Red-team executes lateral movement from one machine to another.
2. **Detection Log**: Blue team has logs from the network and host devices.
3. **Correlate**: Use AI to build a timeline of actions, summarizing detections and highlighting any missed gaps.

| Action                    | Detection Observed (Yes/No) | Log Source   | Suggested Improvements         |
| ------------------------- | --------------------------- | ------------ | ------------------------------ |
| Lateral movement detected | Yes                         | Host Logs    | None                           |
| Unusual network traffic   | No                          | Network Logs | Add traffic baseline detection |

---

#### **3.5 Continuous Validation & Automation**

### **Continuous Detection Testing Exercise**

Using platforms like MITRE Caldera or AttackIQ, schedule a weekly test cycle to automatically run detection validation tests. This should include:

1. **Automated Scenarios**: Use AI to generate and run automated adversary emulation tests each week.
2. **Score Detection Performance**: Review how well the detection rules performed and identify areas for improvement.

| Test Case                    | Detection Accuracy (%) | Recommended Changes                  | Priority |
| ---------------------------- | ---------------------- | ------------------------------------ | -------- |
| Exploiting a web app         | 80%                    | Refine web traffic anomaly detection | High     |
| Privilege escalation via SSH | 70%                    | Improve SSH event rule detection     | Medium   |
| Phishing detection           | 90%                    | Increase phishing awareness rules    | Low      |

---

### 🔐 **4. SECTION 3 — ETHICAL CONSIDERATIONS & GOVERNANCE**

---

#### **4.1 Ethical & Legal Boundaries**

### **Activity: Ethical Considerations in Purple Teaming**

Reflect on a purple-team exercise where AI tools were used. How did the use of AI help maintain **ethical** and **legal** boundaries? Answer the following:

1. **Scope Compliance**: How did AI ensure that only authorized tests were executed?
2. **Oversight**: Describe how human oversight was maintained while using AI.
3. **Data Protection**: How did AI ensure that sensitive information was protected during collaboration?

---

### 🧠 **5. FINAL ASSESSMENT & APPLICATION**

#### **Knowledge Questions**

1. How can AI improve scenario planning and test case design for purple teams?
2. What are the benefits of using AI for detecting gaps in blue-team defenses?
3. How does AI assist in validating detection rules and improving SOC maturity?
4. What are the ethical considerations when using AI for purple-team collaboration?
5. In what ways does AI help automate the detection validation process?

---

#### **Scenario-Based Exercise**

Given a **purple-team engagement scenario**, describe how AI can be used throughout the lifecycle of the test. Ensure your explanation covers:

1.


**Scenario Design & Test Planning** (Which tools to use?)
2. **Detection Validation** (How can AI assist?)
3. **Reporting & Post-Test Analysis** (How does AI help summarize the findings?)

---
