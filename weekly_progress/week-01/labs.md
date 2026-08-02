# Labs Completed

# TryHackMe – OWASP Top 10 2025: IAAA Failures

## Room Overview
This room covers Identity, Authentication, Authorisation, and Accountability (IAAA)
failures as defined in the OWASP Top 10:2025.

The room is beginner-friendly and focuses on understanding concepts
and applying them through hands-on challenges.

## OWASP Categories Covered
- A01: Broken Access Control
- A07: Authentication Failures
- A09: Logging & Alerting Failures

---

## Key Learnings

### 🔐 A01 – Broken Access Control
**What I learned:**
- Access control must always be enforced server-side
- Client-side restrictions are not security controls
- Every request must be validated for authorization

**Security takeaway:**
> Never trust the client. Validate permissions on every request.

---

### 🔑 A07 – Authentication Failures
**What I learned:**
- Weak authentication mechanisms lead to account takeover
- Brute-force protection is essential
- Session handling mistakes increase risk

**Best practices learned:**
- Enforce unique indexes on canonical usernames/emails
- Rate-limit login attempts / lock accounts
- Rotate sessions after password or privilege changes

---

### 📊 A09 – Logging & Alerting Failures
**What I learned:**
- Lack of logging hides active attacks
- Alerts are as important as logs
- Logs should be centralized and protected

**Security best practices:**
- Log full authentication lifecycle (success/failure)
- Log password, 2FA, role, and admin changes
- Alert on anomalies such as:
  - Brute-force attacks
  - Privilege escalation
  - Suspicious login patterns

---

## Practical Skills Gained
- Identifying access control weaknesses
- Understanding authentication attack surfaces
- Recognizing poor logging and monitoring setups
- Thinking like both attacker and defender

---

## Room Completion Status
- ✅ Room completed
- ✅ Challenges solved
- ✅ Concepts understood and documented

---

## How This Helps Bug Bounty
- Helps identify IDOR and privilege escalation issues
- Improves authentication testing methodology
- Enhances reporting quality by understanding impact
- Strengthens OWASP-based vulnerability mapping

---

## Next Steps
- Continue with **Application Design Flaws** room
- Apply IAAA concepts during recon & testing
- Map findings to OWASP Top 10 in future reports

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

