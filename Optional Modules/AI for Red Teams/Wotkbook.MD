# 🔴 **AI FOR RED TEAMS — WORKBOOK**

*A comprehensive, interactive workbook designed to help learners understand and apply AI in red-team engagements while adhering to ethical boundaries.*

---

## **TABLE OF CONTENTS**

1. Pre‑Assessment
2. Section 1: AI in Red Teaming – Overview
3. Section 2: AI-Enhanced Red Team Operations
4. Section 3: Hands-On Exercises & Playbooks
5. Section 4: Reporting & Collaboration
6. Section 5: Ethical Considerations & Governance
7. Section 6: Final Assessment & Application
8. Templates & Cheat Sheets

---

# ⚡ **1. PRE‑ASSESSMENT**

### **1.1 Self-Assessment**

Rate your current knowledge on the following topics (1 = None, 5 = Strong):

| Skill Area                                 | Rating (1–5) |
| ------------------------------------------ | ------------ |
| Red Teaming Fundamentals                   |              |
| Reconnaissance & OSINT                     |              |
| Adversary Emulation Planning               |              |
| MITRE ATT&CK Framework                     |              |
| Ethical & Legal Constraints in Red Teaming |              |
| Use of AI for Attack Path Modeling         |              |
| Report Generation & Documentation          |              |

---

### **1.2 Knowledge Check**

Circle YES or NO based on your experience:

1. Do you use AI tools for reconnaissance or data aggregation? (YES/NO)
2. Are you familiar with using MITRE ATT&CK for attack path modeling? (YES/NO)
3. Do you use AI to automate report generation or documentation? (YES/NO)
4. Have you worked on a red-team exercise with an AI-assisted planning tool? (YES/NO)
5. Do you understand the importance of ethical boundaries in red teaming? (YES/NO)

---

# 🧠 **2. SECTION 1 — AI IN RED TEAMING – OVERVIEW**

---

## **2.1 Role of AI in Red Teaming**

### **Activity: AI’s Role in Red Team Tasks**

Review the following red-team tasks and decide if they’re best suited for **AI support** or **human expertise**:

| Task                              | AI Support | Human Expertise | Why?                                               |
| --------------------------------- | ---------- | --------------- | -------------------------------------------------- |
| Reconnaissance & data aggregation | Yes        | No              | AI can process large datasets quickly.             |
| Adversary simulation planning     | Yes        | Yes             | AI can assist, but humans define strategies.       |
| Ethical review of attack paths    | No         | Yes             | Requires human judgment.                           |
| Reporting findings                | Yes        | Yes             | AI drafts reports, but humans refine and validate. |

---

## **2.2 AI in Red Team Workflows**

Reflect on where AI can help in a red-team engagement.

* **Reconnaissance**: Summarize public data, identify exposed services, map technologies.
* **Adversary Simulation**: Model attack paths and suggest adversary behaviors.
* **Exercise Analysis**: Monitor telemetry, identify detection gaps, and summarize red-team actions.

**List three red-team activities that would benefit most from AI integration:**

1.
2.
3.

---

## **2.3 Key AI Tools for Red Teaming**

List and describe any tools mentioned in the module or tools you’ve used in red teaming that incorporate AI capabilities.

| Tool Name     | Primary Use                        | AI Capabilities                          |
| ------------- | ---------------------------------- | ---------------------------------------- |
| MITRE Caldera | Adversary emulation                | AI-driven attack path modeling           |
| PlexTrac      | Red-team reporting & collaboration | AI-enhanced reporting & team interaction |
| SafeBreach AI | Attack simulation                  | AI to model attack paths                 |
| Maltego AI    | Reconnaissance & OSINT             | AI-driven data aggregation & analysis    |

---

# 🔍 **3. SECTION 2 — AI-ENHANCED RED TEAM OPERATIONS**

---

## **3.1 Reconnaissance & Target Profiling**

### **AI-Driven Recon Exercise**

Given a list of publicly available data about an organization, perform the following tasks using AI tools:

1. **Summarize** the organization’s public footprint (domains, assets, tech stack).
2. **Identify** any exposed services or potential attack surfaces.
3. **Generate** a prioritized list of areas for deeper investigation.

| Finding                    | Risk Level | Suggested Action                     |
| -------------------------- | ---------- | ------------------------------------ |
| Exposed FTP service        | High       | Investigate for misconfigurations    |
| Public GitHub repositories | Medium     | Look for sensitive information leaks |
| External-facing web server | Low        | Assess for vulnerabilities           |

