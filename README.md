
# OWASP ZAP Web Application Vulnerability Scan

## Objective
To perform a full vulnerability assessment of a web application using OWASP ZAP and document findings and remediation steps.

## Tools Used
* DVWA (Localhost)
* OWASP ZAP
* Kali Linux

## Methodology
- Automated Scan
- Crawl application using Spider
- Passive and Active Scanning
- Analyze alerts and risks

## Key Findings
| Risk Level | Vulnerability |
|----------|---------------|
| High | SQL Injection |
| Medium | Cross-Site Scripting (XSS) |
| Low | Missing Security Headers |
| Info | Cookie Security Flags |

## Remediation Summary
- Implement input validation
- Use parameterized queries
- Add HTTP security headers
- Harden session management

## Lessons Learned
This exercise improved my understanding of automated vulnerability scanning, interpreting scan results, and mapping findings to real-world security controls.

