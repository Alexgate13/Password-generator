# 🔐 Password Generator with Encryption (Tkinter GUI)

A simple yet functional password generator built using Python's `tkinter` library. This application can generate passwords of varying strength, encrypt them using a basic Caesar cipher, and decrypt them. It also includes copy-to-clipboard functionality using the `pyperclip` module.

## 🖥️ Features

- GUI built with `tkinter`
- Select password length (6, 8, or 10 characters)
- Choose password strength:
  - Low (only letters)
  - Medium (letters + numbers)
  - Strong (letters + numbers + symbols)
- Encrypt generated password using Caesar cipher (shift = 3)
- Decrypt encrypted password
- Copy password to clipboard

## 📷 Screenshot

> *Add a screenshot here by uploading an image and using:*
> `![Screenshot](screenshot.png)`

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  - `pyperclip`
  - `tkinter` (comes pre-installed with Python)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/password-generator.git
   cd password-generator
Install dependencies:

bash
Αντιγραφή
Επεξεργασία
pip install pyperclip
Run the application:

bash
Αντιγραφή
Επεξεργασία
python password_generator.py
🔐 How It Works
The user selects the password length and strength.

Click Generate to produce a password.

Click Copy to copy the password to clipboard.

Click Encrypt to apply a Caesar cipher with a shift of 3.

Click Decrypt to revert the encrypted password.

🛠️ Code Structure
generate(): Generates passwords based on strength.

encrypt(): Applies Caesar cipher to the password.

decrypt(): Reverses the Caesar cipher encryption.

copy(): Copies the password to the clipboard.

📋 Example
pgsql
Αντιγραφή
Επεξεργασία
Password:      5gH#8z
Encrypted:     8jK(Br
Decrypted:     5gH#8z
📄 License
This project is open source and available under the MIT License.

💡 Note
Caesar cipher used here is for educational purposes only and not secure for real-world encryption.

yaml
Αντιγραφή
Επεξεργασία

---

Let me know if you’d like a `LICENSE` file or want this converted into a GitHub `README.md` upload.





