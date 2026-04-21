# 🔐 Secure Password Manager (Python + Tkinter)

A simple and secure desktop password manager built using Python.
This application allows users to store, manage, and generate passwords safely using encryption.

---

## 🚀 Features

* 🔑 Master Password Authentication
* 🔐 Encryption using **Fernet (cryptography library)**
* 🧠 Secure hashing with **PBKDF2 + SHA-256**
* 💾 Local database using **SQLite**
* 🔍 Search saved credentials
* ➕ Add, ✏️ Edit, ❌ Delete passwords
* 👁️ Show/Hide password
* 📋 Copy to clipboard
* ⚡ Strong password generator
* 🖥️ Clean GUI using Tkinter

---

## 🛠️ Tech Stack

* Python
* Tkinter (GUI)
* SQLite3 (Database)
* Cryptography (Encryption)
* Hashlib (Security)

---

## 📂 Project Structure

```
password_manager.py   # Main application file
passwords.db          # Database (auto-created)
config.json           # Config file (if used)
```

---

## 🔒 Security Overview

* Master password is **never stored directly**
* Password is:

  * Salted
  * Hashed using PBKDF2 (100,000 iterations)
* Encryption key is derived from the master password
* All stored passwords are encrypted using Fernet

---

## ▶️ Installation & Setup

### 1. Install Dependencies

```bash
pip install cryptography
```

### 2. Run the Application

```bash
python password_manager.py
```

---

## 🧑‍💻 Usage

### First Run:

* Set your **master password**

### Next Runs:

* Login using your master password

---

## ⚙️ Functionalities

### 🔑 Manage Passwords

* Add new credentials
* Update existing ones
* Delete entries

### 🔍 Search

* Search by website or username

### 🎲 Password Generator

* Length: 8–64 characters
* Optional symbols

### 📋 Clipboard Support

* Copy passwords easily

---

## ⚠️ Important Notes

* ❗ If you forget your master password, recovery is not possible
* ❗ Keep your database file (`passwords.db`) safe
* ❗ Do not share your master password

---

## 🧪 Future Improvements

* Cloud backup / sync
* Export & import feature
* Dark mode
* Auto-lock system
* Multi-user support

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork and improve the project.

---

## 📄 License

This project is open-source and free to use.

---

## ⭐ Acknowledgement

This project demonstrates:

* Secure password handling
* GUI development in Python
* Real-world encryption implementation

---
🔐 Secure Password Manager (Python + Tkinter)

A secure desktop password manager built using Python and Tkinter that allows users to safely store, manage, and generate passwords with encryption.

🚀 Features
🔑 Master Password Authentication
🔐 Strong Encryption using Fernet (cryptography library)
🧠 Secure password hashing with PBKDF2 + SHA-256
💾 Local storage using SQLite database
🔍 Search saved passwords
➕ Add, ✏️ Edit, ❌ Delete credentials
👁️ Show/Hide password functionality
📋 Copy password to clipboard
⚡ Built-in strong password generator
🖥️ User-friendly GUI with Tkinter
🛠️ Tech Stack
Python
Tkinter (GUI)
SQLite3 (Database)
Cryptography (Encryption)
Hashlib & PBKDF2 (Security)
📂 Project Structure
password_manager.py   # Main application file
passwords.db          # SQLite database (auto-created)
config.json           # Config file (if used)
🔒 How Security Works
Master password is never stored directly
It is:
Salted
Hashed using PBKDF2 (100,000 iterations)
Encryption key is derived from master password
All saved passwords are:
Encrypted using Fernet symmetric encryption
Stored safely in database
▶️ How to Run
1. Install dependencies
pip install cryptography
2. Run the program
python password_manager.py
🧑‍💻 First-Time Setup
On first run:
You will be asked to set a master password
On next runs:
You must login using the master password
📸 Application Workflow
Login / Set Master Password
Add new credentials (website, username, password)
View saved passwords
Search for entries
Edit or delete records
Generate strong passwords
⚙️ Key Functionalities
🔑 Password Management
Add new credentials
Update existing ones
Delete saved passwords
🔍 Search
Search by website or username
🔐 Encryption
All passwords are encrypted before storage
🎲 Password Generator
Custom length (8–64)
Option to include symbols
⚠️ Important Notes
❗ If you forget your master password, data cannot be recovered
❗ Keep your database file (passwords.db) safe
❗ Do not share your master password
🧪 Future Improvements
Cloud sync / backup
Export & import passwords
Auto-lock after inactivity
Dark mode UI
Multi-user support
🤝 Contributing

Feel free to fork this project and improve it!

📄 License

This project is open-source and free to use.

⭐ Final Thoughts

This project is a great example of:

Secure application design
GUI development in Python
Real-world encryption usage

If you want, I can also:

Make this GitHub-ready with badges
Add screenshots
Or simplify it further for college submission 👍
