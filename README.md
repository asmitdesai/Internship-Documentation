# 🔐 Internship Project: Open-Source SOC Stack for Threat Detection & Response

**🧑‍💻 Role:** Cybersecurity Enginner Intern  
**📅 Duration:** 8 Weeks  
**📂 Project Type:** End-to-End Security Monitoring & Automation using Open Source Tools

---

## 🧩 Overview

Built a comprehensive open-source **Security Operations Center (SOC)** stack by integrating SIEM, EDR, SOAR, and threat intelligence. The solution supports real-time detection, enrichment, and automated response to adversary techniques in a simulated enterprise environment.

---

## ⚙️ Key Features

### 🔍 SIEM Deployment (Wazuh 4.12)
- Installed and configured **Wazuh** on Ubuntu with Linux and Windows agents.
- Enabled log collection for system events, audit logs, and database logs (**MariaDB & PostgreSQL**).
- Used `rsyslog` and custom JSON-export scripts for log forwarding.

### 🧠 Threat Intelligence Enrichment
- Integrated **MISP** and **VirusTotal** APIs for automatic enrichment of:
  - File hashes
  - IP addresses
  - Filenames (flagged even on name match)
- Enriched Wazuh alerts with contextual threat intelligence.

### 🚀 SOAR Automation using Shuffle
- Developed workflows in **Shuffle 1.4.0** to:
  - Parse IOCs from Wazuh alerts using JSONPath
  - Query MISP and VirusTotal
  - Trigger Slack/email alerts for positive matches
- Reduced mean time to respond (MTTR) and minimized manual triage.

### 🛡 Endpoint Visibility with Velociraptor
- Deployed **Velociraptor** for endpoint monitoring and forensics.
- Queried:
  - Running processes
  - Startup scripts
  - Persistence mechanisms
  - Registry changes
- Enabled live threat hunting and anomaly detection.

### 🛑 Active Defense with Fail2Ban
- Configured **Fail2Ban** to monitor `/var/log/auth.log` for brute-force attempts.
- Automatically banned offending IPs and forwarded events to Wazuh.

### 🧪 Adversary Simulation (Atomic Red Team)
- Used **Atomic Red Team (ART)** to simulate real-world attacks (e.g., T1003 – Credential Dumping).
- Validated Wazuh’s detection rules and alerting mechanisms.

### 📊 Dashboards & Visualization
- Created custom dashboards in **Kibana** for:
  - Linux and Windows activity
  - Threat enrichment hits
  - Fail2Ban events
  - Simulated attacks and correlation maps

---

## 🧰 Tech Stack
•Wazuh 
• MISP 
•VirusTotal 
• Velociraptor 
• Shuffle SOAR 
• Atomic Red Team
•Fail2Ban 
• PostgreSQL 
• MariaDB 
•Python 
• Bash 
• Sysmon

## ✅ Outcomes

- 🚀 Delivered a **production-ready**, modular SOC platform using open-source technologies.
- 🔁 Achieved full-stack automation from detection to response using Wazuh + Shuffle.
- 🎯 Hands-on experience across **SIEM tuning, SOAR automation, EDR, and threat simulation**.
- 📈 Developed executive-ready dashboards to visualize attack surface and mitigation status.

---
## 📬 Contact

**Asmit Desai**  
Connect on [LinkedIn](https://www.linkedin.com/in/asmit-desai-858668230/)  
Reach out for collaboration, mentoring, or resume opportunities!

---
