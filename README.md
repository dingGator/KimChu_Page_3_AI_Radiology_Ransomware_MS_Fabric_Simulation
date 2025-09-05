# 📄 Page 3 – AI-Enabled Radiology Ransomware Simulation

**Theme**: SOC Response to AI Risk in Healthcare  
**Author**: Kim Lien Chu – Healthcare Cybersecurity Analyst  
**Source**: HHS 405(d) Volume XXV (July 2024)

---

## 📁 Artifact Download

📄 Full PDF with embedded visuals and dashboards:  
[KimChu_Page_3_AI_Radiology_Ransomware_MS_Fabric_Simulation.pdf](KimChu_Page_3_AI_Radiology_Ransomware_MS_Fabric_Simulation.pdf)

---

## 🧠 Overview

This simulation models a ransomware attack targeting an AI-powered radiology platform. It explores adversarial AI behavior, poisoned training data, and SOC response mapped to HHS 405(d) Volume XXV. The scenario highlights gaps in AI governance and operational readiness across healthcare environments.

---

## 📊 Artifact Includes

- Scenario summary and impact  
- Splunk and KQL detection logic  
- Microsoft Fabric integration (Eventstream, Power BI)  
- AI risk matrix and governance alignment  
- SOC response phases: containment, investigation, recovery  
- Strategic takeaways for healthcare defenders

---

## 🔍 Detection Logic Files

Detection logic used in this simulation is available as standalone `.txt` files:

- 📄 [`splunk-query.txt`](detection-logic/splunk-query.txt) – Flags poisoned trigger phrase `"zebra123"` in radiology logs  
- 📄 [`kql-query.txt`](detection-logic/kql-query.txt) – Simulates real-time detection in Microsoft Fabric using mock telemetry

These files complement the embedded visuals and support SOC teams in adapting detection logic across platforms.

---

## 📚 References

- [HHS 405(d) Volume XXV](https://405d.hhs.gov)  
- [Microsoft Fabric Documentation – Real-Time Intelligence](https://learn.microsoft.com/en-us/fabric/real-time-intelligence)  
- [Splunk Adversarial ML Content](https://research.splunk.com)  
- [HIPAA Security Rule – HHS.gov](https://www.hhs.gov/hipaa/for-professionals/security/index.html)  
- [CISA Strategic Risk Management Framework (SRMA)](https://www.cisa.gov/resources-tools)

---

📌 This is Page 3 of my healthcare cybersecurity portfolio.  
Pages 1 and 2 are housed in [`KimChu_Healthcare_Cybersecurity_Portfolio`](https://github.com/dingGator/KimChu_Healthcare_Cybersecurity_Portfolio).

Feedback welcome from SOC leads, AI governance teams, and healthcare defenders.