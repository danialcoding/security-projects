# Introduction

Welcome to the GitHub repository for the Homework 1 assignment of the "Basics of Security of Information" course at Amirkabir University of Technology. This repository is dedicated to the practical implementation and exploration of the Data Encryption Standard (DES), a seminal symmetric-key algorithm that has shaped the landscape of digital security. DES is historically significant, having been one of the first encryption algorithms widely adopted by governments and industries for secure data encryption.

In this repository, you will find a Jupyter Notebook that walks through each step of the DES encryption processes. This practical approach not only helps in understanding the theoretical aspects of the algorithm but also provides hands-on experience in implementing cryptographic algorithms using Python.

# Overview of DES

DES is a symmetric-key algorithm for the encryption of electronic data. It uses a 64-bit block size and a key size of 56 bits, though the key is initially presented as 64 bits, with 8 bits used for parity checking. The DES algorithm, despite being considered less secure today due to advancements in computational power, serves as an excellent educational tool for students beginning their journey in the field of cryptography. By dissecting its mechanisms, students can gain insights into more complex encryption techniques and better understand the principles that underpin modern cryptographic methods.

Key Stages of the Algorithm:

  - Initial Permutation (IP): The data block is initially permuted using the IP table.
  - Key Generation: A 56-bit key is generated from the original 64 bits by ignoring every 8th bit. This key undergoes 16 transformations to generate 16 subkeys, one for each round of the DES process.
  - Round Function: Each round involves expanding the 32-bit half-block to 48 bits using the expansion permutation (EP), applying the XOR function with the round key, and then compressing it back to 32 bits using the S-boxes followed by a P-box permutation.
  - Final Permutation: After 16 rounds, a final permutation is performed on the combined output using the Final Permutation (FP) table, reversing the initial permutation to produce the final encrypted data.

