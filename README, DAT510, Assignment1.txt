Certainly! Below is a README file that explains the Python code for implementing and assessing the Vigenère cipher and row-column transposition cipher.

---

# Cryptography Assignment: Vigenère and Row-Column Transposition Cipher

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Features](#features)
- [Assessment](#assessment)

## Introduction

This Python script implements the Vigenère cipher and row-column transposition cipher for encrypting and decrypting messages. The script also includes an assessment function for the Vigenère cipher.

## Requirements

- Python 3.x
- No additional libraries are required.

## Usage

1. Run the script.
2. Input the message you want to encrypt.
3. Input the secret key for the Vigenère cipher.
4. The script will output the encrypted and decrypted messages for both ciphers and their combinations.

## Features

### Vigenère Cipher

- **Encryption**: The function `encrypt_vig` takes a message and a key to produce an encrypted message.
- **Decryption**: The function `decrypt_vig` takes an encrypted message and a key to produce the original message.

### Row-Column Transposition Cipher

- **Encryption**: The function `encryptMessage` takes a message and encrypts it using row-column transposition.
- **Decryption**: The function `decryptMessage` takes an encrypted message and decrypts it.

### Combination of Both

- The script first encrypts a message using the Vigenère cipher and then applies row-column transposition to the ciphertext.
- It also decrypts the message by reversing the process.

### Assessment

- The function `assess_vigenere` assesses the Vigenère cipher by checking if decryption is successful, evaluating the key length, and analyzing character frequency in the ciphertext.

## Assessment

The script includes an assessment function for the Vigenère cipher that:

- Checks if decryption is successful.
- Evaluates the key length.
- Analyzes the character frequency in the ciphertext.

---