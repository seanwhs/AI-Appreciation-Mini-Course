### **Task Suitability Matrix for AI in Tabletop Exercises (TTX)**

The **Task Suitability Matrix** helps identify where AI can be applied in **Tabletop Exercises (TTX)**. By evaluating the nature of each task and its alignment with AI capabilities, you can determine whether AI is a suitable tool for automating, augmenting, or optimizing each task.

---

### **AI Task Suitability Criteria**

1. **Repetitive:** Tasks that are performed frequently, often in a similar manner, and do not require significant variation.
2. **Pattern-Heavy:** Tasks that rely on recognizing or generating predictable patterns (e.g., recognizing attack types, detecting behavioral anomalies).
3. **Error-Prone:** Tasks that are susceptible to human error or inconsistent execution.
4. **Time-Consuming:** Tasks that require substantial time investment without the need for complex decision-making.
5. **Documentation-Heavy:** Tasks that require extensive documentation or tracking of events, decisions, or outcomes.
6. **Alert-Heavy:** Tasks that involve a large number of alerts or notifications that need to be processed, categorized, or acted upon.
7. **Learning/Prototyping:** Tasks that require experimentation or the creation of new threat models or attack paths based on evolving data.

---

### **Task Suitability Matrix for AI in Tabletop Exercises (TTX)**

| Task                                           | Repetitive | Pattern-Heavy | Error-Prone | Time-Consuming | Documentation-Heavy | Alert-Heavy | Learning/Prototyping | AI Suitability (Low/Med/High) | Example AI Tool/Platform             |
| ---------------------------------------------- | ---------- | ------------- | ----------- | -------------- | ------------------- | ----------- | -------------------- | ----------------------------- | ------------------------------------ |
| **Scenario Generation**                        | Yes        | Yes           | No          | No             | No                  | No          | Yes                  | High                          | **SimSpace**, **Cortex XSOAR**       |
| **Real-Time Threat Intelligence Injects**      | No         | Yes           | Yes         | No             | No                  | Yes         | Yes                  | High                          | **Recorded Future**, **Anomali**     |
| **Adaptive Attack Simulations**                | Yes        | Yes           | Yes         | Yes            | No                  | No          | Yes                  | High                          | **Cortex XSOAR**, **CyberBit**       |
| **Incident Documentation**                     | Yes        | No            | Yes         | Yes            | Yes                 | No          | No                   | High                          | **Splunk SOAR**, **Power BI**        |
| **Post-Exercise Reporting**                    | Yes        | No            | No          | Yes            | Yes                 | No          | No                   | High                          | **Power BI**, **Tableau**            |
| **Facilitator Support & Performance Tracking** | Yes        | Yes           | Yes         | Yes            | Yes                 | Yes         | Yes                  | High                          | **Splunk SOAR**, **Exabeam**         |
| **Collaboration & Communication**              | No         | No            | Yes         | No             | No                  | Yes         | No                   | Medium                        | **Slack AI**, **Microsoft Teams AI** |
| **Injecting Real-Time Feedback**               | Yes        | Yes           | Yes         | Yes            | Yes                 | Yes         | Yes                  | High                          | **Cortex XSOAR**, **Darktrace**      |

---

### **Explanation of AI Suitability for Each Task:**

1. **Scenario Generation**
   AI can automate the creation of dynamic, evolving scenarios for TTX, pulling from threat intelligence feeds and historical data to generate relevant and realistic exercises. **AI Suitability: High**.

   * **Tools**: **SimSpace**, **Cortex XSOAR** (for adaptive scenario creation).

2. **Real-Time Threat Intelligence Injects**
   AI can inject real-time threat intelligence into a TTX scenario, such as external attacks, zero-day vulnerabilities, or newly discovered malware tactics. This can adapt the scenario on the fly based on actual, live data. **AI Suitability: High**.

   * **Tools**: **Recorded Future**, **Anomali** (for integrating live threat feeds).

