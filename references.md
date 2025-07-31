# References

This document lists all frameworks, tools, CVEs, and real-world case studies referenced in the vulnerability assessment.

---

## Industry Frameworks & Standards

- **OWASP Top 10**  
  A list of the most critical web application security risks.  
  https://owasp.org/www-project-top-ten/

- **CIS Controls**  
  Prioritized and actionable recommendations to improve cybersecurity posture.  
  https://www.cisecurity.org/controls

- **NIST Cybersecurity Framework (CSF)**  
  Guidelines to manage and reduce cybersecurity risk across systems.  
  https://www.nist.gov/cyberframework

- **ISO/IEC 27001**  
  International standard for information security management systems.  
  https://www.iso.org/standard/27001

- **NIST SP 800-115**  
  Technical Guide to Information Security Testing and Assessment.  
  https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-115.pdf

- **SANS Windows Security Checklist**  
  Practical guide to hardening Windows environments and identifying security gaps.  
  https://www.sans.org/white-papers/windows-security-checklists

---

## Tools Used

- **Nmap (Network Mapper)**  
  Open-source tool for network discovery and security auditing.  
  https://nmap.org/book/

- **Nmap NSE (Script Engine)**  
  Custom scripts for deeper vulnerability detection (e.g., SMB, RPC analysis).  
  https://nmap.org/nsedoc/

- **Lynis**  
  Auditing tool for Linux/Unix systems for hardening and compliance.  
  https://cisofy.com/lynis/

- **Nikto**  
  Web server scanner for detecting outdated software and common misconfigurations.  
  https://cirt.net/Nikto2

---

## Vulnerabilities Referenced (CVEs)

- **EternalBlue (MS17-010, SMBv1)**  
  Remote Code Execution via SMBv1 used in WannaCry.  
  CVE-2017-0144  
  https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-0144

- **PrintNightmare (Windows Print Spooler RCE)**  
  Exploits printer sharing services to gain elevated privileges.  
  CVE-2021-34527  
  https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-34527

---

## Real-World Case Studies

- **WannaCry Ransomware (2017)**  
  Worldwide ransomware attack that used SMB vulnerabilities (EternalBlue).  
  https://en.wikipedia.org/wiki/WannaCry_ransomware_attack

- **NotPetya Malware (2017)**  
  Malware leveraging SMB vulnerabilities for lateral movement and data destruction.  
  https://www.csoonline.com/article/3309704/what-is-notpetya-the-ransomware-that-wasnt.html

---

## Additional Reading

- **Understanding SMB Security**  
  https://learn.microsoft.com/en-us/windows-server/storage/file-server/smb-security-overview

- **Understanding RPC and DCOM Security**  
  https://learn.microsoft.com/en-us/windows/win32/secauthn/security-considerations-for-rpc

---

