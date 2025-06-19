 1. File Integrity Checker

-->Description
This tool monitors changes in files by calculating and comparing hash values using SHA-256.

-->How to Run
Run the code in Jupyter Notebook or VS Code.

On first run, it saves the hash values of files in the folder.

On second run, it compares current hashes to the saved ones and detects:

❌ Deleted files

⚠ Modified files

🔟 New files added

 Inputs Needed
Change the variable folder_to_monitor to your folder name (default: test_files).

folder_to_monitor = "test_files"

2. Web Vulnerability Scanner

-->Description
This scanner detects common web vulnerabilities like SQL Injection and Cross-Site Scripting (XSS).

--> How to Run
Run the code.
Enter a URL of a test website like:
https://testphp.vulnweb.com
The script will crawl forms and check them for common vulnerabilities.
--> Inputs Needed
A URL to a vulnerable/test web app (example: https://testphp.vulnweb.com).

3. Penetration Testing Toolkit

-->Description
Includes:
Port Scanner
SSH Brute-Force Tester
Network Host Discovery
-->How to Run
Run the script, then select the option (1, 2, or 3):

Option 1: Port Scanner

Input: Any IP or domain (e.g., 192.168.1.1 or testphp.vulnweb.com)

Option 2: SSH Brute-Force

IP: test.rebex.net

Username: demo

Password list is hardcoded: ['admin', '1234', 'password', 'root', 'toor']

Option 3: Host Discovery

IP Prefix: 192.168.1 will scan from 192.168.1.1 to 192.168.1.254


4. Advanced Encryption Tool

-->Description

This project allows you to encrypt and decrypt any file using AES-256 (Fernet).

-->How to Run

Run the script.

Select:

1 for encryption

2 for decryption

Input full path of file (e.g., C:/Users/RAYI/Documents/file.txt)

Input a password (custom; it will generate a key from it)
--> Inputs Needed

File path: e.g., C:/Users/RAYI/Documents/file.txt

Password: Your own custom password
