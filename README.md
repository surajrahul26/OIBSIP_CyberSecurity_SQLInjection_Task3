# OIBSIP_CyberSecurity_SQLInjection_Task3
Performed SQL Injection on DVWA (Low Security) to demonstrate how malicious users can exploit input fields to access unauthorized data

# Task 3: SQL Injection on DVWA (Low Security)

## 🔐 Objective
To demonstrate a basic SQL Injection vulnerability using DVWA with the security level set to LOW.

## 🛠 Tools Used
- Kali Linux (Apache2 & MySQL)
- DVWA (Damn Vulnerable Web App)
- Web Browser
- Bash Script

## 🔎 Steps Performed
1. Started Apache and MySQL services.
2. Configured and launched DVWA at `http://localhost/DVWA`
3. Set DVWA security level to **Low**
4. Navigated to **SQL Injection** module.
5. Injected payload: `1' OR '1'='1`
6. Successfully retrieved all user records.

## 📸 Output
Screenshot: `sql_injection_result.png`

## 📜 Script
File: `sql_injection_exploit.sh`  
Description: Demonstrates the payload used.

## 📘 Learning Outcome
- Understood SQL Injection basics.
- Learned how weak input validation exposes data.
- Gained hands-on experience with DVWA.

## 🙋‍♂️ Author
Suraj Vishwakarma    

