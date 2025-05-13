# Week 5 - Ethical Hacking & Exploiting Vulnerabilities Report

## Overview
This week focused on hands-on exploitation and remediation of key vulnerabilities in a Node.js web application (NodeGoat) running on Kali Linux. The objective was to simulate real-world attack scenarios and implement effective security measures.

---

## ✅ Task 1: Reconnaissance using Nmap
- **Tool:** Nmap
- **Objective:** Identify open ports and services running on the target host.
- **Command Used:**
  ```bash
  nmap -sV -p- 127.0.0.1
 Task 2: SQL Injection Testing and Prevention
Target: Signup/Login forms

Test Performed: Manual SQL Injection attack (e.g., ' OR '1'='1)

Result: Initial bypass achieved, confirming vulnerability.

Fix Implemented: Used input validation and ORM-level query protection in user.js
 Task 3: CSRF Protection Implementation
Tool: csurf middleware in Node.js

Objective: Protect forms from Cross-Site Request Forgery attacks.

Steps Taken:

Installed and configured csurf in app.js

Token rendered in signup.jade form

Token validated in route logic
Conclusion
Successfully performed end-to-end ethical hacking tests and implemented countermeasures. 
This week strengthened my ability to find, exploit,
and secure common web vulnerabilities in real-world applications.
