# Caesar Cipher 🔐

A simple Python implementation of the **Caesar Cipher** for educational purposes.

This project was created as part of my learning journey in programming, information security, and classical cryptography.

The main goal of this project is to understand how the Caesar Cipher works by implementing both encryption and decryption in a simple and clear way.

Anyone who is learning basic cryptography or Python can use this project as a small practical example to understand the concept more easily.

---

## Table of Contents

- [About the Project](#about-the-project)
- [How Caesar Cipher Works](#how-caesar-cipher-works)
- [Features](#features)
- [What I Learned](#what-i-learned)
- [Example](#example)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Educational Purpose](#educational-purpose)
- [Author](#author)

---

## About the Project

The Caesar Cipher is one of the simplest classical substitution ciphers.

It works by shifting each letter in a message by a specific number of positions in the alphabet.

This program allows the user to:

- Encrypt plaintext into ciphertext.
- Decrypt ciphertext back into plaintext.
- Choose a custom key.
- Use uppercase and lowercase letters.
- Keep spaces and non-alphabetic characters unchanged.

---

## How Caesar Cipher Works

Each letter has a position in the alphabet:

```
A B C D E F ... Z
0 1 2 3 4 5 ... 25  
```
For encryption, the key is added to the current position:

New Position = (Current Position + Key) % 26

For decryption, the key is subtracted:

New Position = (Current Position - Key) % 26

The % 26 operation keeps the result inside the 26 letters of the English alphabet.

For example, using a key of 3:

A → D
B → E
C → F

When the shift reaches the end of the alphabet, it starts again from the beginning:

X → A
Y → B
Z → C
Features
Caesar Cipher encryption
Caesar Cipher decryption
Custom key input
Uppercase letter support
Lowercase letter support
Spaces and symbols remain unchanged
Simple command-line interface
No external libraries required
What I Learned

Through this project, I practiced and improved my understanding of:

Classical cryptography
Substitution ciphers
Caesar Cipher encryption and decryption
Python strings
Loops
Conditional statements
User input
Character positions in the alphabet
Modulo operations
Simple command-line program design

This project helped me connect the mathematical idea behind the Caesar Cipher with an actual working Python program.

Example
Encryption
1- Encrypt
2- Decrypt

Choose: 1
Enter key: 3
Enter plaintext: Hello World

Ciphertext: Khoor Zruog
Decryption
1- Encrypt
2- Decrypt

Choose: 2
Enter key: 3
Enter ciphertext: Khoor Zruog

Plaintext: Hello World
How to Run
1. Clone the repository
git clone https://github.com/WaelALSULAMI1/caesarCipher.git
2. Open the repository folder
cd caesarCipher
3. Open the program folder
cd "lab caesarCipher"
4. Run the program
python CaesarCipher.py

If your system uses python3, run:

python3 CaesarCipher.py
Requirements

You only need:

Python 3
A terminal or Python-supported IDE

You can run the project using tools such as:

Visual Studio Code
PyCharm
IntelliJ IDEA with Python support
Windows Terminal
Command Prompt

No external Python libraries are required.

Project Structure
caesarCipher/
│
├── README.md
│
└── lab caesarCipher/
    ├── CaesarCipher.py
    ├── encrypt image.png
    └── decrypt image.png
Files

CaesarCipher.py

Contains the main Python implementation of the Caesar Cipher.

encrypt image.png

Shows an example of the encryption process.

decrypt image.png

Shows an example of the decryption process.


Educational Purpose

This project is intended for educational and learning purposes.

It was created to practice Python programming and understand the basic concepts of classical cryptography through a practical implementation.

The Caesar Cipher is useful for learning how substitution-based encryption works, but it is not secure enough for protecting real sensitive information because the number of possible keys is very small.

Students and beginners are welcome to explore the code, modify it, test different keys, and use it as a simple learning resource.

Author

Wael Alsulami


