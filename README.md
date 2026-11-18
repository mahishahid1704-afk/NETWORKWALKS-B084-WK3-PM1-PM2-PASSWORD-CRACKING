# NETWORKWALKS-B084-WK3-PM1-PM2-PASSWORD-CRACKING
<p align="center">
  <img src="https://img.shields.io/badge/CYBERSECURITY-PRACTICAL%20PROJECT-0A7B83?style=for-the-badge" alt="Cybersecurity Practical Project">
  <img src="https://img.shields.io/badge/NETWORKWALKS-INTERNSHIP-2563EB?style=for-the-badge" alt="NetworkWalks Internship">
  <img src="https://img.shields.io/badge/WEEK-03-6F42C1?style=for-the-badge" alt="Week 03">
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-238636?style=for-the-badge" alt="Project Completed">
</p>
<p align="center">
  <a href="(https://github.com/mahishahid1704-afk)">
    <img src="https://img.shields.io/badge/GitHub-josuemutsiirwa-181717?style=for-the-badge&logo=github" alt="GitHub Profile">
  </a>
  <a href="https://www.linkedin.com/in/josue-matembera-37a269407/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20me-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn Profile">
  </a>
  <img src="https://img.shields.io/badge/TOOLS-John%20the%20Ripper%20%7C%20Johnny%20%7C%20NetworkWalks-orange?style=for-the-badge" alt="Project Tools">
</p>

---

## 1. PROJECT OVERVIEW

This repository contains the practical projects completed during **Week 3 of the NetworkWalks Cybersecurity Internship**.

The main focus of this week's activities was password recovery using two different approaches:

- **W3-PM1:** Password cracking using John the Ripper and its graphical interface, Johnny.
- **W3-PM2:** Password cracking using NetworkWalks online tools.

Both exercises involved extracting a password hash from a protected PDF document, attempting to recover its password, and checking whether the recovered password could successfully open the document.

These activities provided an opportunity to work with password hashes, wordlists, and dictionary-based password attacks.

## 2. PROJECT OBJECTIVES

The objectives of these practical exercises were to:

- Understand the concept of password hashing.
- Extract password hashes from password-protected PDF documents.
- Learn how to use John the Ripper.
- Configure and use Johnny as a graphical interface for John the Ripper.
- Understand how dictionary-based password attacks work.
- Work with built-in and external wordlists.
- Compare locally installed password-cracking software with online tools.
- Verify password recovery by opening the protected PDF document.

## 3. TOOLS AND TECHNOLOGIES

The following tools and resources were used during the two projects:

| Tool / Resource | Purpose |
|---|---|
| John the Ripper | Password-cracking software |
| Johnny | Graphical interface for John the Ripper |
| NetworkWalks Hash Calculator | Extracting password hashes |
| NetworkWalks Password Cracker | Performing password-recovery attempts |
| PDF Hash Extractor | Extracting the PDF password hash |
| JTR Default Password List | External wordlist used during the exercise |
| Windows | Operating system used for the local JTR practical |
| Web Browser | Accessing the online tools |

---

# 4. W3-PM1 — PASSWORD CRACKING WITH JOHN THE RIPPER

## 4.1 Project Description

The first practical exercise involved recovering the password of a protected PDF document using **John the Ripper (JTR)**.

The exercise was carried out on Windows. I used Johnny as the graphical interface to configure and manage the password-cracking process.

## 4.2 Tools Used

- John the Ripper
- Johnny GUI
- PDF Hash Extractor
- Notepad
- Password-protected PDF document

## 4.3 Practical Procedure

The following steps were completed during the exercise:

1. Downloaded the password-protected PDF document.
2. Launched Johnny.
3. Configured Johnny by providing the location of the John the Ripper executable.
4. Used a PDF hash extraction tool to extract the password hash.
5. Saved the extracted hash in a text file named `hash1.txt`.
6. Loaded the saved hash file into Johnny.
7. Configured and started the password-cracking attack.
8. Used the recovered password to open the PDF document and confirm that it worked.

## 4.4 Screenshots and Evidence

The screenshots below show the main stages of the practical exercise, from downloading the PDF to successfully opening it.

### Step 1 — PDF Downloaded

The password-protected PDF document was downloaded and prepared for the exercise.

