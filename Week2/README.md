# Week 2 – Vulnerability Assessment and Penetration Testing (VAPT)

## 📄 Overview
This week focuses on practical exploitation, vulnerability scanning, and the complete VAPT cycle using Metasploitable2 and Kali Linux.

## 🧠 Theoretical Knowledge
- **Vulnerability Scanning:** Understanding Nmap, OpenVAS, Nikto, and CVSS scoring.
- **Penetration Testing Phases:** Recon, Scanning, Exploitation, Post-Exploitation, Reporting.
- **Exploit Development:** Basics of buffer overflow, SQLi, and XSS using Exploit-DB references.

## 🧪 Practical Work Done
1. **Vulnerability Scanning**
   - Scanned Metasploitable2 with Nmap and OpenVAS.
   - Identified high-severity vulnerabilities using CVSS scoring.

2. **Exploitation**
   - Gained reverse shell using `nc` and verified root access.
   - Exploited Tomcat manager service via Metasploit.

3. **Post-Exploitation**
   - Verified system details and privilege level.
   - Collected basic forensic evidence (file hash, system info).

## 📸 Screenshots
- Add screenshots of:
  - Nmap scan results
  - OpenVAS dashboard
  - Exploit success in Metasploit
  - Root access (bind shell output)

## 🧾 Reports
- `VAPT_Week2_Report.pdf` 
- `Bindshell_output.txt` 
- `scans/nmap_full_tcp_192-168-1-100.txt`
- `scans/nmap_service_192-168-1-100.txt`
- `scans/nikto_192-168-0-139.txt`
- `scans/gobuster_192-168-0-139.txt`
- `web/phpinfo.html`
- `web/phpmyadmin_index.html`
- `exploits/msf_tomcat_mgr_login_output.txt (copy msf output)`
- `exploits/tomcat_upload_output.txt (exploit upload output)`
- `exploits/bindshell_1524_output.txt`
- `evidence/evidence_192-168-0-139.tar.gz`
- `evidence/evidence_hash.txt (contains the sha256 above)`
- `screenshots` 


## 🧩 Deliverables
- [x] Nmap + OpenVAS scan reports  
- [x] Exploitation proof (shell access)  
- [x] Documentation + Key Learnings PDF  
- [x] README summary  
