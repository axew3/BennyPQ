# BennyPQ (BPQ)

**BennyPQ** is an ultra-lightweight, single-file HTML standalone tool designed to generate Post-Quantum Cryptography (PQC) key pairs, perform local file/s encryption/decryption, and safely obfuscate Private Keys using the **Cincia Keys Vault** mechanism.

Completely client-side and auditable, BennyPQ guarantees absolute data sovereignty by design—zero dependencies, zero tracking, and zero server interaction required for core cryptographic tasks. [How to](https://www.axew3.com/w3/bennypq/)

---

## 🔒 Cryptographic Standards

BennyPQ implements state-of-the-art, future-proof protocols aligned with recent NIST post-quantum standardization:

*   **ML-KEM 1024**: Secure post-quantum key encapsulation mechanism for bulletproof key exchanges.
*   **ML-DSA 87**: Digital signature algorithm for absolute sender identity verification and tamper protection.
*   **AES-GCM-256**: High-speed, authenticated symmetric bulk encryption ensuring data integrity.
*   **SHA-512**: Robust cryptographic hashing for underlying file verification.

---

## 🚀 Key Features

*   **Zero Dependencies**: A portable, standalone `BPQ.html` file running directly inside any modern web browser.
*   **Cincia Keys Vault**: A zero-knowledge obfuscation engine. Instead of storing private keys in plain or standard encrypted text, Cincia isolates the 2 correct key fragments out of 97 fakes, reverts modified bytes in secure memory, and automatically loads the rebuilt KEM or DSA private key right into the interface.
*   **Fully Auditable**: Transparent client-side execution allows immediate source code inspection before managing sensitive keys.
*   **Cross-Compatible**: Shares a synchronized file format infrastructure with the [w3myPQ WordPress Plugin](https://wordpress.org/plugins/w3mypq/).

---

## 🛠️ Usage & Workflow

1.  **Download & Launch**: Open `BPQ.html` in your browser.
2.  **Generate Keys**: Create your quantum-resistant ML-KEM and ML-DSA key pairs.
3.  **Obfuscate with Cincia**: Pass your private key through the Cincia Vault screen to safely hide its footprint.
4.  **Encrypt / Decrypt**: Secure your data using local AEAD encryption layers or verify digital signatures effortlessly.
5.  [How to and download](https://www.axew3.com/w3/bennypq/)

---

## 📝 Project Status & Development Note

*BennyPQ is essentially an optimized standalone excerpt of the **[w3myPQ WordPress Plugin](https://wordpress.org/plugins/w3mypq/)** core engine. Feel free to inspect, contribute, or report issues!*

---

## 🤝 Credits

Powered by a compiled version of the authoritative [Noble post-quantum](https://github.com/paulmillr/noble-post-quantum) cryptography libraries for ML-KEM and ML-DSA.

Developed by **axew3** — [axew3.com](https://axew3.com)

MIT License

Copyright (c) 2026 axew3

🔐❤️ Built for absolute Privacy – [Your privacy matters: Support the tools that protect it.](http://www.paypal.me/alessionanni/)
