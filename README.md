# Secure Image Encryption Tool

A Python-based GUI application that demonstrates image encryption and decryption using the XOR operation.

Built with Python, Pillow (PIL), NumPy, and Tkinter, this project allows users to upload an image, encrypt it into unreadable pixel data, and later restore it using the same XOR-based process.

---

# Why This Project Exists

Encryption is one of the fundamental concepts in cybersecurity.

While most people hear terms like AES, RSA, and cryptography, it can be difficult to understand what encryption actually does to data.

This project demonstrates the concept visually by transforming an image into encrypted pixel data and restoring it back to its original form through decryption.

The goal is to provide a simple and practical introduction to how encryption protects information.

---

# Features

- Upload images through a graphical interface
- Encrypt images using XOR operations
- Decrypt encrypted images back to their original form
- Automatic output saving
- Error handling and status notifications
- Simple and beginner-friendly interface

---

# Technologies Used

- Python
- Tkinter
- Pillow (PIL)
- NumPy

---

# Requirements

Install the required libraries:

pip install pillow numpy

---

# How to Run

Run the script:

python image_encryption.py

1. Upload an image
2. Click Encrypt
3. View the encrypted output
4. Click Decrypt to restore the image
5. Use Clear to reset the application

---

# How XOR Encryption Works

XOR (Exclusive OR) is a bitwise operation commonly used in cryptography.

One interesting property of XOR is:

A XOR B XOR B = A

This means that data encrypted with a key can be restored by applying the same key again.

Example:

5 XOR 10 = 15

15 XOR 10 = 5

The original value is recovered because the same key is applied twice.

---

# Demonstration

Original Image:
(Insert Screenshot)

Encrypted Image:
(Insert Screenshot)

Decrypted Image:
(Insert Screenshot)

---

# Cybersecurity Relevance

This project introduces learners to:

- Cryptography fundamentals
- XOR operations
- Data confidentiality
- Image processing
- Encryption and decryption workflows

While modern systems use significantly stronger algorithms, XOR encryption is an excellent way to understand the core logic behind how encrypted data can be transformed and later restored.

---

# Disclaimer

This project was created for educational purposes only.

The XOR technique used here is intended for learning and demonstration. Modern security systems rely on stronger encryption standards such as AES and RSA for real-world protection.

IMAGE DESCRIPTION:

1) The introductory screen to upload an image:
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/f94f3016-3c6c-4cb7-bc0b-1354117ea6e5" />

2) On uploading an image:
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/4bd6277c-9337-4f86-b875-aab667c18351" />

3) By pressing the decrypt button we are provided with an error.
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/ca922368-b92b-4fb0-ba97-2d93cb17314d" />

4) On encrypting the image:
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/dfab2c0d-f915-4b27-aad9-3d105697ed1f" />
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/ff5f4c9a-4b67-42a9-a970-ebbfdcf28c7a" />

5) On decrypting the encrypted image:
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/ce8e3938-8be5-46af-84f8-d813168072d3" />
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/6974f424-065a-488c-b550-4b4b49e0d5dc" />

6) By clearing the page, previously input data is erased.
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/6d55a843-d1e7-465b-b001-dad5e3e85142" />
