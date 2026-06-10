# 🏗️ Projects & The Capstone

Building projects proves you can apply what you've learned. Put these on your GitHub profile and your resume!

---

## 🛠️ Mini-Projects (Months 1-5)

### 1. The Python Port Scanner
*   **Goal:** Write a Python script that takes an IP address and scans a range of ports (e.g., 1-1024) to see which ones are open.
*   **Skills learned:** Python networking (sockets), loops, exception handling.

### 2. Bash Automation Script
*   **Goal:** Write a Bash script for your Linux VM that automatically updates the system, clears the package cache, and outputs a log file of the update time.
*   **Skills learned:** Linux administration, Bash syntax, cron jobs.

### 3. Keylogger (In Lab Only!)
*   **Goal:** Write a basic Python script that records keystrokes and saves them to a local file. 
*   **Warning:** ONLY run this on your own virtual machine. Never deploy this on systems you don't own.
*   **Skills learned:** Python libraries, understanding malware behavior.

### 4. Simple Web App Vulnerability Report
*   **Goal:** Deploy **OWASP Juice Shop** (a deliberately insecure web app) locally. Find 3 vulnerabilities, take screenshots, and write a 2-page report explaining the vulnerabilities and how to fix them.
*   **Skills learned:** Web testing, technical writing, remediation.

---

## 🏆 Final Capstone Project: Full Penetration Testing Report

In Month 6, you will act as a professional Penetration Tester. You will compromise a vulnerable machine and write a professional-grade report.

### The Target
Choose a beginner/intermediate machine on TryHackMe (e.g., "Internal" or "Wreath" network) or Hack The Box.

### Requirements for your Report

Your final report must be formatted professionally (like a PDF you would hand to a client) and include:

1.  **Executive Summary:** A non-technical summary of your findings and the overall risk level for business leaders.
2.  **Scope:** What IP addresses/domains were tested.
3.  **Methodology:** A brief mention of the steps taken (Recon, Scanning, Exploitation).
4.  **Detailed Findings (The core of the report):**
    *   **Vulnerability Name** (e.g., Unauthenticated SQL Injection)
    *   **Severity** (Critical, High, Medium, Low)
    *   **Description:** What is the flaw?
    *   **Proof of Concept (PoC):** Step-by-step instructions on how you exploited it. *Must include screenshots!*
    *   **Impact:** What can a bad guy do with this? (e.g., Steal the database).
    *   **Remediation:** How does the developer fix this? (e.g., Use parameterized queries).
5.  **Appendices:** Nmap scan outputs, scripts used.

### Why this matters
Hacking is only 50% of the job. The other 50% is writing reports. Employers will hire a decent hacker who writes amazing reports over an amazing hacker who writes terrible reports. Having a sample report on your GitHub/Resume sets you apart from 90% of beginners.
