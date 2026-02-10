# ICT1301 – Lab 5: Secure E-mail Communication Using OpenPGP

## 📌 Lab Overview
This lab focuses on implementing **e-mail cryptography** using **OpenPGP** in Mozilla Thunderbird. The objective is to understand how encryption and digital signatures protect e-mail communication by ensuring confidentiality, integrity, authentication, and nonrepudiation.

---

## 🛠 Tools & Environment
- Mozilla Thunderbird
- Gmail Account
- OpenPGP (Built-in Thunderbird Support)
- Internet Connection

---

## 🧪 Task A: Step-by-Step Implementation

### Step 1: Install Mozilla Thunderbird
- Downloaded Mozilla Thunderbird
- Completed installation using default settings
- Successfully launched Thunderbird

---

### Step 2: Configure Gmail Account in Thunderbird
- Entered name, Gmail address, and password
- Completed 2-Step Verification authentication
- Successfully accessed Gmail inbox through Thunderbird

---

### Step 3: Configure Public/Private Key Pair
- Navigated to **Account Settings → End-to-End Encryption**
- Created a new OpenPGP key pair
- Generated and confirmed public/private keys
- Reviewed key properties such as acceptance, certifications, and structure
- Verified encryption and signing settings

---

### Step 4: Send an Encrypted & Signed E-mail
- Composed a new e-mail
- Enabled **Encrypt** and **Digitally Sign** options
- Sent the e-mail to a partner with the public key attached

---

### Step 5: Receive an Encrypted E-mail
- Opened encrypted e-mail in Thunderbird
- Verified:
  - **Good Digital Signature**
  - **Message Is Encrypted**

📸 Screenshots of configuration and encrypted communication are included.

---

## 🧠 Reflection Questions & Answers

### Web Browser vs Thunderbird View
Encrypted e-mails appear unreadable in a web browser, while Thunderbird decrypts them automatically because it supports OpenPGP encryption.

### Key Usage Summary
- E-mail encryption: Recipient’s **public key**
- Decryption: Recipient’s **private key**
- Digital signing: Sender’s **private key**
- Signature verification: Sender’s **public key**

### Security Properties Achieved
- **Confidentiality:** Public key encryption
- **Integrity:** Digital signatures
- **Authentication:** Verified sender identity
- **Nonrepudiation:** Proof of message origin using private key signatures

---

## 🏁 Conclusion
This lab successfully demonstrates the practical implementation of e-mail cryptography using OpenPGP. It highlights how encryption and digital signatures protect sensitive communication and reinforce trust in secure e-mail systems.

---

## 📚 References
1. Kearns, D., O'Gorman, J., & Aharoni, M. (2019). *The Principles of Computer Security*. McGraw-Hill.
2. Zimmermann, P. (1999). *Why I Wrote PGP*.
3. Stallings, W. (2019). *Computer Security: Principles and Practice*. Pearson.
4. Miller, R. (2017). *Hacking: The Art of Exploitation*. No Starch Press.

---

## 📎 Appendix
- Thunderbird installation screenshots
- OpenPGP key generation screenshots
- Encrypted and signed e-mail evidence
