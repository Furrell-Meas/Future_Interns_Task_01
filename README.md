# Web Application Vulnerability Assessment
## Author
**Furrell Meas**  
Cybersecurity Student | Aspiring Penetration Tester  

- Email: [furrelljordanmeas@gmail.com](mailto:furrelljordanmeas@gmail.com)  
- Phone: +27 60 695 9079

---
## Overview
This repository contains the results of a **web application vulnerability assessment** conducted on the intentionally vulnerable testing platform [demo.testfire.net](http://demo.testfire.net).  

The purpose of this assessment was to identify security weaknesses, evaluate their potential impact, and provide remediation recommendations to improve the overall security posture of the system.  

Findings have been compiled into a professional vulnerability assessment report, designed using **Canva**, included as a PDF in this repository. Supporting evidence, such as screenshots and tool outputs, are also included where applicable.

---

## Target Website

**Application Tested:** `demo.testfire.net`  

**Application Description:**  
Demo Testfire is an intentionally vulnerable online banking application commonly used for security education and penetration testing practice. The platform simulates real-world banking functionality and demonstrates common web application security weaknesses.  

Testing this environment allows security practitioners to practice identifying vulnerabilities and recommending appropriate security controls.

---

## Scope of Assessment

The assessment focused on **external web application security testing** of publicly accessible components.

- Passive analysis only
- No Active analysis/ No exploitation
- Use public demo website

---

## Tools Used

### OWASP ZAP
OWASP ZAP (Zed Attack Proxy) was used to perform automated vulnerability scanning and identify potential security misconfigurations. It helped detect:
- Missing security headers  
- Information disclosure  
- General web application vulnerabilities  

### Browser Developer Tools
Browser developer tools were used to manually inspect:
- HTTP response headers  
- Network requests  
- Resource loading behavior  
- Client-side scripts  
- Security header configurations  

Manual verification helped confirm findings from automated scans.

### Manual Security Analysis
Additional manual techniques were used to verify vulnerabilities and assess the overall security posture of the application.

---

## Vulnerability Summary

| Vulnerability | Severity |
|---------------|---------|
| No HTTPS Encryption | High |
| Content Security Policy (CSP) Header Missing | Medium |
| Subresource Integrity (SRI) Attribute Missing | Medium |
| Server Version Information Disclosure | Low |

While some findings are configuration weaknesses rather than direct exploits, they still weaken the overall security architecture and may increase the likelihood of successful attacks.

---

## Evidence
Supporting evidence for the findings is included in this repository and contains:
- Screenshots of observed vulnerabilities  
- Tool outputs from OWASP ZAP  
- Browser inspection results  

These artifacts document how each vulnerability was identified and validated during the assessment.

---

## Report
The complete vulnerability assessment report is included in this repository and contains:
- Executive summary  
- Attack summary  
- Detailed vulnerability descriptions  
- Proof-of-concept evidence  
- Risk severity ratings  
- Remediation recommendations  

The report is designed to be professional, client-ready, and suitable for presentation to stakeholders, security consultants, or technical teams.

---

## Disclaimer
This vulnerability assessment reflects the security posture of the application at the time of testing. Findings may not account for security changes made after the assessment was completed.


