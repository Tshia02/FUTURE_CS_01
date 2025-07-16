# FUTURE_CS_01 – Web Application Security Testing

This repository contains the completed submission for **Cyber Security Task 1** as part of the Future Interns internship program.

## Task Overview

The objective of this task was to perform a basic web application security assessment using ethical hacking tools and OWASP Top 10 standards. The project simulates real-world security testing scenarios on intentionally vulnerable applications.

### Key Activities:
- Set up and explored **OWASP Juice Shop**, a vulnerable test application
- Used **OWASP ZAP** to scan for vulnerabilities
- Identified and documented **Sensitive File Disclosure** vulnerabilities
- Mapped vulnerabilities to the **OWASP Top 10** categories
- Created a detailed **Security Assessment Report** with impact analysis and remediation steps

## Tools Used
- **OWASP Juice Shop** (Target Application)
- **OWASP ZAP** (Scanning Tool)
- **Java JDK 24** (Required for ZAP)
- **Microsoft Word** for report writing

## Files in This Repository
- `Security_Report.pdf` – Full report with methodology, screenshots, findings, and conclusion
- `README.md` – This file

## Vulnerabilities Identified
- Sensitive File Disclosure – `._darcs`
- Sensitive File Disclosure – `.bzr`
- Sensitive File Disclosure – `.hg`
- Sensitive File Disclosure – `BitKeeper`

Each vulnerability includes a description, impact level, OWASP mapping, remediation, and screenshots.

## Learning Outcomes
- Gained practical experience with web vulnerability scanning tools
- Understood common misconfigurations in web applications
- Improved skills in security documentation and reporting


