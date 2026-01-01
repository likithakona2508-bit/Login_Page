# Login_Page  

### 📌 Project Overview

This project is a console-based Registration and Login System built using Python.
It allows users to register, log in, reset passwords, and securely store credentials using hashing and regular expressions.

The project demonstrates core Python concepts such as:

File handling

Regular expressions (RegEx)

Password hashing

Functions and control flow

### 🛠️ Technologies Used

Python 3

Regular Expressions (re module)

File Handling

Hashlib (SHA-256 for password encryption)

OS module

### ✨ Features

✔ User Registration with email & password validation
✔ Secure password storage using SHA-256 hashing
✔ Login authentication
✔ Forgot password functionality
✔ Email validation using Regular Expressions
✔ Menu-driven console interface
✔ User data stored persistently in a text file

###🔍 Functionalities Explained
1️⃣ Registration

Validates email format using RegEx

Checks if email already exists

Enforces password rules:

Minimum 6 characters

At least one uppercase letter

At least one special character

Stores hashed password in a file

2️⃣ Login

Verifies registered email

Compares hashed password for authentication

Displays login success or error messages

3️⃣ Forgot Password

Validates registered email

Allows user to reset password

Updates the hashed password securely in the file

4️⃣ Retrieve Registered Users

Displays stored emails along with hashed passwords

Useful for learning file handling and debugging

### 🧠 Regular Expressions Used

Email format validation

Pattern matching for secure input handling

⚠️ Note

This project is designed for learning purposes

Passwords are securely hashed, but the storage method is basic (text file)

Can be extended using databases (MySQL, SQLite)

### 🚀 Future Enhancements

Database integration (SQLite / MySQL)

GUI using Tkinter

Password masking

Email OTP verification

Role-based authentication

### 🎯 Learning Outcomes

Practical use of RegEx

Secure password handling

File-based data persistence

Building real-world authentication logic
