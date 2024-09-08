# Passify: Elevate Your Password Security with Advanced Strength and Leak Detection

<p align="center">
  <img src="https://github.com/kalmux1/Passify/blob/main/Assets/Tool%20Image.png" alt="Passify GUI">
</p>

## Overview

Passify is a Python-based tool designed to elevate your password security. It evaluates passwords based on length, character variety, and checks them against known leaked passwords. With a user-friendly graphical interface built using Tkinter, Passify offers an easy way to assess and improve your password strength.

## ✨ Features

- **Password Length Check**: Scores passwords based on length, with higher scores for longer passwords.
- **Character Variety Check**: Assesses the presence of uppercase letters, lowercase letters, digits, and special characters.
- **Leak Check**: Compares passwords against a database of commonly leaked passwords to ensure they are not vulnerable.
- **Repetition Check**: Identifies passwords with consecutive character repetitions that may weaken security.
- **Strength Rating**: Provides a strength rating (Very Weak, Weak, Moderate, Strong) based on an aggregated score from various checks.

## 📚 Requirements

- Python 3.x
- Tkinter (usually included with Python installations)
- `re` (Regular expressions library, usually included with Python installations)

## 🚀 Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kalmux1/Passify.git
    cd Passify
    ```

2. **Run the application**:
    ```bash
    python passify.py
    ```

3. **Ensure you have the password list file**:
   - The tool uses a file named `Passwords.txt` for checking against known leaks. Ensure this file is in the same directory as `passify.py` or adjust the `path` variable in the script accordingly.

## 🛠️ How It Works

- **Password Check**:
  - **Length Check**: Points are awarded based on password length.
  - **Character Variety Check**: Points are awarded for different types of characters (uppercase, lowercase, digits, special characters).
  - **Repetition Check**: Flags passwords with consecutive character repetitions.
  - **Leak Check**: Checks the password against a list of leaked passwords.
  - **Strength Rating**: Aggregates scores from all checks to classify password strength.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

If you have any questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/nitin-jaiswal1/) or open an issue on GitHub.

---

Enhance your password security with Passify! 🔐💪
