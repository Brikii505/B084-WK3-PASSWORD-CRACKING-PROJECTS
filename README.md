# B084-WK3-PASSWORD-CRACKING-PROJECTS

### Password Cracking with John the Ripper (JTR) and Networkwalks Tools

---

## Project Information

| Category | Details |
|---|---|
| Academy | Networkwalks Academy |
| Project | Week 3 – Project Modules 1 & 2 |
| Module 1 | Password Cracking with JTR |
| Module 2 | Password Cracking with Networkwalks Tools |
| Operating System | Windows |
| Main Focus | Password Security and Password Recovery |
| Evidence | Screenshots of completed practical tasks |

---

## 1. Liability Disclaimer

This repository documents practical cybersecurity exercises completed for educational purposes as part of Networkwalks Academy's Cybersecurity and Ethical Hacking training.

All activities were performed using the provided lab materials and authorised files. The tools demonstrated in this repository should only be used for educational purposes, security testing, and password recovery where proper permission has been granted.

The purpose of these exercises is to understand password security, identify weaknesses in password protection, and develop practical cybersecurity skills.

---

## 2. Introduction

During Week 3, I completed two practical projects focused on password cracking and password recovery.

The exercises demonstrated how password-protected PDF files can be tested using different tools. I learned how to extract password hashes from encrypted PDF files and use password recovery tools to identify the corresponding passwords.

The first project involved using John the Ripper (JTR) and its graphical interface, Johnny. The second project involved using two browser-based tools provided by Networkwalks: Hash Calculator and Password Cracker.

Both exercises helped me understand the importance of password complexity and the role of password security in protecting sensitive information.

---

## 3. Project Module 1 – Password Cracking with JTR

### 3.1 Objective

The objective of this practical exercise was to recover the password of the provided protected PDF file, `My Locked PDF1.pdf`, using John the Ripper (JTR) and Johnny on a Windows PC.

### 3.2 Tools Used

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password recovery tool |
| Johnny GUI | Graphical interface for John the Ripper |
| Online PDF Hash Extractor | Extracting the password hash from the protected PDF |
| Notepad | Saving the extracted hash into a text file |
| Windows PC | Operating environment |

### 3.3 Activities Performed

**Step 1 – Downloading John the Ripper**

Downloaded John the Ripper from the official Openwall website and prepared it for use on Windows.

**Step 2 – Installing and Configuring Johnny**

Downloaded and installed Johnny GUI. After installation, I opened Johnny and configured its settings by locating and selecting the `john.exe` executable inside the John the Ripper `run` folder.

**Step 3 – Extracting the PDF Hash**

Downloaded the provided protected PDF file and uploaded it to the Online Hash Extractor to obtain its password hash.

**Step 4 – Saving the Hash**

Copied the extracted hash and pasted it into Notepad. Saved the file as `hash1.txt`, ensuring that the hash was correctly formatted.

**Step 5 – Loading the Hash into Johnny**

Opened Johnny, selected the Open Password File option, and imported the previously saved `hash1.txt` file.

**Step 6 – Starting Password Recovery**

Selected Start New Attack in Johnny and allowed John the Ripper to process the hash.

**Step 7 – Verifying the Result**

After the password was recovered, I used it to open the protected PDF file and verify that the recovery was successful.

### 3.4 Evidence Collected

**Evidence 1 – John the Ripper and Johnny Setup**

![JTR Setup](<Screenshots/JTR setup - Copy.png>)

*This screenshot documents the JTR and Johnny setup.*

**Evidence 2 – Password Recovery Result**

![JTR Result](<Screenshots/JTR-Result - Copy.png>)

*This screenshot documents the password recovery result using JTR.*

---

## 4. Project Module 2 – Password Cracking with Networkwalks Tools

### 4.1 Objective

The objective of this practical exercise was to recover the password of the provided protected PDF file using the Networkwalks Hash Calculator and Password Cracker tools through a web browser.

### 4.2 Tools Used

| Tool | Purpose |
|---|---|
| Networkwalks Hash Calculator | Extracting the PDF password hash |
| Networkwalks Password Cracker | Recovering the password from the extracted hash |
| Web Browser | Accessing the online tools |
| Windows PC | Operating environment |

