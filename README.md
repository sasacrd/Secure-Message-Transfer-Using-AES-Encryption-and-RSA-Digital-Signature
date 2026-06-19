# Secure-Message-Transfer-Using-AES-Encryption-and-RSA-Digital-Signature
# Overview
This project implements a Secure Message System that combines Advanced Encryption Standard (AES) encryption with RSA-based digital signatures. AES is used to provide efficient and secure message confidentiality, while RSA digital signatures provide authentication, integrity verification, and non-repudiation. The system is implemented in Python and demonstrates the practical application of modern cryptographic techniques for secure communication.
# Features

AES-128 Encryption

AES Decryption

RSA Digital Signature Generation

RSA Signature Verification

SHA-256 Hashing

Secure Message Transmission
# Security Goals
AES encryption provides confidentialiy. SHA-256 hash function, and digital signature ensure integrity. And RSA digital signature also provides authentication, and non- repudiation. 
# Working Principle of the System 

Sender Side:

First all, create a plaintext message, then create a digital signature using RSA private key. After that, encrypt the plaintext using AES encryption method. And finally, send encrypt message and digital signature to the receiver side.

Receiver Side:

In the receiver, receive ciphertext and digital signature, then decrypt ciphertext using AES decryption key. After that, verify signature using RSA public key. And finally, display the original message.

# Cryptographic Algoritms Used

# Advanced Encryption Standard (AES)

Symmetric key encryption, and key size is 128-bit.

Fast and efficeient. AES provides confidentiality.

# RSA Digital Signature

Asymmetric cryptography.

Uses public and private key for creating signature and verifying it.

Provides authentication, integrity, and non-repudiation.

# SHA-256

Crptographic hash function.

Generates Fixed-Length Hash Values

Used during signature generation.
