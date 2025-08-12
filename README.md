# CS-305-artemis-financial-secure-software

# CS 305 Module Eight Journal – Artemis Financial Secure Software Practices

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Security](https://img.shields.io/badge/Security-AES--256--GCM%20%2B%20HMAC--SHA256-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)



---

## 🏢 Client & Requirements  
Artemis Financial is a financial services company that handles sensitive client data and needed to improve the security of its web application. They requested:
- A vulnerability assessment  
- Secure code updates following industry best practices  
- Protection against breaches, compliance risks, and reputation damage  

---

## ✅ What I Did Well  
I identified and fixed vulnerabilities in:
- **Encryption:** Implemented AES-256-GCM for confidentiality and HMAC-SHA256 for integrity  
- **Input Validation:** Sanitized and validated all user inputs  
- **Secure Communications:** Enforced HTTPS/TLS with a self-signed certificate  
- **Key Management:** Stored secrets securely in Java Keystore or environment variables  

Secure coding protects sensitive data, builds trust, and ensures compliance — all essential to a company’s long-term success.

---

## ⚙️ Challenges & Insights  
The most challenging aspect was **configuring TLS** with a self-signed certificate in Spring Boot and ensuring secure keystore handling. This deepened my understanding of certificate management and transport-layer security.

---

## 🔒 Layers of Security Implemented  
- Enforced **HTTPS/TLS** for encrypted communications  
- Used **AES-256-GCM** for encryption and **HMAC-SHA256** for data integrity  
- Secured keys in a **Java Keystore**  
- Validated all inputs to prevent injection attacks  
- Scanned dependencies with **OWASP Dependency-Check**  

---

## 🧪 Functionality & Security Verification  
- Functional testing of all endpoints  
- TLS handshake and encryption verification  
- Input validation and error handling tests  
- OWASP scans to ensure no new vulnerabilities  

---

## 🛠 Tools & Best Practices  
- **Java Keystore** for secure key storage  
- **OWASP Dependency-Check** for vulnerability scanning  
- **SecureRandom** for cryptographic randomness  
- **Spring Boot TLS** configuration for HTTPS  
- **Least privilege** server access controls  

---

## 📂 Portfolio Value  
This project demonstrates:
- Vulnerability assessment skills  
- Secure code refactoring  
- Compliance with **NIST** cryptographic standards  
- End-to-end security testing  

> Employers will see that I can deliver secure, functional software that meets industry best practices.

---

**Author:** Lamberto Nunez  
**Course:** CS 305 – Secure Coding