![PDF Downloaded](W3-PM1-John-the-Ripper/01-pdf-downloaded.png)

### Step 2 — Johnny Launched

Johnny was launched to provide a graphical interface for working with John the Ripper.

![Johnny Launch](W3-PM1-John-the-Ripper/02-johnny-launch.png)

### Step 3 — Johnny Configuration

The location of the John the Ripper executable was configured in Johnny.

![Johnny Configuration](W3-PM1-John-the-Ripper/03-johnny-configuration.png)

### Step 4 — PDF Hash Extraction

The password hash was extracted from the protected PDF using a PDF hash extraction tool.

![PDF Hash Extraction](W3-PM1-John-the-Ripper/04-pdf-hash-extraction.png)

### Step 5 — Hash Saved in Notepad

The extracted hash was saved in a text file named `hash1.txt` for use in Johnny.

![Hash Saved in Notepad](W3-PM1-John-the-Ripper/05-hash-saved-in-notepad.png)

### Step 6 — Hash Loaded into Johnny

The saved hash file was loaded into Johnny in preparation for the password-cracking attempt.

![Hash Loaded in Johnny](W3-PM1-John-the-Ripper/06-hash-loaded-in-johnny.png)

### Step 7 — Attack Results

The password-cracking process was started using the configured tool. This screenshot shows the results of the attack.

![Attack Results](W3-PM1-John-the-Ripper/07-attack-results.png)

### Step 8 — PDF Successfully Unlocked

After recovering the password, I used it to open the protected PDF document successfully.

![PDF Successfully Unlocked](W3-PM1-John-the-Ripper/08-pdf-successfully-unlocked.png)

## 4.5 Project Outcome

I successfully completed the password-recovery exercise using John the Ripper and Johnny.

The practical helped me understand how to extract a PDF password hash, load it into a cracking tool, and verify the result by opening the protected document.

---

# 5. W3-PM2 — PASSWORD CRACKING WITH NETWORKWALKS TOOLS

## 5.1 Project Description

The second practical exercise focused on using NetworkWalks online tools to extract and recover the password of a protected PDF document.

Unlike the first exercise, which involved locally installed software, this project was completed using browser-based tools provided by NetworkWalks.

An important part of this exercise was testing the built-in wordlist and then trying an external wordlist when the first attempt did not recover the password.

## 5.2 Tools Used

- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- JTR Default Password List
- Web Browser
- Password-protected PDF document

## 5.3 Practical Procedure

The following steps were completed:

1. Downloaded the password-protected PDF document.
2. Opened the NetworkWalks Hash Calculator.
3. Uploaded the PDF document and extracted its password hash.
4. Copied the extracted hash, which began with `$pdf$`.
5. Opened the NetworkWalks Password Cracker.
6. Loaded the extracted hash into the password-cracking tool.
7. Started a password-recovery attempt using the built-in wordlist.
8. Observed that the built-in wordlist did not recover the password.
9. Downloaded and uploaded an external wordlist named `JTR_default_password.txt`, containing 3,556 words.
10. Started another password-cracking attempt using the external wordlist.
11. Successfully recovered the password and used it to open the protected PDF document.

## 5.4 Screenshots and Evidence

The screenshots below document the process, including the unsuccessful first attempt and the successful recovery using an external wordlist.

### Step 1 — PDF Downloaded

The password-protected PDF document was downloaded for the practical exercise.

![PDF Downloaded](W3-PM2-NetworkWalks-Tools/001-pdf-downloaded.png)

### Step 2 — Hash Calculator Opened

The NetworkWalks Hash Calculator was opened to extract the password hash from the PDF.

![Hash Calculator Opened](W3-PM2-NetworkWalks-Tools/002-hash-calculator-opened.png)

### Step 3 — PDF Hash Extracted

The PDF document was uploaded, and its password hash was extracted.

![PDF Hash Extracted](W3-PM2-NetworkWalks-Tools/003-pdf-hash-extracted.png)

### Step 4 — Password Cracker Opened

The NetworkWalks Password Cracker was opened to begin the recovery process.

![Password Cracker Opened](W3-PM2-NetworkWalks-Tools/004-password-cracker-opened.png)

