# AetherLock

AetherLock is a secure and intuitive password manager designed to keep your credentials safe while offering a seamless user experience. Built using Electron, AetherLock ensures that your passwords remain protected using industry-standard encryption techniques and hashing algorithms.

## Features

- **Secure Password Storage**: Passwords are safely stored locally on your device using Keytar.
- **Encryption & Hashing**: Your master password is securely hashed using the SHA-256 algorithm, and all stored service passwords are encrypted with your master password using Crypto-JS.
- **Password Strength Evaluation**: AetherLock assesses the strength of your passwords and provides recommendations for improvement.
- **HIBP API Integration**: The application checks whether your passwords have been exposed in data breaches using the Have I Been Pwned (HIBP) API.
- **Password Generation**: Easily generate strong and unique passwords for your accounts.
- **Modern & Clean UI**: The user interface is designed to be clean, simple, and easy to navigate.
- **Service Details Management**: Click on a saved service name to view its details. You can also modify or delete stored credentials as needed.
- **Account Recovery**: In case you forget your master password, you can restore access using the memorable recovery phrase set during registration.
- **Windows Support**: Currently, AetherLock is available only for Windows.

## Security Measures

- **Local-Only Storage**: All your passwords are stored locally on your device, ensuring no external server has access to your data.
- **End-to-End Encryption**: Your passwords are encrypted using your master password before being saved, preventing unauthorized access.
- **Strong Hashing Algorithm**: The master password is hashed using SHA-256, making it extremely difficult to reverse-engineer.

## Installation

> **Note:** AetherLock is still in the development and testing phase. Expect potential updates and improvements in future releases.

To install AetherLock, download the latest version from the official repository or website and follow the installation instructions.

## How to Use

1. **Create an Account**: Register with a strong master password and set a memorable recovery phrase.
2. **Save Your Credentials**: Add your services and securely store their passwords.
3. **Check Password Strength**: Review the strength of your stored passwords and make improvements if necessary.
4. **Verify Password Security**: Use the built-in HIBP integration to check if your passwords have been leaked.
5. **Manage Your Data**: Click on a service name to view details, edit, or delete credentials.
6. **Recover Your Account**: If you forget your master password, restore access using your recovery phrase.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

[Your Name]

---

AetherLock is committed to providing a secure and user-friendly password management experience. Stay tuned for future updates and improvements!

