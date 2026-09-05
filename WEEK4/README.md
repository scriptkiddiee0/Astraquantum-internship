# OWASP Top 10 Foundations — Beginner Track Lab Report

Write-up of four Apprentice-level [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs, completed as part of AstraQuantum Tech's Offensive Security Training (Task ID: WEBSEC-W01-BEGINNER).

## Labs Covered

| Lab | OWASP Category |
|---|---|
| SQL Injection in WHERE Clause | A03:2021 – Injection |
| Reflected XSS into HTML Context (Nothing Encoded) | A03:2021 – Injection |
| Unprotected Admin Functionality | A01:2021 – Broken Access Control |
| CSRF Vulnerability with No Defenses | A01:2021 – Broken Access Control |

Each write-up covers recon, the exploitation steps/payload used, proof of completion, root-cause explanation, real-world impact, and mitigation recommendations.

## Tools

- Browser (Chromium/Firefox)
- Burp Suite Community Edition
- PortSwigger Web Security Academy

## Scope

All testing was performed exclusively against PortSwigger's own hosted lab environments — no techniques here were applied to any external system.

**Author:** Nazish Saghir (AQT-172)
