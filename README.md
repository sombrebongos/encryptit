# 🔒 Encrypt It!

This tool allows you to **protect your Python source code** by encoding it into a compressed Base64 string, wrapped inside an `exec()` statement. The result is still a valid `.py` file, but the original source code is hidden and much harder to read or modify.  

---

## 🚀 Features
- Encrypt any `.py` file into an obfuscated `.py` version.  
- Keeps the script executable with `python yourfile_enc.py`.  
- Uses only Python **standard libraries** (no external dependencies).  

---

## 🛠️ Usage
```bash
   git clone https://github.com/sombrebongos/encryptit
   cd encryptit
   python enc.py
