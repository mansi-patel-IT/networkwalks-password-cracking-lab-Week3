# networkwalks-password-cracking-lab-Week3
Practical cybersecurity lab covering PDF password recovery using John the Ripper (JTR), Johnny GUI and Networkwalks password-cracking tools.
# 🔐 PDF Hash Analysis & Password Security Lab

---

## 📌 About This Project

Cybersecurity is not just about understanding concepts; it is also about learning how security tools work in practical situations.

As part of my **Cybersecurity & Ethical Hacking training with Networkwalks**, I completed two hands-on project modules focused on PDF hash extraction and password security assessment.

During these exercises, I explored how password-protected PDF files can be examined using different password auditing tools.

I worked with two approaches:

- **PM1:** John the Ripper (JTR) and Johnny GUI.
- **PM2:** Networkwalks Hash Calculator and Password Cracker.

I performed the practical exercises, extracted PDF hashes, carried out dictionary-based password recovery tests and verified the results using the protected PDF files.

This repository documents my practical workflow, tools used, captured flags and key learning outcomes.

## 🎯 Project Objectives

- Understand the concept of PDF hash extraction.
- Explore password auditing using John the Ripper.
- Learn how Johnny GUI works with John the Ripper.
- Understand dictionary-based password testing.
- Explore Networkwalks Hash Calculator and Password Cracker.
- Understand the relationship between password strength and file security.
- Verify password recovery results in an authorized lab environment.

---

## 🧪 Project Module 1 – John the Ripper (JTR)

### Tools Used

- John the Ripper
- Johnny GUI
- PDF hash extraction utility
- Notepad
- Windows operating system

### Practical Workflow

1. Downloaded John the Ripper from its official distribution source.
2. Downloaded and installed Johnny GUI.
3. Opened Johnny and configured its settings by locating the `john.exe` executable.
4. Extracted the hash from the password-protected PDF using the PDF hash extraction utility.
5. Copied the extracted hash into Notepad.
6. Saved the hash as a text file (`hash1.txt`).
7. Loaded the hash file into Johnny.
8. Started the password recovery process.
9. Examined the recovered result.
10. Verified the result by opening the protected PDF.

### What I Understood

This module helped me understand how a password auditing tool processes extracted hash information and how a graphical interface can simplify the configuration and use of John the Ripper.

---

## 🌐 Project Module 2 – Networkwalks Hash Analysis Tools

### Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web browser
- Windows operating system

### Practical Workflow

1. Obtained the password-protected PDF provided for the lab.
2. Opened the Networkwalks Hash Calculator.
3. Uploaded the protected PDF.
4. Extracted the PDF hash beginning with `$pdf$`.
5. Copied the complete hash value.
6. Opened the Networkwalks Password Cracker.
7. Pasted the extracted hash into the tool.
8. Started the dictionary-based password recovery process.
9. Observed the recovery result.
10. Verified the recovered password by opening the protected PDF.

### What I Understood

This module helped me understand how hash extraction and password recovery are connected.

I also got practical exposure to browser-based security tools without needing to install an additional password auditing application.

---

## 🏆 Practical Achievements – Three Captured Flags

Successfully completed the practical flag-capture activities and collected three Networkwalks flags.

| Achievement               | Flag                                      |
| ------------------------- | ----------------------------------------- |
| Flag 01 – Networkwalks    | `nw{networkwalks_flag_260821_1}`          |
| Flag 02 – JTR Persistence | `nw{networkwalks_persistence_jtr_270521}` |
| Flag 03 – Cybersecurity   | `nw{cybersecurity_flag_captured_2608}`    |

### Flag Capture Gallery


**01 – Networkwalks Flag**

<img width="660" height="810" alt="Screenshot1" src="https://github.com/user-attachments/assets/992bd9cc-3c71-458a-ae1d-ca3acc9e7a6e" />


**02 – JTR Persistence Flag**

<img width="661" height="812" alt="Screenshot2" src="https://github.com/user-attachments/assets/2c65a94f-0670-4cef-987b-ccdf8fea63f2" />


**03 – Cybersecurity Flag**

<img width="1015" height="298" alt="Screenshot3" src="https://github.com/user-attachments/assets/ec7f3a2e-06cf-4b41-8373-eb5f255e3b99" />


---

## 🛠️ Tools & Technologies

| Tool                          | Purpose                            |
| ----------------------------- | ---------------------------------- |
| John the Ripper               | Password auditing                  |
| Johnny GUI                    | Graphical interface for JTR        |
| Networkwalks Hash Calculator  | PDF hash extraction                |
| Networkwalks Password Cracker | Dictionary-based password recovery |
| Notepad                       | Saving extracted hash information  |
| Windows                       | Practical environment              |

---

## 📚 Key Learning Outcomes

Through these practical exercises, I gained a better understanding of:

- **Hash Extraction:** How hash information can be obtained from protected PDF files.
- **Password Auditing:** How security tools evaluate password strength.
- **John the Ripper:** How JTR works with extracted hash information.
- **Graphical Configuration:** How Johnny makes JTR easier to configure.
- **Dictionary-Based Testing:** How candidate passwords are tested against extracted hash information.
- **Password Security:** Why commonly used and weak passwords can create security risks.
- **Practical Verification:** Why it is important to verify a recovered password rather than relying only on a tool's output.

### 💡 My Key Takeaway

One of the most interesting things I learned was how the strength of a password affects the security of a protected document.

Before these exercises, I understood password security mainly from a theoretical perspective. Working with actual tools helped me connect the concepts with practical workflows.

I also learned that understanding hash extraction, tool configuration and result verification is just as important as knowing how to operate the tools.

For me, these exercises were a valuable step towards developing a stronger foundation in cybersecurity and ethical hacking.

---

## 🔒 Ethical Use & Disclaimer

This repository is created strictly for educational purposes and documents authorized cybersecurity lab exercises.

Password auditing and recovery tools should only be used on files, systems and data for which appropriate permission has been granted.

The purpose of this project is to understand password security, identify weaknesses in controlled environments and promote stronger security practices.

---


## 👩‍💻 Author

**Mansi Patel**

Cybersecurity Learner | Ethical Hacking | Information Technology

🔗 **LinkedIn:** https://www.linkedin.com/in/mansi-patel-8a2715346/

---

\<p align="center">   \<strong>Learning • Practicing • Exploring Cybersecurity\</strong>   \<br>   🚀 Every practical exercise is another step forward! \</p>
