# PASSWORD CRACKING PROJECT

## Project Overview

This project demonstrates practical password recovery techniques using two different approaches:

1. **John the Ripper (JTR) and Johnny GUI:** Used to extract password hashes and recover passwords from three locked PDF files.
2. **NetworkWalks Password Cracking Tools:** Used the NetworkWalks Hash Calculator and Password Cracker to recover the password of another locked PDF file.

The project provided hands-on experience with password hash extraction, password-cracking utilities, tool configuration, troubleshooting, and password verification.

All activities were performed within an authorized cybersecurity training environment for educational purposes.

---

## Project Objectives

- Understand how password-protected PDF files can be assessed for password recovery.
- Learn how to extract password hashes from PDF documents.
- Configure and use John the Ripper with Johnny GUI.
- Use hash files as input for password-cracking operations.
- Explore NetworkWalks Hash Calculator and Password Cracker.
- Recover passwords and verify the results by unlocking the original PDF files.
- Document the process and capture screenshots as evidence.

---

## Tools and Technologies Used

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password hash cracking |
| Johnny GUI | Graphical interface for John the Ripper |
| OnlineHash.com | PDF hash extraction |
| NetworkWalks Hash Calculator | Generating hashes from PDF files |
| NetworkWalks Password Cracker | Recovering passwords from hashes |
| Windows 11 Pro | Host operating system |
| Notepad | Creating and storing hash files |

---

# MODULE 1: PASSWORD CRACKING USING JOHN THE RIPPER AND JOHNNY GUI

## 1. Downloading and Installing the Tools

I started by downloading John the Ripper and Johnny GUI from their respective official websites.

After downloading the applications, I installed Johnny GUI and proceeded to configure it by locating the `john.exe` executable file within the John the Ripper installation directory.

### Configuration Challenge

During the initial configuration, I encountered difficulties locating the correct `john.exe` file required by Johnny GUI.

I downloaded John the Ripper three times, trying different sources:

- The official John the Ripper website.
- The Google Drive download link provided by NetworkWalks.

After several attempts, I resolved the issue by extracting one of the John the Ripper archives downloaded from the official website.

The extraction created an additional nested folder named:

`john-9.1.0-jumbo-1-win64`

I navigated through the extracted directory, located the `john.exe` executable, and successfully configured Johnny GUI by pointing it to the correct file.

This resolved the configuration issue and allowed me to proceed with the password-cracking exercise.

## 2. Downloading the Locked PDF Files

I downloaded three password-protected PDF documents to my Windows computer.

The documents were:

- Locked PDF 1
- Locked PDF 2
- Locked PDF 3

## 3. Extracting PDF Hashes

