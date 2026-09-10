# 📒 Phonebook

A simple command-line (CLI) Python application for saving people's first name, last name, and mobile number to a text file.

## ✨ Features

- Prompts the user for first name, last name, and mobile number
- Automatically appends the entered data to `outputnumbers.txt`
- Lets you keep adding contacts one after another in a single run
- Shows a welcome banner as ASCII art on startup

## 🚀 Requirements

- Python 3.x

## 📥 Installation & Usage

```bash
git clone https://github.com/sina-mansouri/Phonebook.git
cd Phonebook
python Phonebook.py
```

## 🖥️ How It Works

Run the script and follow the prompts:

1. Enter the first name
2. Enter the last name
3. Enter the mobile number
4. After each contact, answer `y` or `n` to add another contact or exit the program

Each contact's details are automatically appended to `outputnumbers.txt` in the same folder.

## 📂 Project Structure

```
Phonebook/
├── Phonebook.py       # Main application file
├── .gitignore
└── outputnumbers.txt  # Output file (created after the first run)
```

## 🛠️ Ideas for Future Improvements

- [ ] Validate the mobile number format
- [ ] Add search, edit, and delete functionality for contacts
- [ ] Store data as JSON or CSV instead of plain text
- [ ] Build a graphical or web-based interface

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

## 👤 Author

**Sina Mansouri**
GitHub: [@sina-mansouri](https://github.com/sina-mansouri)
