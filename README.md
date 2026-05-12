# Bug Hunting Project – Real-World Vulnerability Discovery

## Overview
This project explores the basics of real-world bug bounty programs, including scope rules, vulnerability severity, payout mapping, and professional vulnerability reporting.

The project also includes a simulated Reflected Cross-Site Scripting (XSS) report using DVWA as a safe lab environment.

---

## Objectives
- Understand how bug bounty platforms operate
- Differentiate between in-scope and out-of-scope vulnerabilities
- Understand severity levels and payout ranges
- Write a professional vulnerability report
- Apply ethical hacking principles in a controlled environment

---

## Task 1 – Out-of-Scope Analysis

This section explains what “Out of Scope” means in bug bounty programs and why certain vulnerabilities may not qualify for rewards.

### Examples Covered
- Self-XSS
- Rate limiting issues
- Missing security headers
- Clickjacking
- Denial of Service testing

### Risks of Testing Outside Scope
- Platform bans
- Legal consequences
- Account suspension
- Reputation damage

---

## Task 2 – Payout Mapping

| Severity | Example Vulnerability | Estimated Payout |
|---|---|---|
| Low | Information Disclosure | $50 – $300 |
| Medium | Cross-Site Scripting (XSS) | $300 – $1,000 |
| High | Insecure Direct Object Reference (IDOR) | $1,000 – $5,000 |
| Critical | Remote Code Execution (RCE) | $5,000+ |

---

## Task 3 – Dummy Bug Report

### Vulnerability Simulated
Reflected Cross-Site Scripting (XSS)

### Payload Used

```html
<script>alert('XSS')</script>
Impact


Session theft


Phishing attacks


Malicious redirects


Page manipulation


Recommended Fixes


Sanitize user input


Encode output before rendering


Implement Content Security Policy (CSP)



Screenshots
Vulnerable Input Field

Payload Reflection and Execution


Tools Used


DVWA


Kali Linux


Firefox


GitHub



Key Takeaways
This project helped reinforce:


Ethical hacking principles


Vulnerability reporting


Web application security basics


Responsible testing practices



Author
Osiogbhemhe Oarue-Itseuwa
