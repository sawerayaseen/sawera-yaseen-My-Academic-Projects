


## 🛡️ ZAP Web Application Security Testing

## 📖 Overview
OWASP ZAP is an open-source web application security scanner. In this project, we configured ZAP to scan a test website (like DVWA or Juice Shop) to identify potential security flaws such as:

SQL Injection

XSS (Cross Site Scripting)

Broken Authentication

Insecure HTTP Headers

Directory Browsing
## ✨ Features
🧪 Automated vulnerability scanning

🔍 Manual exploration with ZAP browser

📊 Scan report generation (HTML format)

🛠️ Custom scripts for authentication and crawling

📁 Full logging of alerts and attack vectors


## 🧰 Tools & Technologies
OWASP ZAP

DVWA / Juice Shop (target app)

Burp Suite (optional for comparison)

Browser Plug-in (ZAP proxy settings)

Linux / Windows environment
## 🧠 Methodology
Setup ZAP and Proxy Configuration

Import Target URL

Spider the Application

Active Scan

Analyze Alerts and Vulnerabilities

Export HTML Report
## 📊 Results
Some of the high/medium/low vulnerabilities found:
| Severity | Vulnerability             | Description                   |
| -------- | ------------------------- | ----------------------------- |
| High     | SQL Injection             | Input fields vulnerable       |
| Medium   | XSS                       | JavaScript injection possible |
| Low      | Server Leaks Version Info | Information Disclosure        |


## 🔮 Future Work
Integrate ZAP with CI/CD pipeline for automated security testing

Compare ZAP results with Burp Suite or Nikto

Add authentication script for restricted areas


## 📄 License
This project is for educational use only. No actual websites were harmed during testing. Tools used are open-source under their respective licenses.

https://drive.google.com/drive/folders/1rFJTB-GCERBjVscerWREZU2kCrvXL4SS?usp=sharing