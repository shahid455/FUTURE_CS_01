# Task 1: Web Application Security Testing

🔒 **Intern Name:** Shahid Hasan  
📁 **Task Code:** FUTURE_CS_01  
🎯 **Domain:** Cybersecurity  
📅 **Internship:** Future Interns (Self-paced)

---

## 🧠 Objective

To perform web application security testing using a sample vulnerable application and identify vulnerabilities such as:
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)

---

## 🧰 Tools Used

- DVWA (Damn Vulnerable Web Application)
- Burp Suite Community Edition
- XAMPP (Apache + MySQL)
- Kali Linux (optional)
- Browser (Burp’s or Chrome)

---

## ✅ Vulnerabilities Tested

### 1. SQL Injection
- **Payload Used:** `' OR '1'='1`
- **Result:** Dumped full user list
- **Tool:** Burp Suite

### 2. Reflected XSS
- **Payload Used:** `<script>alert('xss')</script>`
- **Result:** Alert box triggered (input reflected without sanitization)

---

## 📸 Screenshots

All screenshots of request/response are in the `screenshots/` folder.

---

## 📄 Full Report

Read the detailed task report here: [`task1_report.pdf`](Task1.pdf)

---

## 📌 Outcome

This task enhanced my practical understanding of:
- Web application penetration testing
- Secure coding recommendations
- Input validation flaws in real-world systems

---
