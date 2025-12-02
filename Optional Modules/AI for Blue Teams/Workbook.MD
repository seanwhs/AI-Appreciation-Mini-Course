# 🔵 **AI FOR BLUE TEAMS — WORKBOOK**

*A hands-on workbook designed for SOC analysts, IR teams, and defensive security professionals learning to integrate AI into daily operations.*

---

# **TABLE OF CONTENTS**

1. Pre‑Assessment
2. Section 1: AI Foundations
3. Section 2: Operational Blue Team AI
4. Section 3: Playbook Worksheets
5. Section 4: Real-World Exercises
6. Section 5: Metrics & Improvement
7. Section 6: Final Assessment
8. Templates & Cheat Sheets

---

# ⚡ **1. PRE‑ASSESSMENT**

### **1.1 Self‑Rating**

Rate your current knowledge (1 = none, 5 = strong):

| Skill Area                              | Rating (1–5) |
| --------------------------------------- | ------------ |
| SIEM alert triage                       |              |
| Incident investigation                  |              |
| Threat intelligence enrichment          |              |
| Detection engineering                   |              |
| Log analysis                            |              |
| AI tools (Sentinel AI, Splunk AI, etc.) |              |

---

### **1.2 Knowledge Check**

**Circle YES/NO**

1. I have used automation or SOAR playbooks before.
2. I know how ML models detect anomalies.
3. I understand which SOC tasks are repetitive vs. analytical.
4. I am aware of human-in-the-loop requirements for AI.

---

# 🧠 **2. SECTION 1 — AI FOUNDATIONS**

---

## **2.1 Understanding AI Roles in Blue Teams**

### **Worksheet:** Classify AI Tasks

Place each task into the correct category.

| Task                                    | AUTOMATION | AUGMENTATION | ACCELERATION |
| --------------------------------------- | ---------- | ------------ | ------------ |
| Drafting an incident summary            |            |              |              |
| Correlating alerts                      |            |              |              |
| Suggesting next IR steps                |            |              |              |
| Enriching an IOC                        |            |              |              |
| Tuning a noisy detection                |            |              |              |
| Running a containment action (approved) |            |              |              |

---

## **2.2 Human-in-the-Loop Responsibilities**

### **Reflection Prompt:**

*List 3 actions that must **always** require human approval in your environment.*

1.
2.
3.

---

## **2.3 Blue Team AI Maturity Model**

### **Exercise:** Where is your SOC?

Circle your current level.

* Level 0: No AI
* Level 1: AI-assisted (text queries/summaries)
* Level 2: AI integrated into tools
* Level 3: AI automated workflows
* Level 4: Predictive, adaptive detection
* Level 5: Autonomous (human-governed)

### **What prevents you from reaching the next level?**

*Write 2 blockers:*
1.
2.

---

# 🔍 **3. SECTION 2 — OPERATIONAL BLUE TEAM AI**

---

# **3.1 Alert Triage Workbook**

### **Activity: Identify AI-Ready Alerts**

Select 3 alerts from your SIEM (or provided sample logs) and decide whether AI can help.

| Alert Name | Data Volume | Repetitive? | Needs Enrichment? | Good AI Candidate? (Y/N) |
| ---------- | ----------- | ----------- | ----------------- | ------------------------ |
|            |             |             |                   |                          |
|            |             |             |                   |                          |
|            |             |             |                   |                          |

### **Prompt Practice:**

Write a prompt you would use to ask an AI assistant to triage an alert.

```
Prompt:
```

---

# **3.2 Incident Investigation Workbook**

### **Timeline Reconstruction Exercise**

Given the log sample (trainer provides), fill in:

| Timestamp | Event | System | Notes (AI‑generated or human) |
| --------- | ----- | ------ | ----------------------------- |
|           |       |        |                               |
|           |       |        |                               |

### **Next-Step Decision Tree**

Check what AI should suggest:

* [ ] Check lateral movement
* [ ] Validate identity events
* [ ] Hunt for related hosts
* [ ] Check suspicious processes
* [ ] Extract IOCs

Which ones did you choose and why?

---

# **3.3 Threat Intelligence & IOC Enrichment**

### **IOCs to Enrich**

| IOC | Type | Reputation | Related Threats | Additional IOCs Found |
| --- | ---- | ---------- | --------------- | --------------------- |
|     |      |            |                 |                       |
|     |      |            |                 |                       |

### **Reflection:**

