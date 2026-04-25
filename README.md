FUTURE_CS_01 Vulnerability Assessment Report

Network and web application security assessment of a demo banking site to identify vulnerabilities and security weaknesses.
Tools Used

- Nmap: Network port scanning and service detection
- OWASP ZAP: Web application vulnerability scanner
- Browser DevTools: Manual inspection and testing
- Microsoft Word: Documentation and reporting

Target Tested
- Target: Altoro Mutual Demo Site (demo.testfire.net)
- Type: Public demo banking application
- Scope: Read-only vulnerability assessment (no exploitation)

Analysis Approach
Performed network reconnaissance using Nmap to identify open ports and services, then conducted web application scanning with OWASP ZAP to detect vulnerabilities. Manual testing verified findings. Risk classified as High/Medium/Low based on severity and exploitability.

Vulnerabilities Found

- SQL Injection (High Risk)
- Cross-Site Scripting - XSS (High Risk)
- Missing security headers (Medium Risk)
- Information disclosure (Medium Risk)
- Insecure authentication (Medium Risk)
- Outdated software versions (Low Risk)

Results
- Full report: Task1_Vulnerability_Report.docx
- Nmap scan evidence screenshots
- OWASP ZAP findings screenshots
