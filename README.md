# OWASP-ZAP
DVWA Web Application Security Scan -OWASP ZAP
# DVWA Web Application Security Scan – OWASP ZAP

## Overview

This project documents a full web application vulnerability assessment conducted on **Damn Vulnerable Web Application (DVWA)** using **OWASP ZAP**.

## Objectives

* Perform passive and active scanning using OWASP ZAP
* Identify common OWASP Top 10 vulnerabilities
* Document findings and remediation strategies

## Tools Used

* DVWA (Localhost)
* OWASP ZAP
* Web Browser


## Methodology

1. Proxy DVWA traffic through OWASP ZAP
2. Crawl application using Spider
3. Perform Active Scan
4. Analyze alerts and risks
5. Document vulnerabilities and remediation

## Key Findings

* Remote Code Execution - CVE-2012-1823
* Source Code Disclosure - CVE-2012-1823
* Absence of Anti-CSRF Tokens
* Content Security Policy (CSP) Header Not Set
* Directory Browsing

## Remediation Summary

* Prepared SQL statements
* Input validation and output encoding
*  Principle of least privilege
* CSRF tokens
* Secure HTTP headers


