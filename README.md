# Web-Application-Penetration-Testing-XSS
**Vulnerability Assessment**
**(Authorized Live Website Testing)**

**Project Overview**
This project documents an authorized security assessment performed on a live web application to identify and validate Cross-Site Scripting (XSS) vulnerabilities.
The objective was to help the website owner understand security risks and improve application security by following OWASP Top 10 guidelines

**Scope of Testing**
The following XSS attack vectors were tested:
Reflected XSS
DOM-Based XSS
Input validation and output encoding issues
Client-side script injection points
All testing was conducted only after receiving explicit permission from the website owner.

**Tools & Techniques Used**
Manual payload injection
Browser developer tools
Burp Suite
URL parameter manipulation
JavaScript context testing

**Methodology**
The testing followed a structured approach:
Identified input fields, URL parameters, and DOM sinks
Injected safe XSS payloads to test reflection and execution
Verified vulnerability by observing JavaScript execution
Assessed impact (cookie access, DOM manipulation, session risk)
Documented findings with proof-of-concept screenshots
Provided remediation guidance

**Findings Summary**
The application was found vulnerable to:
**Stored XSS**
**Reflected XSS**
**DOM-Based XSS**
These vulnerabilities could allow attackers to:
Execute malicious JavaScript
Steal session cookies
Perform phishing attacks
Modify page content

**Reporting**
A professional vulnerability report was prepared containing:
Vulnerability description
Affected URLs / parameters
Proof-of-Concept (PoC)
Risk severity
Impact analysis
Remediation recommendations
The report was shared responsibly with the website owner.

**Ethical Disclosure**
This project was conducted under responsible disclosure principles.
No data was damaged, altered, or misused.
The goal was strictly to improve application security.

**Skills Demonstrated**
Web Application Penetration Testing
OWASP Top 10
XSS (Reflected & DOM)
Vulnerability Reporting
Ethical Hacking
Responsible Disclosure
