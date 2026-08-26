# Encryption Techniques 

## Learning Objectives
- Understand cryptography basics
- Differentiate between symmetric and asymmetric encryption
- Learn hashing and digital signature concepts
  
## Cryptography
Cryptography is a technique of securing information and communications using codes ## Symmetric Encryption
- Uses one key for both encryption and decryption. 
- Fast, suitable for bulk data encryption.

## Asymmetric Encryption
- Uses two keys: Public Key (for encryption) & Private Key (for decryption).
- Used for secure key exchange and digital communication.
  
## Hashing
- Converts data into a fixed-length string.
- One-way process - cannot be reversed.
- Used for password storage and integrity checking.
- Common Algorithms: SHA-256, MD5 (deprecated)

## Digital Signatures and Certificates
- Ensure authenticity and non-repudlatilon. 
- A digital signature uses private key to sign data and publlc key to verify.
- Certificates (x.509) aro issued by Certificato Authorities (CAs) for trust vorification (used in HTTPs).

## Example:
When visiting https://bank.com
- browser verifies certificate signed by CA to ensure authenticity.