### 4.3 Activities Performed

**Step 1 – Downloading the Protected PDF**

Downloaded the provided encrypted PDF file, `My Locked PDF1.pdf`, from the Networkwalks project lab page.

**Step 2 – Opening the Hash Calculator**

Accessed the Networkwalks Hash Calculator through the web browser.

Tool: https://networkwalks.com/hash-calculator/

**Step 3 – Extracting the Hash**

Uploaded the protected PDF file to the Hash Calculator. The tool processed the file and generated a PDF password hash.

**Step 4 – Copying the Hash**

Copied the complete extracted hash, ensuring that the value starting with `$pdf$` was included.

**Step 5 – Opening the Password Cracker**

Accessed the Networkwalks Password Cracker through the web browser.

Tool: https://networkwalks.com/password-cracker/

**Step 6 – Starting Password Recovery**

Pasted the extracted hash into the Password Cracker and started the password recovery process.

**Step 7 – Retrieving the Password**

Waited for the tool to complete the process and display the recovered password.

**Step 8 – Verifying the Password**

Opened the protected PDF file and entered the recovered password.

**Step 9 – Successful Completion**

Verified that the PDF opened successfully, confirming completion of the practical exercise.

### 4.4 Evidence Collected

**Evidence 3 – Networkwalks Hash Calculator**

![Networkwalks Hash Calculator](<Screenshots/Networkwalks Hash Calculator - Copy.png>)

*This screenshot shows the Networkwalks Hash Calculator used to extract the PDF hash.*

**Evidence 4 – Networkwalks Password Cracker**

![Networkwalks Password Cracker](<Screenshots/Networkwalks Password Cracker - Copy.png>)

*This screenshot documents the Networkwalks Password Cracker interface.*

**Evidence 5 – Networkwalks Password Recovery Result**

![Networkwalks Result](<Screenshots/Networkwalks result - Copy.png>)

*This screenshot documents the result obtained using the Networkwalks tools.*

---

## 5. Final PDF Verification

As part of the practical exercises, the recovered password was used to verify access to the protected PDF document.

**Evidence 6 – PDF Successfully Unlocked**

![PDF Unlocked](<Screenshots/pdf-unlocked - Copy.png>)

*This screenshot documents the successful opening of the protected PDF file.*

---

## 6. Key Learning Outcomes

Through these two practical projects, I gained experience and improved my understanding of:

- The purpose of password hashing and password recovery.
- How password hashes can be extracted from protected PDF files.
- Installing and configuring John the Ripper and Johnny.
- Loading password hashes into password recovery tools.
- Using graphical password recovery interfaces.
- Using browser-based cybersecurity tools.
- Understanding the importance of strong and complex passwords.
- Verifying password recovery results.
- Documenting practical cybersecurity exercises using screenshots.

---

## 7. Comparison of Both Projects

| Feature | Project Module 1 | Project Module 2 |
|---|---|---|
| Main Tool | John the Ripper | Networkwalks Tools |
| Interface | Johnny GUI | Web Browser |
| Hash Extraction | Online PDF Hash Extractor | Networkwalks Hash Calculator |
| Password Recovery | John the Ripper | Networkwalks Password Cracker |
| Installation | Software installation required | No additional software installation required |
| Environment | Windows | Windows and Web Browser |

Both projects demonstrated different approaches to recovering passwords from protected PDF files.

---

## 8. Conclusion

Completing these two Week 3 projects provided valuable hands-on experience with password security and recovery techniques.

In Project Module 1, I learned how to install and configure John the Ripper and Johnny, extract a PDF hash, save it in a text file, and use the tool to recover the password.

In Project Module 2, I learned how to use the Networkwalks Hash Calculator and Password Cracker to perform a similar process through browser-based tools.

These practical exercises strengthened my understanding of password protection, hashing, and the importance of creating strong passwords to protect sensitive information.

---



**#Networkwalks #Cybersecurity #EthicalHacking #PasswordSecurity #JohnTheRipper #CybersecurityLabs**
