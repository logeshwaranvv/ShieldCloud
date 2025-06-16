# 🔐 Hybrid Cryptographic System using AES and Twofish

## Overview
This project implements a hybrid cryptographic system that combines **AES** (Advanced Encryption Standard) and **Twofish** algorithms. The goal is to enhance data security for cloud environments by layering encryption and generating strong symmetric keys using **SHA-256**.

## Features
- AES + Twofish hybrid encryption
- SHA-256 based key generation
- Secure file encryption and decryption
- Stronger resistance against brute-force and cryptanalysis attacks
- Suitable for cloud storage and transmission

## Technologies Used
- Python
- PyCryptodome
- SHA-256
- AES (256-bit)
- Twofish

## How It Works
1. Input data is first encrypted using AES.
2. The AES output is then encrypted using Twofish.
3. For decryption, the reverse order is followed.
4. Encryption key is derived using SHA-256 hash from a passphrase.

## Use Cases
- Secure file storage in cloud platforms
- Confidential data transfer
- Research and educational use in cryptographic systems

## Reference
Santoso, K. I., Muin, M. A., & Mahmudi, M. A. (2020). *Implementation of AES cryptography and Twofish hybrid algorithms for cloud*.  
[DOI:10.1088/1742-6596/1517/1/012099](https://doi.org/10.1088/1742-6596/1517/1/012099)

## License
This project is licensed under the **MIT License**.