How does AI reduce enrichment time?
(Write 2–3 sentences)

---

# **3.4 Detection Engineering Workbook**

### **Rule Rewrite Exercise**

Given a noisy or incomplete sample rule, rewrite it with the help of AI.

**Original Detection:**

```
<Trainer inserts sample SPL, KQL, or Sigma>
```

**AI-Enhanced Version:**

```
<Your improved version>
```

### **Now complete the checklist:**

| Concept                  | Before | After |
| ------------------------ | ------ | ----- |
| False positives reduced  |        |       |
| Mapped to MITRE ATT&CK   |        |       |
| Added contextual filters |        |       |
| Documentation updated    |        |       |

---

# **3.5 Forensics & Log Analysis**

### **Artifact Review Worksheet**

| Artifact       | AI Summary | Human Validation | Action Needed |
| -------------- | ---------- | ---------------- | ------------- |
| Sysmon log     |            |                  |               |
| Network flow   |            |                  |               |
| Identity event |            |                  |               |

---

# **3.6 Cloud Security Worksheet**

### **IAM Misconfiguration Review**

AI flags the following issues (trainer picks or you simulate):

| Finding                        | Severity | AI Recommendation | Analyst Decision |
| ------------------------------ | -------- | ----------------- | ---------------- |
| Overprivileged service account | High     |                   |                  |
| Public S3 bucket               | Critical |                   |                  |
| Stale admin credentials        | Medium   |                   |                  |

---

# **3.7 Vulnerability Prioritization Workbook**

### **Exploit Likelihood vs. Asset Value Matrix**

Fill in:

| CVE | External Exposure? | Asset Criticality | Known Exploits? | Priority |
| --- | ------------------ | ----------------- | --------------- | -------- |
|     |                    |                   |                 |          |
|     |                    |                   |                 |          |

---

# 🧪 **4. SECTION 3 — REAL-WORLD SCENARIOS**

---

## **Scenario 1 — Suspicious Login Sequence**

You detect:

* Multiple failed logins
* Successful login from new location
* Token issuance for sensitive resource

### **Your Tasks**

1. Use AI to summarize the event chain.
2. Choose which logs to pull next.
3. Identify possible attacker goals.
4. Draft a containment recommendation.

---

## **Scenario 2 — Endpoint Beaconing**

Signals:

* Periodic outbound traffic
* Destination unknown
* Process created by user profile

### **Your Tasks**

1. Ask AI for enrichment of the domain/IP.
2. Ask AI for “next 5 investigative steps.”
3. Document decisions in table:

| Step | Action | Human or AI Suggested? | Result |
| ---- | ------ | ---------------------- | ------ |
|      |        |                        |        |

---

## **Scenario 3 — Cloud IAM Drift**

Your CSPM flags new permissions granted unexpectedly.

### **Workbook Tasks**

1. Summarize the risk.
2. Ask AI for least-privilege recommendations.
3. Define what *you* must verify manually.

---

# 📊 **5. SECTION 4 — METRICS & IMPROVEMENT**

---

## **5.1 SOC AI Metrics Worksheet**

Rank where AI has improved:

| Area                 | Before (Score 1–5) | After (Score 1–5) |
| -------------------- | ------------------ | ----------------- |
| Triage Time          |                    |                   |
| Alert Noise          |                    |                   |
| Detection Quality    |                    |                   |
| Incident Containment |                    |                   |
| Report Quality       |                    |                   |

---

## **5.2 Continuous Improvement Plan**

Write 3 actions to improve your AI workflows:

1.
2.
3.

---

# 📝 **6. FINAL ASSESSMENT**

### **Knowledge Questions**

1. Name two SOC tasks well suited for AI automation.
2. What must AI *never* do without human approval?
3. What is one risk of overusing AI in blue-team operations?
4. Why is enrichment a strong use case for AI?

### **Scenario Wrap-Up**

Given a mock alert of your instructor’s choosing:

* Write an AI prompt
* Summarize AI output
* Provide your human judgment decision
* Recommend a mitigation step

---

# 📎 **7. TEMPLATES & CHEAT SHEETS**

Included:

✔ AI Prompt Templates
✔ AI Decision Log Template
✔ Incident Summary Template
✔ Detection Engineering Template
✔ IOC Enrichment Template
✔ Alert Triage Checklist
✔ MITRE Mapping Capture Sheet
✔ 1‑Page “Blue Team AI Cheat Sheet”

(Just ask and I’ll generate these individually.)

---
