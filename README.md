# 🛡️ RedTeam Labs – Offensive Operations Portfolio
**A curated collection of offensive security exercises focused on initial access, lateral movement, privilege escalation, and full-chain attack simulations.**

## 🎯 Purpose  
This repository documents my hands‑on Red Team practice across multiple lab environments, capturing realistic attack paths, adversary tradecraft, and repeatable methodologies aligned with modern offensive security standards.

## 📁 Repository Structure  

````code
RedTeam-labs/
│
├── Initial-Access/
│   ├── phishing-simulation/
│   ├── web-initial-footholds/
│   └── misconfigurations/
│
├── Lateral-Movement/
│   ├── smb-relay/
│   ├── kerberos-attacks/
│   └── remote-execution/
│
├── Privilege-Escalation/
│   ├── windows/
│   └── linux/
│
├── Full-Chain-Attacks/
│   ├── lab-01/
│   ├── lab-02/
│   └── lab-03/
│
└── Tools-and-Scripts/
├── powershell/
├── bash/
└── python/
````

## 🧩 Methodology  
Each lab follows a consistent, professional structure:

1. **Scenario Overview**  
   Environment description, objectives, and threat model.

2. **Recon & Enumeration**  
   Network mapping, service discovery, OSINT, and internal recon.

3. **Initial Access**  
   Exploitation path, payloads, phishing, or misconfigurations.

4. **Privilege Escalation**  
   Local enumeration, kernel exploits, misconfigurations, token abuse, etc.

5. **Lateral Movement**  
   Credential harvesting, pivoting, Kerberos abuse, remote execution.

6. **Persistence & Evasion**  
   Techniques aligned with MITRE ATT&CK.

7. **Impact & Objectives**  
   Data access, domain compromise, or mission completion.

8. **Detection Opportunities**  
   Blue Team visibility and defensive notes.

9. **Remediation**  
   Hardening recommendations.

## 🧰 Tools & Techniques  
This repository includes practical use of:

- **C2 frameworks:** Sliver, Mythic, Havoc  
- **Credential attacks:** Mimikatz, Rubeus, Impacket  
- **Lateral movement:** PsExec, WinRM, WMI, SMB  
- **Privilege escalation:** WinPEAS, LinPEAS, custom scripts  
- **Payload development:** PowerShell, Python, Bash  
- **Enumeration:** BloodHound, SharpHound, CrackMapExec  

## 🧪 Featured Labs (coming soon)  
These will be the first fully documented labs:

- **Lab 01 — Initial Access via Web Exploitation**  
- **Lab 02 — Lateral Movement with Kerberoasting**  
- **Lab 03 — Full Domain Compromise via Misconfigured AD CS**  

## 📌 Notes  
This repository is continuously updated as I progress through new Red Team labs and simulations.  
All content is for **educational and ethical purposes only**.
