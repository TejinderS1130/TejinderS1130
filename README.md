# Tejinder Singh | SOC Analyst

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&color=00BFFF&center=true&vCenter=true&width=700&lines=SOC+Analyst;Threat+Detection+%7C+SIEM+%7C+Incident+Response;Splunk+%7C+Sentinel+%7C+MITRE+ATT%26CK;AWS+%7C+Cloud+Security+%7C+Threat+Hunting;Building+Real-World+SOC+Labs" />
</p>

---

Demonstrates how real-world attacks can be simulated, detected, and investigated using SIEM tools, cloud security platforms, and structured SOC workflows.

---

## About Me

Cybersecurity & Threat Management @ Seneca
📍 Toronto, Canada 🇨🇦

I build and operate **hands-on SOC environments** focused on detecting, analyzing, and responding to real-world attacks across **on-prem and cloud infrastructure**.

My work centers on **authentication-based threats** (brute force, password spraying, credential access) using SIEM platforms like **Splunk and Microsoft Sentinel**, with detection logic mapped to **MITRE ATT&CK**.

I specialize in turning **raw telemetry into actionable detections**, correlating events across **Linux, Windows, network devices, and cloud environments (AWS)** to improve visibility and reduce detection gaps.

---

## Core Skills & Tools

---

### SIEM & Detection

<p align="center">
  <img src="https://img.shields.io/badge/SIEM-Splunk-blue?style=for-the-badge&logo=splunk"/>
  <img src="https://img.shields.io/badge/SIEM-Microsoft%20Sentinel-purple?style=for-the-badge&logo=microsoft"/>
  <img src="https://img.shields.io/badge/EDR-Microsoft%20Defender-black?style=for-the-badge&logo=microsoft"/>
  <img src="https://img.shields.io/badge/Security-MITRE%20ATT%26CK-red?style=for-the-badge"/>
</p>

SPL (Splunk Query Language) • KQL (Kusto Query Language)
Detection Engineering • Threat Hunting • Alert Tuning
Log Correlation (Multi-source) • MITRE ATT&CK Mapping

---

### IDS / IPS & Network Security Monitoring

<p align="center">
  <img src="https://img.shields.io/badge/IDS%2FIPS-Suricata-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Firewall-pfSense-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/VPN-OpenVPN-green?style=for-the-badge"/>
</p>

* Intrusion Detection & Prevention (IDS/IPS concepts)
* Network traffic inspection & anomaly detection
* Firewall log analysis (pfSense)
* VPN monitoring (OpenVPN)

---

### Cloud Security (AWS)

<p align="center">
  <img src="https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazonaws"/>
  <img src="https://img.shields.io/badge/AWS-VPC-orange?style=for-the-badge&logo=amazonaws"/>
  <img src="https://img.shields.io/badge/AWS-WAF-red?style=for-the-badge&logo=amazonaws"/>
  <img src="https://img.shields.io/badge/AWS-GuardDuty-yellow?style=for-the-badge&logo=amazonaws"/>
  <img src="https://img.shields.io/badge/AWS-CloudWatch-blue?style=for-the-badge&logo=amazoncloudwatch"/>
</p>

EC2 Deployment • VPC Architecture (Subnets, IGW, Route Tables)
Security Groups & NACLs • WAF (SQL Injection Protection)
GuardDuty Threat Detection • CloudWatch Monitoring & Alerts
Cloud Threat Detection & Response

---

### System Administration & Infrastructure ⭐

<p align="center">
  <img src="https://img.shields.io/badge/Linux-Ubuntu-black?style=for-the-badge&logo=ubuntu"/>
  <img src="https://img.shields.io/badge/Windows-Server-blue?style=for-the-badge&logo=windows"/>
  <img src="https://img.shields.io/badge/Active%20Directory-AD-purple?style=for-the-badge&logo=microsoft"/>
  <img src="https://img.shields.io/badge/DNS-Services-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Virtualization-VMware-gray?style=for-the-badge"/>
</p>

* Linux system administration (Ubuntu / CentOS)
* Windows Server administration
* Active Directory (users, groups, authentication basics)
* DNS configuration (records, name resolution)
* Remote access (RDP, SSH)
* VMware virtualization (VM deployment, cloning, networking)
* System hardening & access control

---

### Log Analysis & Visibility

