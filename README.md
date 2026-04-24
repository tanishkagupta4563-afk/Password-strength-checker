# 🔐 Password Strength Checker

🚀 A Python-based command-line tool that evaluates password strength using a scoring system and provides actionable feedback to improve security.

---

## ⚠️ Disclaimer

This tool is developed strictly for **educational and awareness purposes only**.

It is designed to help users understand password security and improve their own credentials. This tool must not be used to test, analyze, or attempt to evaluate passwords belonging to others without proper authorization.

By using this tool, you agree that:

* You will use it only for **learning and personal security improvement**
* You will not engage in any **unauthorized or illegal activities**
* You understand that misuse may lead to legal consequences

The author shall not be held responsible for any misuse or damage caused by this tool. Use responsibly and ethically.

---

## 📖 Introduction

Password Strength Checker is a simple yet effective CLI tool that analyzes passwords based on widely accepted cybersecurity practices.

Instead of failing on a single condition, the tool uses a **scoring-based approach** to evaluate overall password strength and provides **detailed suggestions** for improvement.

Weak passwords are one of the most common causes of security breaches. This project demonstrates how structured validation can help build stronger authentication practices.

---

## ✨ Features

* Score-based password strength evaluation
* Checks for:

  * Minimum length (12+ characters)
  * Uppercase letters
  * Lowercase letters
  * Digits
  * Special characters
* Classifies passwords as:

  * ❌ Weak
  * ⚠️ Medium
  * ✅ Strong
* Provides multiple improvement suggestions at once
* Interactive command-line interface

---

##  Prerequisites

Ensure you have the following installed:

* Python 3

Check your version:

```bash id="p8x2ad"
python --version
```

---

##  Usage

1. Clone the repository:

```bash id="k3n9qp"
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
```

2. Run the script:

```bash id="m1d8zt"
python password_checker.py
```

3. Enter a password to evaluate its strength.

---

##  Example Output

```id="w8q1lo"
 Welcome to the Password Strength Checker

Enter password: Hello123

Result: ⚠️ Medium Password

Suggestions:
• At least 12 characters required
• Add at least one special character
----------------------------------------
```

---

## ⚠️ Important Note

* This tool does **not store or transmit passwords**
* All processing is done locally
* Avoid using real or sensitive passwords while testing

---

## 📌 Future Enhancements

* Password entropy calculation
* Common password blacklist detection
* Hidden input using `getpass`
* GUI or web-based version

---

##  Author

**Tanishka Gupta**

