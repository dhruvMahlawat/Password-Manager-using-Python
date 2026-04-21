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
