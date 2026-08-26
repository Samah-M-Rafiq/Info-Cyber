# Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relatesecurity principles to real-world cyberincidents.
# CIA Triad
- The CIA Triad forms the foundation of information security.
- ⁃ Each element ensures that information remains safe and trustworthy.

 |Element            |Description                                                  |Example                                              |
 |-------------------|-------------------------------------------------------------|-----------------------------------------------------|
 |**Confidentiality**| Ensure data is accessible only to authorised users.         |Encrypting file, using password,access control lists.|
 |**Integrity**      | Ensures data is accurate, consistent, and not tempered with.| Using hashing, digital signature, checksums.        |
 |**Availability**   | Ensures systems and date are avalable when needed.          | Redundant servers, backups, DDoS protection.        |

![download](https://github.com/user-attachments/assets/79b5b55d-f0bb-45cb-bffe-5f2aa33f336c)


# Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key - too much focus on one (e.g, availability) can weaken another (e.g., confidentiality).

# Examples
- **Confidentiality Violation:** Unauthorized access to customer data (e.g., Facebook-Cambridge Analytica case).
- **Integrity Violation:** Tampered medical data in hospitals leading to misdiagnosis.
- **Availability Violation:** DDoS attack on banking websites preventing service access.

# Risk, Privacy, and Accountability
# Risk
-  **Definition:** Probability of a threat exploiting a vulnerability to cause harm.
## Components:
- **Threat** -> something that can cause damage.
- **Vulnerability** -> weakness that can be exploited
- **Impact** -> damage if threat is realized

## Formula: 
**Risk = Threat x Vulnerability x Impact** 
## Example: 
- **Threat:** Phishing 
- **Vulnerability:** Employee lack of awareness 
- **Impact:** Credential theft, financial loss 

<img width="377" height="354" alt="Risk-graphic" src="https://github.com/user-attachments/assets/462b5cb0-f7c6-44db-b26c-0be7d6e3fd09" />


# Privacy 
- Protecting personel and sensitive information of individuals. 
- Governed by laws like GDPR, DPDP Act (India), HIPAA 

![OIP](https://github.com/user-attachments/assets/73865b0c-cb51-4da7-a988-f0c5a018a389)
## Key Practices:
- Data minimization 
- Informed consent 
- Data anonymization
  
Example: A healthcare app must not share user health data without consent.

# Accountability
Ensuring every action in an IT system can be traced back to an individual.
## Achieved through:
- Logging & auditing
- User access tracking
- Non-repudiation mechanisms
  
Example: Audit logs in firewalls to trace malicious user actions. 
## Real-World Case Studies

|Case                     |Description                                      |Violated Principle               |
|-------------------------|-------------------------------------------------|---------------------------------|
|**WannaCry (2017)**      | Ransomeware disabled hospital systems worldwide | Availability                    |
|**Equifox Breach (2017)**| Personal data of 143M users leaked              | Confidentiality & integrity     |
|**Twitter Hack (2020)**  | Insider access to admin tool                    | Confidentiality & accountability|
