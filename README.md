# Local SIEM Lab Project
# Local SIEM Lab Project

## Project Overview
This project demonstrates a **local Security Information and Event Management (SIEM) lab** using **Wazuh** on a **RHEL virtual machine**. The lab is designed to simulate a real-world SOC (Security Operations Center) environment, collecting system and authentication logs, analyzing events, and generating alerts for suspicious activities such as failed logins and port scans.  

This project serves as a **hands-on demonstration of SOC monitoring workflows**, including log collection, alerting, and dashboard visualization.

---

## Tools and Technologies Used
- **RHEL VM** – Host for Wazuh Manager and Filebeat  
- **Kali Linux VM (optional)** – Simulate attacks and generate logs  
- **Wazuh Manager & Agent** – Core SIEM system for log collection and alerting  
- **Kibana Dashboard** – Visualize security events and alerts  
- **Windows 10 Host** – GitHub version control and project management  
- **Git & GitHub** – Version control and portfolio hosting  

---

## Folder Structure

```text
/local-siem-lab
│
├── logs/                  # Sample log files
│   ├── auth_failures.log  # Simulated authentication failures
│   └── port_scan.log      # Simulated port scan events
│
├── screenshots/           # Dashboard screenshots (placeholders)
│   ├── dashboard.png
│   └── alert_example.png
│
├── README.md              # Project overview and setup instructions
This project demonstrates a local SIEM setup using Wazuh on RHEL. Dashboard screenshots and sample logs are included.
