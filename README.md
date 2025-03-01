# AetherLock

AetherLock is a secure and intuitive password manager designed to safeguard your credentials while providing a seamless user experience. Built using [Electron](https://www.electronjs.org/), AetherLock ensures that your passwords remain protected with industry-standard encryption techniques and hashing algorithms.

---

## Why Choose AetherLock?

As the number of online accounts we create continues to rise, password security has never been more important. Many users struggle with remembering complex passwords or resort to reusing the same password across multiple sites, which exposes them to significant security risks.

AetherLock offers a powerful solution by providing secure password management, encryption, and monitoring features to protect your data from unauthorized access and breaches.

---

## Key Features

### Secure Password Storage
- Your passwords are securely stored locally on your device using **Keytar**, ensuring that you retain full control over your sensitive information.

### Encryption & Hashing
- The **master password** is securely hashed using the **SHA-256** algorithm.
- All stored service passwords are **encrypted** with your master password using **Crypto-JS**, providing robust security.

### Password Strength Evaluation
- AetherLock evaluates the strength of your passwords and offers recommendations for improving security.

### Data Breach Monitoring
- Integration with the **Have I Been Pwned (HIBP) API** enables you to check if your passwords have been exposed in known data breaches.

### Password Generation
- Effortlessly generate **strong and unique passwords** tailored to your security needs.

### Modern & Clean UI
- The user interface is designed to be **user-friendly**, minimalistic, and efficient, providing quick access to all essential features.

### Service Details Management
- Click on a saved **service name** to view stored credentials. You can also **edit or delete services** as necessary.

### Account Recovery
- If you forget your **master password**, AetherLock offers a recovery process using a **memorable recovery phrase** set during registration.

### Windows Support
- AetherLock is currently available exclusively for **Windows**.

### Full Local Control
- Unlike cloud-based password managers, **all your passwords are stored locally** on your device, ensuring the highest level of privacy and security.

---

## Security Measures

AetherLock takes security seriously. Here’s how it protect your data:

### End-to-End Encryption
- Your stored passwords are **encrypted** using your **master password**, ensuring that only you can access them.

### Strong Hashing Algorithm
- The master password is **hashed using SHA-256** before being stored, preventing unauthorized access in case of data exposure.

### Offline-First Approach
- All data remains **on your device**, minimizing risks associated with online storage and cloud-based breaches.

### Data Integrity Checks
- The application performs **data integrity checks** to prevent unauthorized modifications.

---

## Installation

### Windows
1. Go to the **[Releases](https://github.com/Legionn-cs50/AetherLock/releases/latest)** page.
2. Download the installer (`Password-Tools-Setup.exe`) from the latest release.
3. Run the installer and follow the on-screen instructions.

> **Note:** AetherLock is still in the **development and testing phase**. As a result, the installation may trigger a security warning due to the lack of digital signing. This is a known issue and can be bypassed by proceeding with the installation.

---

## How to Use

1. **Create an Account**: Register with a **strong master password** and set a **memorable recovery phrase**.
2. **Save Your Credentials**: Add your accounts and securely store their login details.
3. **Check Password Strength**: Review your stored passwords' **security levels** and enhance them if necessary.
4. **Monitor Data Breaches**: Use the integrated **HIBP API** to check if your passwords have been compromised.
5. **Manage Your Credentials**: Click on a **service name** to view, edit, or delete stored passwords.
6. **Account Recovery**: If you forget your **master password**, restore access using your **recovery phrase**.

---

## License

This project is licensed under the **Apache-2.0 license**. See the [LICENSE](https://github.com/Legionn-cs50/AetherLock?tab=Apache-2.0-1-ov-file#) file for more details.

---

## Author

Legionn

---

AetherLock is committed to providing a **secure and user-friendly** password management experience. Stay tuned for future updates and improvements!

---

Let me know if there’s anything else you’d like to adjust!

