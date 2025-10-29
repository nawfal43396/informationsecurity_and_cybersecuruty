# 🖥 Fundamentals of Computer Security

## 🔐 Identification, Authentication, and Authorization

| Concept | Description | Example |
|----------|--------------|----------|
| *Identification* | Claiming an identity | Typing username |
| *Authentication* | Proving identity | Entering password / fingerprint |
| *Authorization* | Granting access | Accessing certain files after login |

---

## 🧩 Key Principle:
> *“Authentication verifies who you are. Authorization decides what you can do.”*

---

## 🔑 Authentication Methods
- *Knowledge-based:* Passwords, PINs  
- *Possession-based:* Smart cards, OTP tokens  
- *Inherence-based:* Biometrics (fingerprints, face ID)  
- *Multifactor Authentication (MFA):* Combination of 2 or more above  
- *Single Sign-On (SSO):* One-time login across multiple systems (e.g., Google or Microsoft SSO)

---

## 🔓 Authorization Models
- *DAC (Discretionary Access Control):* Owner decides who can access (Windows permissions).  
- *MAC (Mandatory Access Control):* Based on classification levels (military systems).  
- *RBAC (Role-Based Access Control):* Permissions assigned to roles (Admin, Manager, User).  
- *ABAC (Attribute-Based Access Control):* Access rights based on conditions (time, location, user type).

---

### 🧠 Example:
An *“HR Manager”* role can view employee details, while *“Employee”* role can only view their own profile.

---

## 🛡 Best Practices
- Use strong, unique passwords.  
- Apply MFA wherever possible.  
- Review role-based permissions regularly.  
- Log all authentication and access events.








