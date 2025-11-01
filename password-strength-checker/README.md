# Password Strength Checker

A simple GUI application built with Python and Tkinter that checks the strength of passwords.

## Features

- Real-time password strength evaluation
- Visual feedback with colors and emojis
- Password visibility toggle
- Checks for:
  - Minimum length (8 characters)
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters
  - Common weak passwords

## Requirements

- Python 3.x
- Tkinter (usually comes with Python)
- re (Python standard library)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/password-strength-checker.git
cd password-strength-checker
```

2. Run the application:
```bash
python password_checker_gui.py
```

## Usage

1. Enter your password in the input field
2. Click the eye icon to toggle password visibility
3. Click "Check Strength" to evaluate the password
4. The result will be displayed with color-coded feedback:
   - Red: Weak password
   - Orange: Moderate password
   - Green: Strong password