3. **Adaptive Attack Simulations**
   AI can simulate evolving attack strategies, continuously changing attack vectors and techniques based on how the team responds. It adapts and challenges participants in real-time. **AI Suitability: High**.

   * **Tools**: **Cortex XSOAR**, **CyberBit** (for adaptive simulations and scenario changes).

4. **Incident Documentation**
   AI can automate the process of documenting actions, decisions, and responses during a tabletop exercise. This helps in accurate record-keeping and reduces human error in tracking events. **AI Suitability: High**.

   * **Tools**: **Splunk SOAR**, **Power BI** (for automated reporting and tracking).

5. **Post-Exercise Reporting**
   AI can generate detailed post-exercise reports, analyzing decisions, team performance, and identifying gaps in response. This saves time on manual reporting and ensures consistency across exercises. **AI Suitability: High**.

   * **Tools**: **Power BI**, **Tableau** (for analytics and reporting).

6. **Facilitator Support & Performance Tracking**
   AI tools can provide real-time feedback and insights to facilitators about team performance during the exercise. They can track how well participants are responding to the simulated threats and identify areas where teams are struggling. **AI Suitability: High**.

   * **Tools**: **Splunk SOAR**, **Exabeam** (for monitoring performance and providing facilitator support).

7. **Collaboration & Communication**
   While AI tools can aid collaboration (e.g., by providing real-time translations or suggesting next steps), the collaboration and communication aspect still relies on human interaction. **AI Suitability: Medium**.

   * **Tools**: **Slack AI**, **Microsoft Teams AI** (for supporting communication but not driving the decision-making).

8. **Injecting Real-Time Feedback**
   AI can provide teams with real-time feedback based on their actions, suggesting improvements or flagging critical mistakes. It can dynamically adjust scenarios or objectives based on team performance, creating a more personalized learning experience. **AI Suitability: High**.

   * **Tools**: **Cortex XSOAR**, **Darktrace** (for real-time feedback based on attack scenario progression).

---

### **Tool Recommendations**

Here are specific AI tools that match the tasks identified in the **Task Suitability Matrix** and will help organizations improve the quality and realism of their tabletop exercises:

1. **SimSpace** – Specializes in creating dynamic, real-world attack simulations that change in real time. Best for **scenario generation** and **adaptive attack simulations**.

2. **Cortex XSOAR** – A leading platform for security orchestration and automation that can manage **incident documentation**, **real-time feedback**, **scenario creation**, and **performance tracking**. It also enables **adaptive attack simulations**.

3. **Recorded Future** – Provides real-time, actionable threat intelligence and helps with **injecting real-time intelligence** into exercises. Best for **threat intelligence** and **real-time threat intelligence injects**.

4. **Splunk SOAR** – A robust platform for automating incident response and managing **incident documentation**, **performance tracking**, and **post-exercise reporting**.

5. **Anomali** – Specializes in threat intelligence and can be used to **inject real-time threat intelligence** into TTXs, keeping exercises grounded in actual threat data.

6. **Power BI** – For **post-exercise reporting** and **performance tracking**, as well as analyzing team performance and decision-making data.

7. **CyberBit** – Ideal for **adaptive attack simulations**, it enables organizations to simulate real-world attacks with AI-driven adaptive capabilities that evolve during the exercise.

8. **Darktrace** – Provides AI-powered threat detection and response, which is particularly useful for **adaptive attack simulations** and **real-time feedback** during the exercise.

---

### **Conclusion:**

Integrating AI into Tabletop Exercises can significantly enhance the realism, adaptability, and effectiveness of the training. By automating repetitive tasks such as scenario generation, real-time intelligence injects, and documentation, AI frees up valuable time for facilitators and participants to focus on strategic decision-making. The **Task Suitability Matrix** helps organizations identify where AI can be most effectively applied, ensuring that AI tools are used where they provide the greatest value.

Leveraging AI tools like **Cortex XSOAR**, **SimSpace**, and **Recorded Future** will elevate your organization’s TTX, making them more dynamic and responsive to the changing cybersecurity landscape.
