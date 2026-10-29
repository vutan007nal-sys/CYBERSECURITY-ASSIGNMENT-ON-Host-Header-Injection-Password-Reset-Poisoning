# CYBERSECURITY-ASSIGNMENT-ON-Host-Header-Injection-Password-Reset-Poisoning
# Cybersecurity Assignment: Host Header Injection & Password Reset Poisoning

## 📌 Project Overview

This project explains **Host Header Injection** and **Password Reset Poisoning**, two web security issues that can occur when applications trust unvalidated HTTP host-related headers.

The assignment covers the concepts, security risks, authorized lab testing methodology, mitigation techniques, and references.

## 🎯 Objectives

- Understand the HTTP Host header and its purpose.
- Learn how Host Header Injection occurs.
- Understand Password Reset Poisoning and its potential impact.
- Practice security testing in an authorized lab using Burp Suite.
- Identify effective prevention and mitigation techniques.

## 📚 Topics Covered

1. Introduction to Host Header Injection
2. HTTP Host and `X-Forwarded-Host` headers
3. Password Reset Poisoning
4. Security impact and potential risks
5. Authorized lab testing methodology
6. Prevention and mitigation
7. Security testing questions

## 🛠️ Tools Used

- **Burp Suite** — Intercept and inspect HTTP requests.
- **Web Browser Developer Tools** — Analyze requests and responses.
- **Local Vulnerable Web Application** — Practice in a controlled environment.

## 🔬 Lab Methodology

1. Set up an authorized web security testing lab.
2. Trigger the password-reset functionality using a test account.
3. Inspect the HTTP request and generated reset URL.
4. Check how the application handles host-related headers.
5. Record sanitized evidence of any security weakness.
6. Verify that the application generates reset links using a trusted domain.

**Note:** Perform testing only on applications you own or have explicit permission to assess. Never expose real password-reset tokens or personal information in screenshots or commits.

## 🛡️ Prevention and Mitigation

- Use a fixed, trusted domain to generate password-reset URLs.
- Validate incoming hostnames against an allowlist.
- Configure reverse proxies to handle
