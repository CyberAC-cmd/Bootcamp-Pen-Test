# Full-Stack Penetration Test: Simulated Corporate Infrastructure

## 🕵️ Executive Summary
This project is a comprehensive, three-day penetration testing engagement conducted against a simulated corporate network. The assessment followed the **PTES (Penetration Testing Execution Standard)** to identify, exploit, and document 23 security vulnerabilities across web applications, Linux servers, and Windows environments.

## 🏆 Key Achievements
* **23 Unique Vulnerabilities** identified, ranging from Critical Remote Code Execution (RCE) to OSINT leaks.
* **Full Domain Compromise** achieved on Windows Server 2019 via credential harvesting.
* **Advanced Bypass Techniques** demonstrated against non-recursive input filters for XSS and Command Injection.

## 📂 Technical Deliverable
A detailed breakdown of every exploit, including bypass logic, step-by-step methodologies, and all 23 flags with screenshots, is available in the formal report:

### 👉 [View Full Technical Report (PDF)](./Final_Report/Penetration_Test_Report.pdf)

## 🛠️ Technical Stack
* **Attacker OS:** Kali Linux
* **Target OS:** Ubuntu, Windows 10, Windows Server 2019
* **Tools:** Burp Suite, Nmap, Metasploit, Nessus, Mimikatz (Kiwi), John the Ripper

## 🕵️ Phase-by-Phase Overview

### Day 1: Web Application
Focused on the OWASP Top 10. Highlights include bypassing input validation to achieve XSS and Command Injection.
<img width="622" height="296" alt="Day1 Cmd" src="https://github.com/user-attachments/assets/0348a346-b354-48ca-8556-5305a9fab593" />
<img width="669" height="269" alt="Day1 XSS" src="https://github.com/user-attachments/assets/485ef231-3e78-4428-ab9e-6c3f1f61341c" />


### Day 2: Linux Infrastructure
Focused on remote service exploitation and privilege escalation. Exploited Shellshock and Drupal RCE to gain root-level access.


### Day 3: Windows & Active Directory
Focused on OSINT and credential harvesting. Concluded with extracting the Administrator NTLM password hash from a Server 2019 machine.
* **[Insert Screenshot 3 - Credential Dump]**
---
*Disclaimer: This engagement was performed in a controlled educational lab environment with explicit authorization for testing.*
