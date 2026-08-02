# Labs Completed

---
  
# TryHackMe – OWASP Top 10 2025: Insecure Data Handling

## Room Overview
This room covers **Insecure Data Handling**, including sensitive data exposure, improper storage, and insecure transmission, as defined in the OWASP Top 10:2025.

The room is beginner-friendly and focuses on understanding concepts and applying them through hands-on challenges.

---

## OWASP Categories Covered
- **A02: Cryptographic Failures**
- **A05: Sensitive Data Exposure**
- **A08: Insecure Deserialization / Data Manipulation**

---

## Key Learnings

<details>
<summary>🔐 A02 – Cryptographic Failures</summary>

**What I learned:**
- Weak or outdated encryption algorithms are easily broken  
- Secrets should never be hardcoded or exposed  
- Proper key management is critical  

**Security takeaway:**
- Always use strong, modern cryptography  
- Protect keys and secrets  
- Encrypt sensitive data at rest and in transit
</details>

<details>
<summary>💾 A05 – Sensitive Data Exposure</summary>

**What I learned:**
- Sensitive information can leak through logs, URLs, or error messages  
- Improper masking or storage increases risk  
- GDPR and privacy regulations enforce proper handling  

**Best practices learned:**
- Store passwords hashed with strong algorithms (e.g., bcrypt, Argon2)  
- Mask or redact sensitive information in logs and error messages  
- Enforce TLS/HTTPS for all data transmission
</details>

<details>
<summary>🛠 A08 – Insecure Deserialization / Data Manipulation</summary>

**What I learned:**
- Deserializing untrusted data can lead to remote code execution or data corruption  
- Input validation is crucial  
- Even seemingly safe formats like JSON can be exploited  

**Security best practices:**
- Avoid deserializing untrusted inputs  
- Validate and sanitize all incoming data  
- Monitor and log deserialization attempts
</details>

---

## Practical Skills Gained
- Identifying insecure storage or transmission of sensitive data  
- Understanding attack vectors for cryptographic weaknesses  
- Recognizing insecure data processing and deserialization issues  
- Thinking like both attacker and defender  

---

## Room Completion Status
✅ Room completed  
✅ Challenges solved  
✅ Concepts understood and documented  

---

## How This Helps Bug Bounty
- Helps identify sensitive data leaks and cryptographic weaknesses  
- Improves testing methodology for encryption, storage, and transmission  
- Enhances reporting quality by mapping findings to OWASP Top 10  
- Strengthens understanding of data-handling vulnerabilities  

---

## Next Steps
- Continue with **Secure Coding Practices** room  
- Apply Insecure Data Handling concepts during recon & testing  
- Map findings to OWASP Top 10 in future reports

  ---
  ---
  
# OWASP BWA Hands-On Labs

## 🧪 Targeted Exercises
* **Lab Target:** bWAPP (Buggy Web Application)
* **Objective:** Intercept and examine parameter inputs across legacy authentication and search forms.
* **Observation:** Logged HTTP transaction details, payload formats, and cookie configurations to establish a baseline for analyzing vulnerability responses.

---
---

## PortSwigger Academy

### Theory

- Internet
- Client vs Server
- Browser vs Server

Status: ✅ Completed

### Practical

- Installed Burp Suite
- Installed Firefox
- Explored Browser Developer Tools
- Inspected Network tab on multiple websites

Status: ✅ Completed
