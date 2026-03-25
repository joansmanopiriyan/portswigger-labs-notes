# PortSwigger Web Security Academy – Lab Notes

This repository contains my structured documentation and walkthroughs from PortSwigger Web Security Academy labs.

The goal of this repository is to strengthen my understanding of web application security concepts through hands-on vulnerability testing and structured reporting practice.

Each lab report includes:

- vulnerability description
- exploitation steps
- payload used
- impact analysis
- mitigation recommendations
- key learning outcomes

These notes reflect my practical learning approach toward web application penetration testing and vulnerability assessment.

---

## Vulnerability Categories Covered

### SQL Injection

Practiced multiple SQL injection techniques including:

- WHERE clause injection for hidden data retrieval
- Authentication bypass
- Database version fingerprinting (Oracle, MySQL, MSSQL)
- UNION-based data extraction
- Blind SQL injection using time delays

---

### File Path Traversal

Practiced directory traversal exploitation techniques including:

- Basic traversal attacks
- Absolute path bypass
- Non-recursive filtering bypass
- Double URL encoding bypass

---

### Access Control Vulnerabilities

Practiced multiple authorization bypass scenarios including:

- Unprotected admin functionality
- Role-based privilege escalation
- IDOR vulnerabilities
- HTTP method-based bypass
- Referer header bypass
- Multi-step workflow access control weaknesses


---

## Skills Developed Through These Labs

Through these exercises I practiced:

- identifying injection points
- parameter manipulation techniques
- authentication workflow testing
- authorization bypass analysis
- database fingerprinting methods
- input validation bypass techniques
- structured vulnerability reporting

---

## Tools Used During Practice

- Burp Suite
- Browser Developer Tools
- PortSwigger Web Security Academy Labs
- HTTP request interception and modification techniques

---

## Learning Approach

Each vulnerability report follows a consistent structure:

- Objective
- Injection point
- Payload used
- Exploitation steps
- Impact
- Mitigation
- Key learning outcome

This approach helps simulate real-world vulnerability assessment reporting workflows.
