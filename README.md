# OWASP Juice Shop - Vulnerability Assessment Report

This repository contains a detailed Vulnerability Assessment Report for the OWASP Juice Shop application. This assessment was conducted by Group CAI2_ISS3_G1 as part of a Cybersecurity Internship program with **DEPI**. The project was completed under the supervision of instructor Ahmed Hisham.

## Target Application

**OWASP Juice Shop**

OWASP Juice Shop is a deliberately insecure web application designed for security training, awareness demonstrations, and testing of security tools. It encompasses vulnerabilities from the entire OWASP Top Ten and other security flaws found in real-world applications.

[https://owasp.org/www-project-juice-shop/](https://owasp.org/www-project-juice-shop/)

## Objective

The primary objective of this assessment was to identify, exploit, and document a wide range of web security vulnerabilities within the Juice Shop environment. This serves as a practical exercise in applying vulnerability assessment methodology and demonstrating common web security flaws.

## Team Members (Group CAI2_ISS3_G1)

*   Mahmoud Mohamed Abdelaziz
*   Mohamed Samir Mohamed
*   Khaled Galal Yehia
*   Ahmed Aziz Habib

## Instructor

*   Ahmed Hisham

## Report Overview

The full report (`Vulnerability_Assessment_Report_OWASP_Juice_Shop.pdf` - *assuming filename*) provides a detailed analysis of numerous vulnerabilities discovered within the OWASP Juice Shop.

For each vulnerability, the report includes:

*   **Vulnerability Name & Challenge:** Clear identification.
*   **Severity/Difficulty:** Juice Shop's rating.
*   **Location/URL & Parameter:** Specific endpoint and input field.
*   **Description:** Explanation of the vulnerability.
*   **Steps to Reproduce (STR):** Detailed steps to replicate the finding.
*   **Proof of Concept (PoC):** Payloads used and illustrative screenshots.
*   **Impact:** Potential consequences of exploitation.
*   **Root Cause (Conceptual):** Underlying reason for the vulnerability.
*   **Remediation / How to Fix:** Suggested mitigation strategies.
*   **Tools Used:** Tools employed during the discovery/exploitation.

## Vulnerabilities Covered

This report details the findings for **34 distinct vulnerabilities** discovered within the OWASP Juice Shop. These vulnerabilities span various categories, including but not limited to:

*   SQL Injection (SQLi - Error-Based, UNION-Based, Blind)
*   Cross-Site Scripting (XSS - Reflected, Stored, DOM-based)
*   Insecure Direct Object References (IDOR) / Broken Access Control (BAC)
*   Missing Function Level Access Control
*   Sensitive Data Exposure (Backup Files, Weak Hashing)
*   Security Misconfiguration (Deprecated Interface, Header Issues)
*   Vulnerable and Outdated Components
*   Improper Input Validation
*   Cross-Site Request Forgery (CSRF)
*   Path Traversal / Null Byte Injection
*   Weak Authentication / Brute Force

*(Refer to the full PDF report for the complete list and details)*

## Tools Used

The assessment employed a variety of tools and techniques, including:

*   Manual Browser Testing & Analysis
*   Browser Developer Tools (Network, Storage, Console)
*   Burp Suite (Proxy, Repeater, Intruder)
*   Directory Fuzzing Tools (e.g., ffuf)
*   Dependency Checkers (e.g., Snyk Advisor)
*   OSINT techniques

## How to Use This Report

This report serves as an educational resource and a practical demonstration of vulnerability assessment techniques applied to a known insecure application. It can be used for:

*   Learning about specific web vulnerabilities.
*   Understanding common exploitation methods.
*   Observing the documentation and reporting process.
*   Reviewing suggested remediation strategies.

## Disclaimer

**OWASP Juice Shop is *intentionally* vulnerable.** The findings documented in this report are expected within this training environment and are part of the application's design for educational purposes. **Do not attempt these techniques against systems without explicit, authorized permission.**
