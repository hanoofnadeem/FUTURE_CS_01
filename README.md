# FUTURE_CS_01 - Vulnerability Assessment Report

## Track Code
CS (Cyber Security)

## Task Number
Task 1

## Website Tested
**http://httpforever.com**

## Date
April 26, 2026

## Author
Hanoof Nadeem

## Scope
- Public-facing website only
- Read-only, passive analysis
- No exploitation or harmful activities

## Tools Used
- **Nmap 7.99** - Port scanning and service version detection
- **SecurityHeaders.com** - Security headers analysis
- **Browser DevTools** - Manual verification

## Summary
A security assessment was performed on http://httpforever.com. The website has 5 security weaknesses:
- **2 HIGH risks** (No HTTPS redirect, Invalid SSL certificate)
- **2 MEDIUM risks** (Exposed SSH and SMTP services)
- **1 LOW risk** (Outdated nginx version)

## Key Findings

| Finding | Risk Level |
|---------|------------|
| No HTTPS redirect (HTTP still works) | **HIGH** |
| Invalid SSL certificate (CERT_DATE_INVALID) | **HIGH** |
| SSH service exposed (Port 22) | **MEDIUM** |
| SMTP service exposed (Port 25) | **MEDIUM** |
| Outdated nginx 1.18.0 | **LOW** |

## Repository Contents
- `report.pdf` - Vulnerability Assessment Report
- `/evidence` - Screenshots from Nmap and security scans

## How to View the Report
Download `report.pdf` to see complete findings and remediation steps.
