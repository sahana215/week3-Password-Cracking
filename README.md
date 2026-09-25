# Week 3 – Password Cracking & Hash Analysis

## 📌 Project Overview

This Week 3 cybersecurity project focuses on understanding password-cracking techniques in an authorized training environment.

The practical work was completed using two modules:

- **W3-PM1 – Password Cracking with John the Ripper**
- **W3-PM2 – Password Cracking with NetworkWalks Tools**

The project demonstrates how password-protected PDF files can be converted into crackable password hashes and how password recovery can be performed using wordlists and password-cracking tools.

---

## 🎯 Objectives

- Understand the basic password-cracking workflow.
- Extract crackable hashes from password-protected PDF files.
- Prepare and use the **RockYou wordlist**.
- Perform password cracking using **John the Ripper (JTR)**.
- Use NetworkWalks password-cracking tools.
- Verify successful password recovery.
- Capture practical evidence and training completion flags.

---

## 🛠️ Tools & Technologies

- Kali Linux
- John the Ripper (JTR)
- RockYou Wordlist
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Password-Protected PDF Files
- Linux Terminal

---

# 🔹 Module 1 – John the Ripper

## Step 1 – Hash Extraction

A password-protected PDF file was converted/extracted into a crackable password hash format.

This hash was then used as input for John the Ripper.

## Step 2 – Wordlist Preparation

The **RockYou** wordlist was prepared in Kali Linux.

The wordlist contains a large collection of commonly used passwords that can be tested against the extracted hash.

## Step 3 – Password Cracking

John the Ripper was used with the extracted hash and the RockYou wordlist.

The tool tested password candidates from the wordlist and successfully recovered the password in the authorized training environment.

### Example Workflow

```bash
john <hash-file> --wordlist=<wordlist>

To display recovered passwords:

john --show <hash-file>


---

🔹 Module 2 – NetworkWalks Password Cracking

The second module was completed using NetworkWalks password-cracking tools.

Step 1 – PDF Hash Extraction

The password-protected PDF was uploaded to the NetworkWalks Hash Calculator.

The tool generated a crackable hash from the PDF.

Step 2 – Password Cracking

The generated hash was provided to the NetworkWalks Password Cracker.

The tool tested possible passwords and successfully recovered the password.

Step 3 – Training Completion

The successful results and training completion flags were captured as practical evidence.


---

📸 Screenshots / Evidence

The project includes screenshots showing:

John the Ripper password-cracking workflow

RockYou wordlist usage

PDF hash extraction

NetworkWalks hash generation

Successful password recovery

Training flags / completion evidence


Screenshots are included in the project evidence folder.


---

🏆 Training Flags

The following flags were obtained during the authorized training exercises:

Flag 1: nw{networkwalks_flag1_jtr_270521_1}
Flag 2: nw{networkwalks_presistence_jtr_270521}
Flag 3: nw{networkwalks_flag_260821_1}


> These flags are included as practical completion evidence from the training environment.

---

📊 Results

Module	Tool	Result

W3-PM1	John the Ripper	Successfully completed
W3-PM2	NetworkWalks Tools	Successfully completed
Hash Extraction	PDF Hash Tools	Successfully completed
Password Recovery	Wordlist-based cracking	Successfully demonstrated
Training Evidence	Flags / Screenshots	Captured
---

📚 Key Learning Outcomes

Through this practical, I learned:

How password-protected PDF hashes can be extracted.

How password hashes are used during password-cracking exercises.

How to prepare and use the RockYou wordlist.

Basic usage of John the Ripper.

How wordlist-based password cracking works.

How NetworkWalks password-cracking tools can be used in a training environment.

How to verify successful password recovery.

The importance of performing security testing only with proper authorization.

🔐 Security & Ethical Considerations

This project was performed in an authorized cybersecurity training environment.

Password-cracking techniques should only be used for:

Authorized labs

Training environments

CTFs

Systems/files where permission has been provided

Real user credentials, private password hashes, or unauthorized systems should never be targeted or published.

✅ Project Status

Status: Completed

Both Week 3 practical modules were successfully completed with screenshots and training evidence.

👩‍💻 Author

Sahana S
