# -Accuknox-Security-Officer-Trainee---itsecgames-security-assessment
Comprehensive vulnerability assessment of itsecgames.com including scans, screenshots, and detailed report
# Security Assessment – itsecgames.com

This repository contains the complete vulnerability assessment of [itsecgames.com](http://www.itsecgames.com/).

## Contents
- **/report/** – Final detailed PDF report with findings and CVE mapping.
- **/screenshots/** – Evidence of command outputs and tool results.
- **/demo/** – Google Drive link to the recorded demonstration.

## Tools Used
- Kali Linux Utilities  
- WHOIS, dig, whatweb  
- Nikto, Nmap, OpenSSL  
- Qualys SSL Labs Online Analyzer  

## Key Findings
- Multiple OpenSSH vulnerabilities (CVE-2023-38408, CVE-2016-1908, CVE-2015-5600, etc.)  
- Missing HTTP headers – `X-Frame-Options`, `X-Content-Type-Options`  
- Expired SSL certificate and missing HSTS  
- Information disclosure through Apache defaults and Drupal metadata  

## Demonstration Video
The walkthrough recording can be found here:  
[Google Drive Video Demonstration](PASTE_YOUR_LINK_HERE)

---

*Submitted as part of a vulnerability analysis and reporting practical assessment.*
