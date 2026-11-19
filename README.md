# Week 03 – Password Cracking & Cryptographic Security 🔐

## Cybersecurity & Ethical Hacking Internship | NETWORKWALKS

Week 3 of my Cybersecurity & Ethical Hacking Internship focused on understanding cryptographic password security, password hashing, and practical password recovery techniques.

The objective was to explore how password-protected PDF files can be tested for weak passwords using dictionary attacks in a controlled and authorized lab environment.

### 🎯 Tasks Performed

**1. Password Cracking with John the Ripper (W3-PM1)**

Tools used:
- Kali Linux
- John the Ripper (JTR)
- pdf2john

Steps performed:
1. Extracted the cryptographic password hash from a password-protected PDF using `pdf2john`.
2. Prepared the extracted hash for password-cracking analysis.
3. Used John the Ripper to perform an offline dictionary attack.
4. Successfully recovered the password.
5. Unlocked the protected PDF and captured the first flag.

**2. Password Forensics with NetworkWalks Security Tools (W3-PM2)**

Tools used:
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker

Steps performed:
1. Extracted the PDF verification hash using the NetworkWalks Hash Calculator.
2. Prepared the extracted hash for analysis.
3. Used the NetworkWalks Password Cracker to perform a dictionary attack.
4. Successfully recovered the password.
5. Opened the protected document and captured the second flag.

### 💡 Key Learnings

- Understood the difference between encryption and cryptographic hashing.
- Learned how password hashes can be extracted from protected PDF files.
- Explored offline dictionary attacks and password recovery techniques.
- Understood why weak and commonly used passwords are vulnerable.
- Learned the importance of strong passwords, unique passphrases, and salted password hashes.
- Explored modern password-hashing algorithms such as Argon2, bcrypt, and PBKDF2.

### 🛠️ Skills & Tools Practiced

`Kali Linux` `John the Ripper` `pdf2john` `Password Hashing` `Dictionary Attack` `Cryptography` `Password Forensics`

### 🔐 Security Note

All activities were performed strictly within the authorized internship training environment for educational purposes. Password cracking without proper authorization is illegal and unethical.

### 📌 Internship Progress

**Week 03 Completed ✅**
Snehal ugale..
