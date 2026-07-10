# Week 5 – Ethical Hacking & Exploiting Vulnerabilities

## Overview

This project focuses on learning ethical hacking techniques in a controlled testing environment. The objective is to identify common web application vulnerabilities, understand how attackers exploit them, and implement appropriate security measures to protect the application.

---

## Objectives

- Learn ethical hacking fundamentals.
- Perform reconnaissance on a test web application.
- Identify SQL Injection vulnerabilities.
- Prevent SQL Injection attacks.
- Implement Cross-Site Request Forgery (CSRF) protection.
- Validate security improvements using penetration testing tools.

---

## Features Implemented

### 1. Ethical Hacking Basics

- Used Kali Linux as the penetration testing environment.
- Performed reconnaissance on a test web application.
- Identified potential security weaknesses.

### 2. SQL Injection Testing & Prevention

- Used SQLMap to test for SQL Injection vulnerabilities.
- Applied parameterized queries (Prepared Statements) to prevent SQL Injection attacks.
- Validated that malicious SQL payloads were successfully blocked.

### 3. CSRF Protection

- Implemented CSRF protection using the **csurf** middleware in Node.js.
- Generated and validated CSRF tokens for sensitive requests.
- Tested CSRF protection using Burp Suite.

---

## Technologies Used

- Kali Linux
- SQLMap
- Burp Suite Community Edition
- Node.js
- Express.js
- csurf Middleware
- MySQL / MongoDB (depending on project)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/week5-ethical-hacking.git
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
npm start
```

---

## Security Testing

The following security assessments were performed:

- Reconnaissance of the target application
- SQL Injection testing using SQLMap
- Verification of Prepared Statements
- CSRF attack simulation using Burp Suite
- Validation of CSRF token protection

---

## Project Structure

```
project/
│
├── routes/
├── middleware/
├── controllers/
├── config/
├── app.js
├── package.json
└── README.md
```

---

## Deliverables

- Ethical Hacking Assessment Report
- SQL Injection Testing Results
- Prepared Statements Implemented
- CSRF Protection Enabled
- Security Improvements Documented
- Updated GitHub Repository

---

## Future Improvements

- Implement JWT Authentication
- Add Multi-Factor Authentication (MFA)
- Integrate OWASP ZAP for automated scanning
- Perform XSS vulnerability testing
- Add Security Logging and Monitoring
- Conduct Regular Penetration Testing

---

## Learning Outcomes

After completing this project, the following concepts were understood and implemented:

- Ethical Hacking Methodology
- Web Application Reconnaissance
- SQL Injection Detection
- SQL Injection Prevention
- CSRF Protection
- Secure Backend Development
- Basic Penetration Testing Techniques

---

## Disclaimer

This project was conducted strictly for educational purposes in a controlled and authorized testing environment. No unauthorized systems were targeted or exploited.

---

## Author

Cybersecurity Internship – Week 5
