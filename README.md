# ElGamal Cryptosystem

## Overview
This repository contains a Jupyter Notebook implementing:
1. **ElGamal Cryptosystem**: Key generation, encryption, and decryption.
2. **Prime Number Computations**: Finding large prime numbers using the Sieve of Eratosthenes.

Each section includes detailed explanations and Python implementations to support theoretical concepts with concrete examples.

## Contents
- `elgamal.ipynb`: Implementation of the ElGamal cryptosystem.
- `number_theory.ipynb`: Analysis of cyclic groups and even-order elements.
- `prime_numbers.ipynb`: Prime number computations with the Sieve of Eratosthenes.
- `README.md`: This documentation file.

## Installation & Usage
### Prerequisites
Ensure you have Python and Jupyter Notebook installed:
```bash
pip install jupyter numpy sympy
```

### Running the Notebook
1. Clone the repository:
```bash
git clone https://github.com/chrishounwnu/rsa_Elgmal_ecosystem_Pohlig_Hellman_Cryptography.git
```
2. Navigate to the project directory:
```bash
cd rsa_Elgmal_ecosystem_Pohlig_Hellman_Cryptography
```
3. Start Jupyter Notebook:
```bash
jupyter notebook
```
4. Open the relevant `.ipynb` file and run the cells.

## Project Details
### 1. ElGamal Cryptosystem
- Generates a large prime `p` of at least 700 digits.
- Computes private and public keys.
- Encrypts and decrypts messages.
- Uses Python for number generation and modular arithmetic.

### 2. Prime Number Computations
- Finds the `(5000000 + n)`-th prime using the Sieve of Eratosthenes.
- Counts prime numbers between `2^25` and `2^26`.
- Uses an optimized approach for large-scale prime computations.

## Example Outputs
- **ElGamal Encryption & Decryption**:
  - Public Key: `(g, p, pk)`
  - Private Key: `sk`
  - Ciphertext: `(c1, c2)`
  - Decrypted Message: `Original text`
- **Number Theory**:
  - Number of even-order elements for different `p, n` values.
- **Prime Computations**:
  - `5000000 + n`-th prime found.
  - Prime count in the given range.

## License
This project is open-source under the MIT License.

## Author
Christophe HOUNWANOU - [GitHub Profile](https://github.com/chrishounwnu)