### Step 5 — Built-in Wordlist Attempt Unsuccessful

The first attempt was performed using the built-in wordlist. However, it did not recover the password.

![Built-in Wordlist Attempt Unsuccessful](W3-PM2-NetworkWalks-Tools/005-builtin-wordlist-attack-unsuccessful.png)

### Step 6 — External Wordlist Uploaded

Since the first attempt was unsuccessful, I uploaded an external wordlist named `JTR_default_password.txt`, containing 3,556 words, for another attempt.

![External Wordlist Uploaded](W3-PM2-NetworkWalks-Tools/006-external-wordlist-uploaded.png)

### Step 7 — Password Successfully Cracked

The second attempt using the external wordlist successfully recovered the password.

![Password Successfully Cracked](W3-PM2-NetworkWalks-Tools/007-password-successfully-cracked.png)

### Step 8 — PDF Successfully Unlocked

I entered the recovered password and successfully opened the protected PDF document.

![PDF Successfully Unlocked](W3-PM2-NetworkWalks-Tools/008-pdf-successfully-unlocked.png)

## 5.5 Project Outcome

I successfully recovered the PDF password using the NetworkWalks Password Cracker.

One important lesson from this exercise was that the built-in wordlist did not recover the password, but the external wordlist succeeded. This helped me understand why choosing an appropriate wordlist matters during a dictionary-based attack.

---

# 6. COMPARISON OF THE TWO PROJECTS

Both exercises focused on recovering the password of a protected PDF document. However, they involved different tools and working environments.

| Comparison | W3-PM1 | W3-PM2 |
|---|---|---|
| Approach | Local password cracking | Online password cracking |
| Main Tool | John the Ripper | NetworkWalks Password Cracker |
| Interface | Johnny GUI | Web interface |
| Hash Extraction | PDF Hash Extractor | NetworkWalks Hash Calculator |
| Wordlist | Configured cracking attack | Built-in and external wordlists |
| Environment | Windows | Web Browser |
| Verification | PDF opened successfully | PDF opened successfully |

## 7. KEY LEARNING OUTCOMES

Through these practical exercises, I gained experience in:

- Extracting password hashes from protected PDF documents.
- Using John the Ripper for password-recovery exercises.
- Configuring Johnny to work with John the Ripper.
- Loading password hashes into cracking tools.
- Understanding dictionary-based password attacks.
- Working with built-in and external wordlists.
- Understanding why one wordlist may fail while another succeeds.
- Comparing locally installed security tools with online tools.
- Verifying password recovery by opening a protected document.

These exercises also improved my confidence in working with password-security tools and following a practical password-recovery process.

## 8. ETHICAL CONSIDERATIONS

Password-cracking tools can be useful for authorized security testing, password recovery, and cybersecurity education. However, using them against files or systems without permission is inappropriate.

The activities documented in this repository were completed as part of a cybersecurity learning exercise.

These techniques should only be used on files, systems, and environments that you own or have explicit authorization to test.

## 9. REFERENCES AND LEARNING RESOURCES

The following resources were used during the practical exercises:

1. **John the Ripper — Official Website**  
   https://www.openwall.com/john/

2. **NetworkWalks Hash Calculator**  
   https://networkwalks.com/hash-calculator/

3. **NetworkWalks Password Cracker**  
   https://networkwalks.com/password-cracker/

4. **NetworkWalks Password Cracking Project Instructions**  
   https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/

5. **Online PDF Hash Extractor**  
   https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

## 10. CONCLUSION

Week 3 gave me an opportunity to work with different password-recovery tools and understand how they are used in practice.

Through the two projects, I gained hands-on experience with John the Ripper, Johnny, and NetworkWalks online tools. I also learned how to extract password hashes, use wordlists, perform dictionary-based attacks, and verify the results.

Overall, these exercises strengthened my understanding of password security and provided useful practical experience for my continued learning in cybersecurity and ethical penetration testing.

---

## 11. AUTHOR INFORMATION

**Name:** Maham Shahid 

**Program:** NetworkWalks Cybersecurity Internship

**Batch:** B084

**Project:** Week 3 — Password Cracking Projects

**GitHub:** 

**LinkedIn:** https://www.linkedin.com/in/maham-shahid-93b0a2261/
