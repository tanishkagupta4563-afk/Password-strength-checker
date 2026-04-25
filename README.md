# Password Strength Checker

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Project Type](https://img.shields.io/badge/Type-CLI%20Tool-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A Python-based command-line tool that evaluates password strength using a scoring system and provides actionable feedback to improve security.

---

## Disclaimer

This tool is developed strictly for educational and awareness purposes only.

It is designed to help users understand password security and improve their own credentials. This tool must not be used to test, analyze, or evaluate passwords belonging to others without proper authorization.

By using this tool, you agree that:

- You will use it only for learning and personal security improvement  
- You will not engage in any unauthorized or illegal activities  
- You understand that misuse may lead to legal consequences  

The author shall not be held responsible for any misuse or damage caused by this tool.

---

## Introduction

Password Strength Checker is a simple yet effective CLI tool that analyzes passwords based on widely accepted cybersecurity practices.

Instead of failing on a single condition, the tool uses a scoring-based approach to evaluate overall password strength and provides detailed suggestions for improvement.

---

## Features

- Score-based password strength evaluation  
- Checks for:
  - Minimum length (12+ characters)
  - Uppercase letters
  - Lowercase letters
  - Digits
  - Special characters  
- Classifies passwords as:
  - Weak  
  - Medium  
  - Strong  
- Provides multiple improvement suggestions at once  
- Interactive command-line interface  

---

## Prerequisites

- Python 3

Check your version:

```bash
python --version
````

---

## Installation

```bash
git clone https://github.com/tanishkagupta4563-afk/Password-strength-checker.git
cd Password-strength-checker
```

---

## Usage

```bash
python password_checker.py
```

---

## Example Output

```
Welcome to the Password Strength Checker

Enter password: Hello123

Result: Medium Password

Suggestions:
• At least 12 characters required
• Add at least one special character
----------------------------------------
```

---

## Important Note

* This tool does not store or transmit passwords
* All processing is done locally
* Avoid using real or sensitive passwords while testing

---

## Future Enhancements

* Password entropy calculation
* Common password blacklist detection
* Hidden input using getpass
* GUI or web-based version

---

## Author

Tanishka Gupta

