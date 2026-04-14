# Secure-Data-Authentication
Secure data authentication using cryptography
# 🛡️ SECURE_AUTH // ENTERPRISE_SECURITY_V2

A comprehensive, browser-based cybersecurity and data integrity suite designed for advanced cryptographic operations. This platform demonstrates the practical application of modern security protocols, from asymmetric digital signatures to hierarchical data verification.

---

## 🚀 core_modules

### 🔐 1. Multi-Factor Authentication
A terminal-style gateway utilizing **Firebase Auth** logic (simulated) with OTP verification and reCAPTCHA protection to ensure only authorized operators gain system access.

### ⛓️ 2. Blockchain Ledger & Merkle Tree
* **Immutable Ledger:** Every cryptographic action is recorded in a sequential, tamper-evident local blockchain.
* **Merkle Visualizer:** Implements hierarchical hashing to generate a single **Merkle Root**, allowing for instant verification of massive datasets.


### 🔒 3. The Vault (AES-256 Encryption)
Utilizes the **Web Crypto API** to provide military-grade **AES-256-GCM** encryption. Users can lock files with a master passkey, transforming data into unreadable cipher-text blobs that can only be decrypted via the system.

### 🕵️ 4. Image Steganography
Hides secret messages within the **Least Significant Bits (LSB)** of image pixels. This module allows for covert communication where the carrier image remains visually identical to the original.


### ✍️ 5. Digital Signatures & Integrity
* **Asymmetric Signing:** Generates RSA/ECDSA key pairs to sign documents.
* **Hash Generator:** Supports SHA-256, SHA-384, and SHA-512 algorithms.
* **Integrity Verifier:** Compares original hashes against current files to detect "Man-in-the-Middle" or unauthorized edits.

### 📋 6. Security Audit Log
Generates a formal system activity report. Features an **Export to CSV** function for professional auditing and compliance record-keeping.

---

## 🛠️ tech_stack
* **Frontend:** HTML5, CSS3 (Modern Terminal Aesthetic), JavaScript (ES6+)
* **Cryptography:** Web Crypto API, SubtleCrypto
* **Storage:** LocalStorage API (Persistent Client-Side Ledger)
* **Icons/UI:** Custom CSS animations and Glitch-effect typography

---

## 🏁 getting_started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sumitbelgaonkar06-byte/Secure-Data-Authentication.git](https://github.com/sumitbelgaonkar06-byte/Secure-Data-Authentication.git)