---

## **3.2 Adversary Emulation & Attack Path Modeling**

### **Scenario Planning with AI**

Using AI-assisted attack path modeling tools, create an emulation plan for the following scenario:
**Scenario**: A corporate network has a web application, a VPN, and a file server exposed to the internet. The red team’s goal is to model an attack path based on real-world tactics.

1. **Step 1:** Input network topology (or diagram).
2. **Step 2:** Have AI map possible attack paths.
3. **Step 3:** Choose paths that align with rules of engagement (ROE).

| Attack Path                | TTPs (MITRE)             | Feasibility | Next Steps                       |
| -------------------------- | ------------------------ | ----------- | -------------------------------- |
| Exploiting web server      | Initial Access (T1071)   | High        | Test web app vulnerability       |
| VPN login brute-forcing    | Persistence (T1053)      | Medium      | Test VPN credentials             |
| File server access via SMB | Lateral Movement (T1021) | Low         | Investigate network segmentation |

---

## **3.3 Reporting, Narrative Building & Documentation**

### **AI-Assisted Reporting Exercise**

Using AI-powered tools (e.g., Notion AI, PlexTrac), generate a draft report for an engagement that included:

1. **Key Findings**
2. **Attack Paths Mapped to MITRE ATT&CK**
3. **Impact on the Organization**
4. **Suggested Recommendations**

| Report Section        | AI-Generated Content                  | Action Needed       |
| --------------------- | ------------------------------------- | ------------------- |
| Executive Summary     | Summary of objectives & outcomes      | Validate and refine |
| Attack Path Narrative | Path modeled based on engagement data | Check for accuracy  |
| Impact & Risk         | High/Medium/Low impact assessment     | Adjust as necessary |

---

# 🔧 **4. SECTION 3 — ETHICAL CONSIDERATIONS & GOVERNANCE**

---

## **4.1 Ethical & Compliance Guidance**

### **Activity: Ethical Boundaries in Red Teaming**

Review a potential red-team engagement scenario and determine how AI can help maintain ethical boundaries:

**Scenario**: The red team is tasked with testing a company’s cloud infrastructure. The scope is clearly defined, but the team may accidentally trigger real incidents in the cloud provider’s environment.

* **AI Assistance:** How can AI ensure that only in-scope assets are targeted and potential scope violations are flagged?

1. **AI Compliance Check:** AI can map the planned actions to ROE, providing real-time alerts if actions deviate.
2. **Human Oversight:** Team members review flagged activities before execution.

**Your Ethical Considerations:**

* What steps would you take to ensure the AI stays within the boundaries of the engagement?
* How do you ensure human operators remain in control?

---

## **4.2 Governance & ROE Enforcement**

### **Activity: Defining AI Governance**

Define the parameters under which AI can assist in a red-team engagement, ensuring it aligns with governance and ROE:

1. **AI Role Definition:** List actions that AI can take (e.g., planning, reporting, modeling).
2. **Oversight Requirements:** Identify points at which human operators must step in (e.g., after AI generates attack paths).
3. **Audit Trails:** Define what needs to be logged to maintain accountability for AI-assisted actions.

---

# 📊 **5. FINAL ASSESSMENT & APPLICATION**

### **Knowledge Questions**

1. How can AI enhance red-team reconnaissance without crossing ethical boundaries?
2. Describe how AI helps with adversary simulation planning and attack path modeling.
3. What are the critical ethical considerations when using AI in red teaming?
4. How does AI assist in reporting and debriefing after an engagement?
5. What’s the difference between AI support and human decision-making in red-team operations?

### **Scenario-Based Exercise**

Given the following hypothetical situation, explain how you would leverage AI for planning and reporting:

* **Scenario**: A red team is engaged in a penetration test of a corporate network that includes a combination of on-premises infrastructure and cloud services.

  * Describe how AI can assist with reconnaissance and emulation planning.
  * How would you ensure that the engagement stays within the agreed-upon scope?
  * What AI tools would help in post-exercise reporting?

---

# 📎 **6. TEMPLATES & CHEAT SHEETS**

Included:

✔ **AI Playbook Template for Red Teams**
✔ **Reconnaissance AI Checklist**
✔ **MITRE ATT&CK Mapping Template**
✔ **Adversary Emulation Plan Template**
✔ **AI-Generated Report Template**
✔ **


