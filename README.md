# phishing-incident-response-journal

# 🎣 Phishing Incident Response Journal & Case Analysis

This project documents a full incident response lifecycle around a simulated phishing campaign, covering real-time alerts, investigation, escalation, and final analysis. It also includes a playbook for phishing response, a structured incident handler's journal, and a high-level breach review report.

The goal of this project is to showcase how phishing incidents are identified, triaged, escalated, documented, and reflected on using a combination of SOC workflows and security tools.

---

## 🧠 What This Project Covers

- Alert ticket triage and documentation  
- Investigation using tools like **VirusTotal**, **SHA-256 hashing**, and **SIEM logs**  
- Escalation decisions based on **threat indicators**  
- Use of a **Phishing Playbook** to guide standard operating procedures  
- Final report write-up of a **realistic PII data breach scenario**  
- Personal reflection on tools, techniques, and learning

---

## 📋 Key Components

### 🗂 Incident Handler Journal
- Tracks **five separate incidents**, including:
  - Phishing campaigns leading to ransomware deployment
  - Malicious attachments identified via file hash analysis
  - Use of **Google Chronicle** and **VirusTotal**
  - Escalation workflow and post-incident review
- Documents tools used and maps activity to NIST incident response phases

📄 [Incident_Handler_Journal.pdf](Incident_Handler_Journal.pdf)

---

### 🚨 Alert Ticket
- Alert ID: **A-2703**  
- Phishing attempt with malicious executable (.exe) attached  
- Evaluated indicators:
  - Suspicious email address and IP mismatch  
  - Spelling/grammar issues in email body  
  - Confirmed malicious hash via **VirusTotal**  
- Escalated to level-two SOC analyst

📄 [Alert_Ticket.pdf](Alert_Ticket.pdf)

---

### 📘 Phishing Playbook
A step-by-step phishing investigation guide used to evaluate alert tickets.

Includes:
- Evaluation criteria for alert triage  
- Procedures for link/attachment analysis  
- Escalation flow and closure steps  
- Visual flowchart of phishing incident workflow

📄 [Phishing_Playbook_Version_1.0.pdf](Phishing_Playbook_Version_1.0.pdf)

---

### 📑 Final Report: PII Data Breach Review
- Covers a **forced browsing attack** that exploited URL-based access to transaction records  
- Over **50,000 customers affected**  
- Incident caused by unprotected e-commerce web application routes  
- Root cause analysis, remediation, and public response included

📄 [Final_Report.pdf](Final_Report.pdf)

---

## 🔍 Skills Demonstrated

- Incident detection and investigation  
- Phishing response and escalation  
- SOC documentation and communication  
- Malware identification via hashing  
- Use of tools like VirusTotal and Chronicle  
- NIST CSF mapping and lifecycle reporting  

---

> 🗒️ *All materials are based on fictional scenarios created for educational purposes.*
