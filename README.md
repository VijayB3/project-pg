# 🔐 Password Manager Desktop Application.

A simple and secure desktop password manager built using **Python** and **Tkinter**  
This application helps users generate strong passwords, store credentials, and manage login information efficiently.

---

## 📌 Project Overview

Remembering multiple passwords is difficult.  
This tool reduces that problem by allowing users to:

- Generate strong, random passwords
- Automatically copy them to the clipboard
- Store website credentials locally
- Confirm before saving
- Avoid empty or incorrect entries

This project demonstrates GUI development, event handling, file operations, and modular programming in Python.

---

## 🚀 Features

✅ User-friendly graphical interface  
✅ Random password generation (letters, numbers, symbols)  
✅ Auto-copy password to clipboard  
✅ Input validation  
✅ Confirmation popup before saving  
✅ Persistent storage using a local file  
✅ Clears input fields after saving  
✅ Default email pre-filled for convenience  

---

## 🛠 Technologies Used

- **Python**
- **Tkinter** (GUI)
- **random** module
- **pyperclip**
- File Handling

---

## 📂 Project Structure

password-manager/
│
├── main.py
├── data.txt
├── pass.png
└── README.md


---

## ⚙️ How It Works

### Password Generation
The app:
1. Randomly selects characters from letters, numbers, and symbols.
2. Shuffles them for unpredictability.
3. Inserts the password into the input field.
4. Copies it directly to the clipboard.

### Saving Data
When the user clicks **Add**:
1. Inputs are validated.
2. A confirmation popup appears.
3. If approved, data is appended to `data.txt`.

Format:
website | email | password


---

## 🖼 Application Preview

_Add screenshots of:_
- Main window  
- Generated password  
- Confirmation dialog  

Example:

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Building desktop applications
- Managing layouts using grid
- Handling button events
- Working with external libraries
- Performing file read/write operations
- Improving user experience with validations

---

## 🔒 Limitations

This version stores passwords in plain text and is intended for learning purposes.

Future improvements can include:
- Encryption
- Search & update functionality
- JSON or database storage
- Authentication system
- Cloud sync

---

## 💡 Future Enhancements

- Add password search feature  
- Add edit & delete options  
- Implement encryption for security  
- Convert into a web application  
- Add login system  
- Dark mode UI  

---

## ▶️ How to Run

1. Install Python  
2. Install dependency:
pip install pyperclip

3. Run:


python main.py


---

## 👨‍💻 Author

**Vijay Bhalerao**

Aspiring Developer | Interested in Backend, Cloud & DevOps

---

## ⭐ Support

If you found this useful, consider giving the repository a star!

 

