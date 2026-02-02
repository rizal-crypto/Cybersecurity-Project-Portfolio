# Cybersecurity-Project-Portfolio
Cybersecurity project portfolio showcasing hands-on experience with CTF design, SIEM &amp; IDS/IPS deployment, network vulnerability analysis, and honeypot labs, backed by full technical documentation.
# Cybersecurity Project Portfolio

👋 Hi, I’m Mohamed Rizal Kapat — an MSc Cybersecurity graduate with hands-on experience in offensive and defensive security labs.  
This repository showcases practical cybersecurity projects focused on real-world attack detection, monitoring, and analysis, backed by full technical documentation.

---

## 🔐 Projects Overview

This portfolio includes three major hands-on cybersecurity projects:

- Capture The Flag (CTF) Virtual Machine
- Network Vulnerability Analysis & SIEM (DMZ Lab)
- Honeypot Lab for Attacker Behaviour Analysis

Each project demonstrates applied security concepts, tools, and methodologies used in real SOC and security analyst environments.

---

## 🧩 1. Capture The Flag (CTF) Virtual Machine

**Platform:** Ubuntu Server 18.04  

### Project Summary
Designed and implemented an educational Capture The Flag (CTF) virtual machine aimed at beginners in cybersecurity. The environment simulates real-world attack scenarios using common services, misconfigurations, and progressive challenges.

### Tools & Technologies
- FTP, SSH, Apache, HTTP/HTTPS
- Linux user & permission management
- Steganography (image and audio)
- Hashing (Whirlpool)
- Brute-force tools: Hydra, John the Ripper, Hashcat

### What Was Implemented
- Multiple exposed network services to simulate an attack surface
- Multiple Linux users with restricted directory access
- Progressive flags distributed across services and file systems
- Web-based information disclosure via HTML source inspection
- Steganography-based hidden flags
- Hash cracking and brute-force challenges

### Skills Demonstrated
- Service enumeration
- Linux privilege separation
- Web reconnaissance
- Steganography techniques
- Hash analysis and password cracking

📄 **Full Technical Report:**  
`projects/ctf/CTF_Report.pdf`

---

## 🌐 2. Network Vulnerability Analysis & SIEM (DMZ Lab)

### Project Summary
Performed a vulnerability assessment on a DMZ-hosted server in a simulated enterprise environment. Implemented centralized logging and intrusion detection to monitor, detect, and analyze malicious activity.

### Tools & Technologies
- ELK Stack (Elasticsearch, Logstash, Kibana, Filebeat)
- Suricata IDS/IPS
- UFW Firewall
- OWASP Juice Shop
- Kali Linux

### What Was Implemented
- Multi-VM DMZ architecture
- Centralized log collection and visualization using ELK Stack
- IDS/IPS alerting using Suricata
- Firewall rule enforcement and traffic control
- Simulated attacks including SQL injection and authentication flaws

### Key Findings
- Identified critical vulnerabilities such as SQL injection and broken authentication
- Verified real-time attack detection and logging
- Conducted risk assessment and proposed mitigation strategies

### Skills Demonstrated
- SIEM deployment and log analysis
- IDS/IPS monitoring
- Network security architecture
- Vulnerability assessment and risk analysis

📄 **Full Technical Report:**  
`projects/siem-dmz/Network_Vulnerability_Report.pdf`

---

## 🪤 3. Honeypot Lab – Attacker Behaviour Analysis

### Project Summary
Designed and deployed a secure honeypot lab to capture attacker interactions and analyze malware distribution techniques while maintaining strict isolation from production systems.

### Tools & Technologies
- Windows 10 Honeypot VM
- pfSense Firewall (WAN / LAN / DMZ)
- ELK Stack
- Maltego Casefile
- WinPcap

### What Was Implemented
- Deployment of an exposed honeypot system
- Firewall-based network isolation using pfSense
- Capture of attacker interactions and packet-level traffic
- Centralized log aggregation and analysis
- Analysis of attacker tactics, techniques, and procedures (TTPs)

### Skills Demonstrated
- Honeypot deployment and management
- Firewall and gateway security
- Network traffic capture and forensic analysis
- Threat intelligence collection

📄 **Full Technical Report:**  
`projects/honeypot/Honeypot_Report.pdf`

---

## 🎯 Career Focus

I am actively seeking entry-level or junior roles such as:
- SOC Analyst
- Cybersecurity Analyst
- Network Security Engineer

---

## 📎 Supporting Documentation

Each project is backed by a comprehensive technical report containing:
- Configuration steps
- Commands used
- Verification outputs
- Logs and analysis

These documents provide formal evidence of hands-on cybersecurity experience.

---

*This portfolio is continuously updated as skills and projects evolve.*
