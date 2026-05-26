# Web Application Security Testing Lab

This project documents controlled web application security testing using vulnerable lab environments and Burp Suite.

## Overview

The project analyses and demonstrates common web application vulnerabilities, their impact, and relevant defensive measures. The testing was performed in controlled lab environments using PortSwigger Web Security Academy and DVWA.

## Areas Covered

- Cross-Site Request Forgery (CSRF)
- Server-Side Request Forgery (SSRF)
- Authorisation Bypass
- Command Injection
- HTTP request analysis
- Access control testing
- Input validation testing
- Business impact and defensive recommendations

## Tools Used

- Burp Suite
- PortSwigger Web Security Academy
- DVWA
- Kali Linux
- Web browser developer/testing tools

## Key Findings

- CSRF protections failed when the application only compared matching token values without properly validating token authenticity.
- SSRF protection based on weak blacklist filtering was bypassed.
- Authorisation bypass occurred where access control was enforced in the interface but not properly on the server side.
- Command injection was demonstrated where user input was passed into an operating system command without secure restriction.
- Defensive measures included stronger server-side validation, allowlisting, secure token handling, server-side access control enforcement, and defence-in-depth.

## Full Report

See the attached PDF report in this folder for the full methodology, screenshots, findings, and references.

## Disclaimer

This project was completed in controlled lab environments for learning and portfolio purposes. No real systems were targeted.