# 🛡️ Tanner — Cybersecurity Portfolio

Cybersecurity student focused on **incident response**, **vulnerability assessment**, **digital forensics**, and **practical security testing using industry-standard tools**.  
This repository serves as the technical backbone to my portfolio website, showcasing real projects, lab work, and supporting evidence.

🌐 **Portfolio Website:** https://tannercyber.github.io  
🔗 **LinkedIn:** https://www.linkedin.com/in/tanner-mitchell/  
🐙 **GitHub:** https://github.com/TannerCyber  

---

## 📌 About This Portfolio

This portfolio documents my progression through hands-on cybersecurity coursework, labs, and independent projects, with a focus on:

- Incident response and SOC-style investigations
- Vulnerability assessment and risk analysis using CVE and CVSS concepts
- Digital forensics and file system artifact analysis
- Network and wireless security testing
- Cloud and identity-based security using Microsoft Azure
- Home lab security deployments and operational automation

All public material is **sanitized** to avoid exposing sensitive data while still demonstrating technical methodology, analytical thinking, and decision-making.

---

## 🧠 Core Skills & Focus Areas

- **Incident Response & Investigation**
  - Alert triage and log analysis using SIEM-style workflows
  - Endpoint and host-based investigation with EDR concepts
  - IOC identification from logs and network traffic
  - Documentation of findings and response recommendations

- **Vulnerability Assessment & Risk Analysis**
  - Network and service enumeration
  - Identification of misconfigurations and exposed services
  - Risk assessment using CVE and CVSS scoring concepts
  - Translating technical findings into security impact

- **Digital Forensics**
  - File system analysis of FAT and NTFS volumes
  - Parsing file system structures and metadata at the artifact level
  - NTFS analysis including $MFT records and attribute parsing (e.g., filename, standard information)
  - Timeline reconstruction and evidence interpretation from disk images

- **Network & Wireless Security**
  - Traffic analysis and protocol inspection
  - WPA2 security testing and credential attack methodologies (lab-based)
  - DNS behavior analysis and anomaly detection

- **Cloud & Infrastructure Fundamentals**
  - Hands-on deployment of Azure resources within personal subscriptions
  - Configuration of cloud services, networking, and access controls
  - Use of cloud-native management tools and command-line workflows
  - Implementation of backup and disaster recovery concepts, including replication and recovery planning
  - Understanding of cloud security considerations and the shared responsibility model

- **Security Automation & Tooling**
  - Basic shell scripting for repeatable system and security-related tasks
  - Automation of routine maintenance for Pi-hole environments
  - Use of Azure Cloud Shell for managing and deploying cloud resources
  - Introductory experience with Infrastructure as Code (IaC) concepts using Terraform
  - Familiarity with how automation supports scalability, reliability, and security operations

---

## 🛠️ Tools & Technologies

**Security Operations & Logs**
- Windows Event Viewer
- Microsoft Defender
- SIEM lab workflows
- JSON log analysis

**Network & Traffic**
- Wireshark
- Nmap
- tcpdump
- Zeek
- RITA
- DNS analysis

**Offensive Security Labs**
- Kali Linux
- Metasploit
- msfconsole
- msfvenom
- Aircrack-ng suite
- Hashcat
- SSH tunneling

**Digital Forensics**
- FTK Imager
- Magnet AXIOM
- PALADIN
- HxD
- Autopsy
- Registry Explorer
- NTFS / FAT analysis
- Hash identification
- Evidence hash verification

**Cloud & Identity**
- Microsoft Azure
- Azure AD / Entra ID
- Azure networking
- Network Security Groups
- Backup and disaster recovery concepts

**Systems & Virtualization**
- Windows Server
- Active Directory
- Linux
- Pi-hole
- VMware Workstation
- Docker
- Raspberry Pi

**Scripting & Development**
- Python
- Bash
- PowerShell
- Git / GitHub
- VS Code
- HTML / CSS

---

## 📂 Featured Projects

### 🔹 Pi-hole Home DNS Deployment
**Goal:** Reduce ad/tracker traffic while maintaining reliability across a production home network.

**Highlights:**
- Deployed Pi-hole as primary DNS resolver
- Tuned blocklists to avoid overblocking
- Monitored DNS logs to identify noisy or misconfigured clients
- Automated maintenance tasks (updates, gravity refresh, cache cleanup)

➡️ **Full writeup & screenshots:**  
https://tannercyber.github.io/projects.html

---

### 🔹 Incident Response Log Analysis & IOC Extraction
**Goal:** Extract actionable indicators of compromise from structured log data.

**Highlights:**
- Parsed JSON-based security logs
- Identified suspicious IPs, domains, files, processes, and ports
- Focused on analyst-ready output (not raw data dumps)
- Documented findings and recommended response actions

➡️ **Detailed analysis:**  
https://tannercyber.github.io/projects.html

---

### 🔹 Multi-Hop SSH Tunneling Across Segmented VMware Networks
**Goal:** Design and validate a chained SSH port-forwarding environment across multiple isolated network segments.

**Highlights:**
- Built a segmented VMware lab using Kali Linux and six dual-homed Alpine Linux systems
- Created an Apache-hosted credential-discovery scenario
- Recovered six intentionally generated lab credentials using Hashcat hybrid attacks
- Constructed five progressive SSH local port forwards across isolated networks
- Verified successful end-to-end access to the final Alpine system
- Documented troubleshooting, security risks, and defensive takeaways

➡️ **Full writeup & sanitized evidence:**  
https://tannercyber.github.io/projects.html

---

## 🧪 Labs & Hands-On Practice

**Blue Team / SOC**
- TryHackMe SOC-focused labs
- Windows event log analysis
- Alert triage and abnormal behavior identification

**Network Analysis**
- Wireshark PCAP analysis
- Protocol inspection (TCP, UDP, DNS, HTTP/S)
- Traffic baselining

**Digital Forensics**
- NTFS & FAT artifact analysis
- $MFT record parsing
- Timeline reconstruction

**Ranges & CTFs**
- XP Cyber Range (NIST-aligned scenarios)
- National Cyber League (NCL)
- MetaCTF

➡️ **Lab breakdown & evidence:**  
https://tannercyber.github.io/labs.html

---

## 🎓 Certifications & Relevant Coursework

**Certifications**
- CompTIA IT Fundamentals (ITF+)
- Microsoft Azure Fundamentals (AZ-900)

**Relevant College Coursework & Hands-On Training**
- Ethical Hacking coursework involving enumeration, exploitation workflows, Metasploit, tunneling, and payload generation
- Cybersecurity Analyst coursework aligned with CySA+ concepts, including blue-team operations, alert triage, log analysis, and incident response
- Digital Forensics Analysis coursework involving disk imaging, file system analysis, artifact review, and forensic documentation
- Server Administration coursework covering Windows Server, Active Directory, system administration, and infrastructure fundamentals
- Linux Administration coursework covering command-line usage, users, permissions, services, and system management
- Cloud Essentials coursework covering cloud service models, Azure fundamentals, networking, identity, and security concepts
- SQL Database Concepts coursework covering database design, SQL queries, joins, and relational database fundamentals
- CTF and cyber range participation including NCL, MetaCTF, XP Cyber Range, and TryHackMe labs

---

## 📫 Contact

- **Email:** mitchelltanner23@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/tanner-mitchell/  
- **Portfolio:** https://tannercyber.github.io  

---

> This repository and portfolio are actively maintained as I complete new labs, projects, and coursework.