To prepare the documents for password cracking, I visited [OnlineHashcrack.com](https://www.onlinehashcrack.com/).

I uploaded each locked PDF individually and used the website to extract its corresponding password hash.

After extracting the hashes, I copied each hash for use with John the Ripper.

## 4. Creating Hash Files

I created a dedicated project folder on my computer to organize the files and evidence.

Inside the project folder, I created three separate text files using Notepad:

- `hash1.txt`
- `hash2.txt`
- `hash3.txt`

I pasted the corresponding extracted hash into each text file.

This ensured that each PDF hash was stored separately and could be loaded individually into Johnny GUI.

## 5. Cracking the PDF Passwords Using Johnny GUI

After preparing the hash files, I opened Johnny GUI.

I browsed and loaded each hash file into the application and initiated the password-cracking process using John the Ripper.

I repeated the process for all three PDF documents until their passwords were successfully recovered.

### Recovered Passwords

| PDF Document | Recovered Password |
|---|---|
| Locked PDF 1 | `good-luck` |
| Locked PDF 2 | `password1` |
| Locked PDF 3 | `1qaz2wsx` |

## 6. Password Verification and Flag Capture

To confirm that the recovered passwords were correct, I opened each original PDF document and entered its corresponding password.

All three PDF documents were successfully unlocked.

Each document displayed a picture and a cybersecurity flag.

### Captured Flags

| PDF Document | Flag |
|---|---|
| Locked PDF 1 | `nw{cybersecurity_flag_captured_2608` |
| Locked PDF 2 | `nw{networkwalks_persistence_jtr_270521}` |
| Locked PDF 3 | `nw{networkwalks_flag_260821_1}` |



### Screenshots and Evidence

The following screenshots document the activities performed during this module:
<img width="1332" height="722" alt="Capture locked pdf1 hash" src="https://github.com/user-attachments/assets/42d8f22f-71a4-4de6-b031-fbe9f7bd8398" />
<img width="1366" height="725" alt="Capture john the ripper executable" src="https://github.com/user-attachments/assets/8067e7b3-2cd1-491c-b77a-68796d837a1d" />
<img width="1364" height="733" alt="Capture johnny pdf1 hack" src="https://github.com/user-attachments/assets/de1d9252-fa9d-4b6b-bd57-9255f3c66c45" />
<img width="1366" height="718" alt="Capture johnny pdf2 hack" src="https://github.com/user-attachments/assets/d8059a5d-d40b-488e-8280-8ea5729596c3" />
<img width="1366" height="708" alt="Capture johnny pdf3 hack" src="https://github.com/user-attachments/assets/84da39d8-0fd2-4997-befc-f195e27fd9fb" />
<img width="1012" height="618" alt="Capture unlocked pdf1" src="https://github.com/user-attachments/assets/06daae86-4dfe-4170-aa04-d77ea0c7784f" />
<img width="1047" height="676" alt="Capture unlocked pdf2" src="https://github.com/user-attachments/assets/f5ab256a-b814-464f-8ec5-d514ae2074d8" />
<img width="1013" height="660" alt="Capture unlocked pdf3" src="https://github.com/user-attachments/assets/e24b5ab8-2f1c-4e98-8e1d-b69f458d2570" />

---

# MODULE 2: PASSWORD CRACKING USING NETWORKWALKS TOOLS

## 1. Project Overview

In this module, I used two online tools provided by NetworkWalks to recover the password of another password-protected PDF document.

The tools used were:

- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker

## 2. Downloading the Locked PDF

I started by downloading the password-protected PDF document to my computer.

## 3. Extracting the PDF Hash

I visited the NetworkWalks Hash Calculator website and uploaded the locked PDF document.

The tool generated the corresponding hash, which I copied for the next stage of the exercise.

## 4. Cracking the Hash

After obtaining the hash, I navigated to the NetworkWalks Password Cracker website.

I submitted the extracted hash to the password-cracking tool and initiated the cracking process.

The tool successfully recovered the PDF password.

### Recovered Password

`password1`

## 5. Password Verification and Flag Capture

To verify the recovered password, I opened the original PDF document and entered:

`password1`

The document was successfully unlocked and displayed the following flag:

### Captured Flag

`nw{networkwalks_flag1_jtr_270521_1}`

### Screenshots and Evidence

Screenshots were captured to document the following activities:
<img width="1314" height="655" alt="Capture NW hash generator" src="https://github.com/user-attachments/assets/37dddbef-0b57-46e2-b5bd-e13e46cf0184" />
<img width="1344" height="655" alt="Capture NW locked pdf hack" src="https://github.com/user-attachments/assets/66700a58-29d9-4710-89f9-5348bcf92b5b" />
<img width="665" height="596" alt="Capture unkocked pdf1(NW)" src="https://github.com/user-attachments/assets/b68b5c76-ffb5-4aa1-a502-b7341ea3654a" />



---

# CHALLENGES ENCOUNTERED AND SOLUTIONS

During this project, I encountered a few challenges, particularly during the initial setup of John the Ripper and Johnny GUI.

### Challenge 1: John the Ripper Configuration

I initially experienced difficulties locating the correct `john.exe` executable file required for Johnny GUI configuration.

**Solution:**

I downloaded John the Ripper multiple times from different sources, including the official website and the Google Drive resource provided by NetworkWalks.

Eventually, I extracted the official downloaded archive, navigated through the additional nested folder, located `john.exe`, and successfully configured Johnny GUI.

### Challenge 2: Managing Multiple PDF Hashes

Since I was working with three different PDF documents, I needed to ensure that their extracted hashes were properly organized.

**Solution:**

I created three separate text files (`hash1.txt`, `hash2.txt`, and `hash3.txt`) and stored each PDF's corresponding hash independently.

This made it easier to load and process each hash using Johnny GUI.

---

# SKILLS AND KNOWLEDGE ACQUIRED

Through this project, I gained practical experience in:

- Password hash extraction.
- Password cracking using John the Ripper.
- Configuring and operating Johnny GUI.
- Working with PDF password-protection mechanisms.
- Using online hash extraction tools.
- Using NetworkWalks cybersecurity utilities.
- Managing hash files and project directories.
- Troubleshooting software configuration issues.
- Password recovery and verification.
- Technical documentation and evidence collection.

---

# KEY TAKEAWAYS

This project strengthened my understanding of password security and how password-protected files can be assessed using password-cracking utilities.

I also learned the importance of correctly configuring cybersecurity tools, organizing extracted hashes, troubleshooting installation issues, and verifying recovered passwords against the original documents.

Most importantly, the project gave me practical exposure to two different password-cracking approaches and improved my confidence in using security tools within a controlled cybersecurity lab environment.

---

# CONCLUSION

Successfully completing both modules of this Password Cracking Project gave me valuable hands-on experience with John the Ripper, Johnny GUI, and NetworkWalks password-cracking utilities.

I successfully recovered the passwords of four locked PDF documents, verified each password by unlocking the original documents, and captured the flags displayed within them.

This project represents another step in my cybersecurity learning journey, particularly in understanding password security, authentication weaknesses, and the practical use of offensive security tools.

**Project Status: COMPLETED**

---

**Disclaimer:** This project was conducted for educational and authorized cybersecurity training purposes. Password-cracking techniques should only be applied to files, systems, and environments for which explicit permission has been granted.
