# 🔐 Random Password Generator

A simple and secure random password generator written in Python. It uses the `secrets` module to ensure cryptographic security, making it ideal for generating passwords that are difficult to guess or brute-force.

## 🧰 Features

- Generates a 10-character long password by default
- Includes:
  - Uppercase and lowercase letters
  - Digits (0-9)
  - Special characters (e.g. `!@#$%^&*`)
- Uses `secrets` for high-level security over `random`

## 📦 Requirements

- Python 3.6+

The script uses only standard libraries:
```python
import secrets
import string