* Linux: `/var/log/auth.log`
* Windows Event Logs: **4624, 4625, 4672**
* Firewall & VPN logs
* Authentication monitoring (SSH, RDP, VPN)
* Cross-source correlation (host + network + cloud)

---

### Networking & Security

Wireshark • pfSense • OpenVPN
Firewall Monitoring • VPN Analysis
Network Traffic Analysis • Packet Inspection

Concepts:

* Network Segmentation
* Traffic Flow Analysis
* Intrusion Indicators

---

### Offensive Simulation

Kali Linux • Hydra • Nmap

Brute Force Attacks • Password Spraying
Port Scanning & Reconnaissance
Adversary Simulation for Detection Testing

---

### Automation & Development

Bash Scripting • Cron Jobs
Detection Automation • Log Parsing

Development:
Node.js • Express • EJS

---

## Certifications

<p align="center">
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/CompTIA-CySA%2B-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ISC2-CC-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Microsoft-SC--200-purple?style=for-the-badge"/>
</p>

---

## Featured SOC Projects

### Enterprise Authentication Attack Detection (Splunk)

* Detects SSH, RDP, VPN brute force & password spray attacks
* Cross-platform correlation (Linux + Windows + Firewall)
* SOC-style dashboards and alert logic

👉 Demonstrates SOC-level detection engineering with multi-source correlation and attacker simulation

🔗 https://github.com/TejinderS1130/Enterprise-Authentication-Attack-Detection-Splunk

---

### Enterprise Cloud Security Lab (AWS + SOC Simulation)

* Built full cloud environment (EC2, VPC, subnets, routing)
* Simulated SQL Injection attack on DVWA
* Implemented WAF to block malicious requests (403 response)
* Detected threats using CloudWatch + GuardDuty

👉 Demonstrates **end-to-end SOC workflow: Attack → Detection → Response → Defense**

🔗 https://github.com/TejinderS1130/enterprise-cloud-security-lab

---

### SSH Brute Force Detection + Fail2Ban

* Simulated attacker behavior using Hydra
* Log-based detection and alerting
* Automated containment using Fail2Ban

👉 Shows detection + response automation

🔗 https://github.com/TejinderS1130/splunk-ssh-bruteforce-detection-fail2ban

---

### Sydney Travel Platform (Security-Aware Web App)

* Full-stack app with authentication and user tracking
* Designed with secure input handling
* Can integrate with logging/monitoring pipelines

👉 Demonstrates development + security awareness

🔗 https://github.com/TejinderS1130/sydney-travel-platform

---

## Current Focus

* Detection engineering (Splunk SPL & Sentinel KQL)
* Threat hunting across multi-source telemetry
* Cloud security detection (AWS)
* Building enterprise-level SOC labs
* Detection tuning & reducing false positives

---

## SOC Mindset

I approach problems from both attacker and defender perspectives:

* How would an attacker generate this activity?
* What logs would capture it?
* How can it be detected with minimal false positives?

👉 This mindset drives how I design detections, alerts, and investigations

---

## SOC Capabilities

✔ Log Analysis (Windows, Linux, Cloud telemetry)
✔ SIEM Monitoring (Splunk, Microsoft Sentinel)
✔ Detection Engineering (SPL & KQL queries, alert logic, tuning)
✔ Threat Hunting (multi-source telemetry analysis)

✔ Brute Force Detection (MITRE T1110)
✔ Password Spray Detection
✔ SQL Injection Detection (WAF + application layer)
✔ Reconnaissance Detection (Port scanning – GuardDuty)

✔ Incident Investigation & Triage
✔ Alert Validation & False Positive Reduction
✔ Event Correlation (Host + Network + Cloud logs)

✔ Endpoint Visibility (Microsoft Defender XDR)
✔ Network Security Monitoring (pfSense, VPN logs)
✔ Cloud Threat Detection (AWS GuardDuty, CloudWatch)

✔ Incident Response (basic containment & mitigation)
✔ Security Control Validation (WAF blocking, detection testing)
✔ SOC Workflow Execution (Detection → Investigation → Response)

---

## Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/tejinder-singh-4452923a6">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"/>
  </a>
</p>

---

## Mission

To contribute to security operations and threat detection by building systems that identify, analyze, and respond to real-world attacks across enterprise and cloud environments.

---

## Summary

This profile showcases hands-on SOC lab simulations, SIEM-based detection engineering, cloud security implementations (AWS), and strong system administration foundations across Linux, Windows, and network environments.

---
