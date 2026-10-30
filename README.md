# Encrypted File Transfer & Secure File Storage

## Overview
This is a Python-based cybersecurity project that demonstrates secure file transfer and storage using AES-256-GCM encryption and HMAC-SHA256 integrity verification.

## Objectives
- Secure file transfer using encryption.
- Divide large files into smaller chunks.
- Verify file integrity using HMAC.
- Store encrypted files on a server.
- Understand MITM attacks and key management.

## Features
- AES-256-GCM encryption and decryption.
- File chunking (1 MB chunks).
- HMAC-SHA256 integrity verification.
- Encrypted file storage.
- File upload and download.
- Data tampering detection.

## Technologies Used
- Python
- Flask
- Cryptography
- Requests
- Google Colab

## How It Works
1. Generate AES and HMAC keys.
2. Divide the file into smaller chunks.
3. Encrypt each chunk using AES-256-GCM.
4. Generate an HMAC for integrity verification.
5. Transfer encrypted chunks to the local server.
6. Store encrypted data on the server.
7. Verify HMAC before decryption.
8. Decrypt and reconstruct the original file.

## Testing
The project includes tests for:
- File upload and download.
- Integrity verification.
- Modified data detection.
- Comparison of original and downloaded files.

## Security Considerations
AES encryption protects file confidentiality, while HMAC helps detect unauthorized data modification.

The current Google Colab implementation uses local HTTP communication. It does not implement HTTPS/TLS, user authentication, or persistent secure key storage.

## Limitations
- Educational prototype only.
- Local server demonstration.
- No HTTPS/TLS implementation.
- No user authentication.
- Encryption keys are stored in memory.

## Conclusion
This project demonstrates important cybersecurity concepts, including encryption, secure file handling, data integrity, and basic threat awareness using Python.<img width="1032" height="628" alt="image" src="https://github.com/user-attachments/assets/a8df34b0-79a8-4230-889d-f5922e1ad525" />
