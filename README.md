# 🛡 Security Operations Lab (SOC Simulation Environment)

## 📌 Overview
This project is a simulated Security Operations Center (SOC) home lab designed to demonstrate hands-on experience with endpoint security monitoring, SIEM analysis, and incident response workflows.

The lab focuses on detecting, analyzing, and responding to simulated security events in a controlled Windows-based environment using Splunk for log ingestion and analysis.

---

## 🧱 Lab Architecture

- **Endpoint:** Windows 10/11 virtual machine (victim system)
- **Logging Source:** Windows Event Logs (Security, System, Application)
- **SIEM / Monitoring Tool:** Splunk (Free Tier / Enterprise Trial)
- **Attack Simulation:** Manual and scripted security event generation
- **Analysis Platform:** Splunk dashboards, searches, and alerts

---

## 🎯 Objectives

- Generate and monitor security-relevant system activity in a Windows environment  
- Ingest and analyze logs using Splunk SIEM  
- Detect suspicious authentication attempts and endpoint behavior  
- Correlate events across multiple log sources  
- Perform structured incident investigations using SOC workflows  
- Document findings using professional incident reporting practices  

---

## ⚔️ Simulated Attack Scenarios

This lab includes controlled simulations of:

- Brute force login attempts  
- Failed authentication patterns  
- Suspicious PowerShell execution  
- Unauthorized access attempts  
- Endpoint process and behavior anomalies  

---

## 📊 Splunk SIEM Usage

- Ingest Windows Event Logs into Splunk for analysis  
- Use Splunk Search Processing Language (SPL) to investigate security events  
- Create queries to detect failed logins, suspicious processes, and anomalous behavior  
- Build dashboards to visualize authentication activity and endpoint events  
- Configure alerts to identify potential security incidents in real time  

---

## 🔍 Investigation Workflow

Each simulated scenario follows a structured SOC process:

1. **Detection** – Identify suspicious activity via Splunk dashboards or alerts  
2. **Triage** – Assess severity and potential impact  
3. **Analysis** – Correlate logs and identify root cause using Splunk searches  
4. **Containment** – Simulate response actions based on findings  
5. **Documentation** – Create incident reports summarizing investigation results  

---

## 📊 Skills Demonstrated

- Splunk SIEM analysis and alert triage  
- Windows Event Log analysis  
- Incident response lifecycle (NIST framework)  
- Threat detection and log correlation  
- Security investigation and reporting  
- Endpoint behavior analysis  
- SPL (Search Processing Language) for log queries  

---

## 📁 Repository Structure

- `/windows-endpoint` – Endpoint configuration and log generation notes  
- `/siem-setup` – Splunk setup, ingestion, and configuration notes  
- `/attack-simulations` – Simulated attack scenarios and test cases  
- `/incident-reports` – SOC-style investigation reports  
- `/screenshots` – Evidence of logs, dashboards, and alerts  

---

## 📌 Notes

This project is part of an ongoing cybersecurity portfolio focused on building real-world SOC analyst skills through hands-on simulation, Splunk-based log analysis, and structured incident response practice.
