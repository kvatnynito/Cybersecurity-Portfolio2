## Connect with Me

- LinkedIn: [Kevin Nito](https://www.linkedin.com/in/kevin-nito)
- GitHub: [github.com/kvatnynito](https://github.com/kvatnynito)

# 🛡️ Security Engineering Portfolio

My hands-on projects demonstrating **Microsoft Sentinel**, **detection engineering**, **incident response**, **threat hunting**, and **automation**. This is the hub that links all repos in my blue-team stack.

---

## 🎯 Core Skills Demonstrated
- Detection Engineering (KQL, Sigma, Windows/Linux/Sysmon signals)
- SIEM Operations in Microsoft Sentinel
- Incident Triage & Investigation (MITRE ATT&CK aligned)
- Threat Hunting Workflows
- Log Ingestion & Normalization (Sysmon, Windows Event Logs, Linux auth, DNS)
- Automation & Enrichment (PowerShell/Python, SOAR/Logic Apps)
- Lab Architecture (pfSense, VLANs, Proxmox/VMware/Hyper-V, Azure)

---

## 📂 Project Index (6 Repos)

### **Repo 1 – Security Operations & Detection Engineering** - Job Role Matchs: SOC Analyst, Detection Engineer
**Focus:** SIEM, Detection Rules, Incident Response  
This project showcases hands-on SecOps skills using Microsoft Sentinel. It includes detection rules, incident investigations, log samples, and automation scripts used to identify and respond to suspicious activity in a simulated enterprise environment.  
🔗 Repo: [https://github.com/kvatnynito/1-secops-detections-sentinel](https://github.com/kvatnynito/P2-1-secops-detections-sentinel)

### **Repo 2 – Vulnerability Management** - Job Role Matches: Vulnerability Analyst, Security Engineer
**Focus:** Nmap, OpenVAS/GVM, Risk Analysis  
This project demonstrates hands-on vulnerability management using Nmap and OpenVAS/GVM. Includes scan outputs, analysis reports, risk matrices, and remediation planning based on real test environments.  
🔗 Repo: [https://github.com/kvatnynito/2-vuln-mgmt-openvas-lab](https://github.com/kvatnynito/P2-2-vuln-mgmt-openvas-lab)

### **Repo 3 – Endpoint Hardening (Windows & Linux)** - Job Role Matches: Endpoint Security, SysAdmin Security
**Focus:** System Hardening, Baselines, Validation  
This project shows practical endpoint hardening for both Windows and Linux systems. Includes baselines, configuration changes, validation steps, and evidence showing how systems were strengthened against common attack vectors.  
🔗 Repo: [https://github.com/kvatnynito/3-endpoint-hardening-windows-linux](https://github.com/kvatnynito/P2-3-endpoint-hardening-windows-linux)

### **Repo 4 – Cloud Security (Azure)** - Job Role Matches: Cloud Security Analyst/Engineer
**Focus:** Azure IAM, Security Reviews, Sentinel  
This project demonstrates hands-on cloud security inside Microsoft Azure. It includes Azure security reviews, Sentinel analyses, IAM evaluations, architecture mapping, and evidence from a real mini-lab built on Azure free-tier resources.  
🔗 Repo: [https://github.com/kvatnynito/4-azure-security-mini-lab](https://github.com/kvatnynito/P2-4-azure-security-mini-lab)

### **Repo 5 – Governance, Risk & Compliance (GRC)** - Job Role Matches: GRC Analyst, Compliance, Security Governance
**Focus:** NIST, ISO, PCI, Risk Management  
This project demonstrates core GRC skills including security policies, risk matrices, governance documentation, and mapping to frameworks such as NIST CSF, NIST 800-53, ISO27001, and PCI-DSS.  
🔗 Repo: [https://github.com/kvatnynito/5-grc-policies-and-risk](https://github.com/kvatnynito/P2-5-grc-policies-and-risk)

### **Repo 6 – Cybersecurity Automation & Scripting** - Job Role Matches: SecOps Automation, SOAR, IR Automation
**Focus:** PowerShell, Python, Bash, Automation Tools  
This project showcases cybersecurity automation across multiple scripting languages. It includes tools for log parsing, alert generation, evidence collection, and security task automation used in real SecOps, SOC, and IR workflows.  
🔗 Repo: [https://github.com/kvatnynito/6-sec-automation-py-ps-bash](https://github.com/kvatnynito/P2-6-sec-automation-py-ps-bash)


---

## 🧪 Lab Topology (Quick View)
- **Hosts:** Proxmox/VMware/Hyper-V/Docker
- **VMs:** Windows Server 2019, Ubuntu 22.04, Kali
- **Network:** pfSense with two VLANs (Home / Lab)
- **Cloud:** Azure (Sentinel, Log Analytics, Defender for Cloud, Entra ID)

> Diagram lives in: `repo-5/docs/architecture/` (linked above)

---

## 🚨 What’s Implemented
- ✅ Detection rules (KQL) — mapped to MITRE ATT&CK  
- ✅ Incident reports — triage, queries, findings  
- ✅ Sample logs — Windows/Sysmon/Linux for reproducible tests  
- ✅ Sentinel configuration — Analytics, Data Connectors, Incidents  
- ✅ Automation — enrichment scripts & SOAR (work-in-progress)

---

## ▶️ How to Explore
To get the most out of this portfolio, follow the recommended path below:

### **1. Start with Repo 1 — Security Operations & Detection Engineering**
Explore how detection rules, KQL analytics, Sentinel incidents, and Sysmon logs work together.  
🔗 https://github.com/kvatnynito/P2-1-secops-detections-sentinel

### **2. Review Repo 2 — Vulnerability Management**
See how vulnerabilities are discovered, analyzed, scored, and mapped to remediation strategies using Nmap and OpenVAS/GVM.  
🔗 https://github.com/kvatnynito/P2-2-vuln-mgmt-openvas-lab

### **3. Move to Repo 3 — Endpoint Hardening**
Check out Windows and Linux hardening baselines, validation evidence, and configuration changes that strengthen endpoints against common attacks.  
🔗 https://github.com/kvatnynito/P2-3-endpoint-hardening-windows-linux

### **4. Explore Repo 4 — Azure Cloud Security**
Understand how Azure IAM, Sentinel, and cloud architecture reviews work in a real mini-lab environment built on the Azure free tier.  
🔗 https://github.com/kvatnynito/P2-4-azure-security-mini-lab

### **5. Review Repo 5 — GRC Policies & Risk**
See formal governance documents, risk matrices, policies, and framework mapping aligned with NIST, ISO, and PCI.  
🔗 https://github.com/kvatnynito/P2-5-grc-policies-and-risk

### **6. Finish with Repo 6 — Cybersecurity Automation & Scripting**
Explore Python, PowerShell, and Bash tools built to automate log analysis, evidence collection, and SecOps workflows.  
🔗 https://github.com/kvatnynito/P2-6-sec-automation-py-ps-bash

---

## 📈 Roadmap (Next Up)
- +10 detections (brute force, persistence, malware, lateral movement)
- Logic Apps (SOAR) auto-response flows
- Enrichment with VirusTotal/AbuseIPDB integrations
- Add Apache & DNS logs; build a hunting workbook
- Publish a small “Playbook Pack” PDF in `docs/`

---

## 🧠 Selected Learnings
- Writing reliable **KQL** detections and tuning false positives
- Joining log sources (Windows/Sysmon/Linux) for better signal
- Mapping detections to **MITRE ATT&CK** tactics/techniques
- Sentinel Incident flow: Analytics → Alerts → Incidents → Investigation
- Repeatable lab patterns using pfSense + VLANs + Azure

---

## 📬 Contact
- GitHub: https://github.com/kvatnynito 
- LinkedIn/Portfolio/Email: 

---

## ⚖️ License
MIT — see `LICENSE`.
