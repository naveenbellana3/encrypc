<p align="center">
  <img src="https://user-images.githubusercontent.com/72680045/102007940-19d68080-3d53-11eb-8518-d681586666e6.png">
  <h2 align="center" style="margin-top: -4px !important;">File Encryption Application using Python</h2>
  <p align="center">
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-informational">
    </a>
    <a href="https://www.python.org/">
    	<img src="https://img.shields.io/badge/python-v3.8-informational">
    </a>
    <img src="https://img.shields.io/badge/version-v1.0.0-blue">
    <img src="https://img.shields.io/badge/maintenance-active-success">
  </p>
</p>

# EncrypC

<p align="center">
	<img src="https://user-images.githubusercontent.com/72680045/103018817-d0184200-456b-11eb-8fd2-11893c3173cd.PNG" alt="EncrypC Stable">
  <img src="https://user-images.githubusercontent.com/72680045/103018827-d1e20580-456b-11eb-8503-173356c1cde9.PNG" alt="EncrypC Working">
</p>

## Tech Stack Used:
* Python3
* Tkinter for GUI (Inbuilt)
* pycryptodomex for Cryptodome (AES Encryption)

### External Dependencies to be Installed:
* `pycryptodomex` (AES encryption)
```sh
pip install pycryptodomex
```

## Tutorial to Encrypt/Decrypt Files:
1. Open the Application and Click SELECT FILE Button to select your file e.g. "mydoc.pdf" (OR You can add path manually).
2. Enter your Key (This should be alphanumeric letters). Remember this so you can Decrypt the file later. (Else you'll lose your file permanently)
3. Click ENCRYPT Button to encrypt the file. A new encrypted file with ".encr" extention e.g. "mydoc.pdf.encr" will be created in the same directory where the "mydoc.pdf" is.
4. When you want to Decrypt a file you, will select the file with the ".encr" extention and Enter your Key which you chose at the time of Encryption. Click DECRYPT Button to decrypt. The decrypted file will be of the same name as before with the suffix "decrypted" for e.g. "mydoc_decrypted.pdf".
5. Click CLEAR Button to reset the input fields and status bar.

## Important Note:
- The Maintainer will not be responsible for any kind of loss of data so it is essential to have a Backup of Original Data you give as Input to Encrypt/Decrypt in the Software. Under no circumstances shall we be liable or responsible to you or any other person for any damages, loss of any of your useful data by using this Software. Read the LICENSE for more information.

## About the Developer
Naveen Bellana is a Security Analyst with over 4 years of experience in cybersecurity monitoring, incident response, and vulnerability management. With a strong background in Python automation and security analytics, Naveen maintains this project to provide a streamlined tool for secure file handling and data protection.

- Title: Security Analyst
- Skills: Python, PowerShell, Bash, Automation Scripting, ISO/IEC 27001, NIST CSF
- Email: naveenbellana04@gmail.com
- LinkedIn: https://www.linkedin.com/in/naveenbellana