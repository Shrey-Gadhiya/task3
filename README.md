# task3
This repository documents a practical vulnerability assessment performed on a personal computer using Nessus Essentials. It showcases how to identify, analyze, and understand system vulnerabilities from a beginner's perspective.
 Basic Vulnerability Scan on Personal Computer
This repository documents a practical vulnerability assessment performed on a personal computer using Nessus Essentials. It showcases how to identify, analyze, and understand system vulnerabilities from a beginner's perspective.

🧑‍💻 Project Overview
Vulnerability scanning is a critical part of cybersecurity. It helps identify known weaknesses that could be exploited by attackers. In this project, a full vulnerability scan was run on the local system (localhost) using the free version of Nessus Essentials to discover potential threats and understand their severity.

🎯 Objective
To perform a basic vulnerability scan on a local machine
To identify and document critical vulnerabilities
To suggest basic remediations
To gain hands-on experience in vulnerability assessment
🛠️ Tools Used
Tool	Description
Nessus Essentials	Free vulnerability scanner by Tenable
Localhost / 127.0.0.1	The target system (this PC)
Browser	To access Nessus dashboard (https://santhohex:8834)
🧪 Project Steps
Installed Nessus Essentials and activated it using the free license key.
Configured a new scan targeting the local IP address (127.0.0.1).
Executed a basic network scan.
Waited ~45 minutes for scan completion.
Analyzed the vulnerability report and filtered high/critical issues.
Researched fixes for each vulnerability.
Documented the findings, solutions, and screenshots in a detailed report.
📋 Key Findings (Summary)
Vulnerability	Severity	CVE ID	CVSS Score	Fix
SMB Signing not required	High	CVE-2017-0143	8.1	Enforce SMB signing
Outdated Firefox Version	Medium	CVE-2023-5381	6.5	Update Firefox
SSL/TLS Weak Ciphers Supported	Medium	CVE-2016-2183	5.9	Disable weak SSL protocols
ICMP Timestamp Response	Info	-	-	Disable ICMP timestamp replies via firewall


📑 Files in this Repository
File	Description
README.md	Project documentation and interview Q&A
Vulnerability_Scan_Report.pdf	Full PDF report with screenshots, findings, and fixes
vulnerability-scan-interview-qa.txt	Full Interview Question
🎓 Learning Outcomes
Understood how vulnerability scanning works
Learned to interpret and prioritize scan results
Identified real-world system misconfigurations and outdated software
Prepared for common cybersecurity interview questions
❓ Interview Questions & Answers
1. What is vulnerability scanning?
Answer: It’s an automated process to detect known security weaknesses and misconfigurations in a system or network.

2. What is the difference between vulnerability scanning and penetration testing?
Aspect	Vulnerability Scanning	Penetration Testing
Purpose	Detect known issues	Simulate real attacks
Tools	Automated (e.g., Nessus)	Manual + Automated
Risk	Low risk	Higher risk
Depth	Broad but shallow	Deep and targeted
3. What are some common vulnerabilities in personal computers?
Outdated software or OS
Weak or default passwords
Open or unused ports
Unpatched applications
Disabled antivirus or firewall
4. How do vulnerability scanners detect vulnerabilities?
Answer: They compare system information (like software versions, services) against a database of known vulnerabilities (CVE) using fingerprinting and rule-based scans.

5. What is CVSS?
Answer: CVSS stands for Common Vulnerability Scoring System. It is a standardized method to score the severity of vulnerabilities on a scale from 0 (low) to 10 (critical).

6. How often should vulnerability scans be performed?
Answer: Regularly—ideally:

Monthly for personal systems
Weekly or after changes in enterprise environments
7. What is a false positive in vulnerability scanning?
Answer: It occurs when a scanner incorrectly reports a vulnerability that doesn't actually exist or isn't exploitable in that environment.

8. How do you prioritize vulnerabilities?
Answer:

Based on CVSS score (Critical, High, Medium)
Whether known exploits exist
Exposure level (external vs. internal)
Importance of the affected system
