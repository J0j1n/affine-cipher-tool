# Affine Cipher Encryption & Decryption Tool

A simple GUI-based Affine Cipher encryption and decryption tool developed using Python and Tkinter.

## Features
- Encrypt plaintext using Affine Cipher
- Decrypt ciphertext
- GUI interface using Tkinter
- Validates coprime key values
- Beginner-friendly cryptography project

## Technologies Used
- Python
- Tkinter

## How Affine Cipher Works

Encryption Formula:

E(x) = (a*x + b) mod 26

Decryption Formula:

D(x) = a⁻¹(x - b) mod 26

Where:
- a and 26 must be coprime
- b is the shift value

## How to Run

1. Install Python
2. Clone this repository
3. Run:

```bash
python affine_cipher.py
