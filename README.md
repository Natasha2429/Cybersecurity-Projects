 Cybersecurity Internship Projects

 COMPANY: CODTECH IT SOLUTIONS
 
 NAME: RAYI NATASHA
 
 INTERN ID: CT04DF12
 
 DOMAIN: CYBER SECURITY AND ETHICAL HACKING
 
 DURATION:4 WEEKS
 
 MENTOR:NEELA SANTHOSH

This repository contains **four practical cybersecurity tools** developed as part of an internship. Each project is implemented in Python and demonstrates core cybersecurity concepts like integrity checking, vulnerability scanning, penetration testing, and encryption.

---

## Project Overview

###  1. File Integrity Checker
- **Purpose**: Monitors a folder for changes using SHA-256 hashes.
- **Tech Used**: `hashlib`, `json`
- **Run**: Use Jupyter or VS Code to detect modified, added, or deleted files.
- **Location**: [`1_File_Integrity_Checker/`](./1_File_Integrity_Checker)

---

###  2. Web Vulnerability Scanner
- **Purpose**: Identifies web app vulnerabilities like SQL Injection and XSS.
- **Tech Used**: `requests`, `BeautifulSoup`
- **Run**: Input a test website URL (e.g., `https://testphp.vulnweb.com`)
- **Location**: [`2_Web_Vulnerability_Scanner/`](./2_Web_Vulnerability_Scanner)

---

###  3. Penetration Testing Toolkit
- **Purpose**: Includes Port Scanner, SSH Brute Forcer, Host Discovery
- **Tech Used**: `socket`, `paramiko`, `threading`
- **Run**: Choose module via command-line input.
- **Location**: [`3_Penetration_Testing_Toolkit/`](./3_Penetration_Testing_Toolkit)

---

###  4. Advanced Encryption Tool
- **Purpose**: Encrypt and decrypt files using AES-256 encryption (Fernet)
- **Tech Used**: `cryptography`, `hashlib`, `base64`
- **Run**: Choose to encrypt or decrypt. Enter file path and password.
- **Location**: [`4_AES_Encryption_Tool/`](./4_AES_Encryption_Tool)

---

##  How to Run All Projects
1. Clone or download this repository.
2. Open each `.ipynb` file in **Jupyter Notebook** or `.py` file in **VS Code**.
3. Follow instructions in each folder's `README.md`.

---

## Deployment Instructions
If submitting for review:
1. Ensure each project runs successfully.
2. Push to GitHub via terminal:
   ```bash
   git init
   git add .
   git commit -m "✅ Added all cybersecurity projects"
   git remote add origin https://github.com/YourUsername/YourRepoName.git
   git push -u origin main
