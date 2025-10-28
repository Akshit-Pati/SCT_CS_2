# - Image Encryption Tool 🧠🔐

## 📌 Overview
This project demonstrates a simple image encryption and decryption system using **pixel manipulation** techniques.  
Each pixel’s RGB values are modified using **XOR encryption**, making the image unreadable until decrypted with the same key.

---

## ⚙️ Features
- Encrypt any image file (`.png`, `.jpg`)
- Decrypt using the same key
- Fast and lightweight (uses NumPy and Pillow)
- Beginner-friendly and educational

---

## 🧑‍💻 How It Works
1. Each pixel is converted to an RGB value.
2. Every RGB value is XOR’d with a numeric key (1–255).
3. The result is saved as `encrypted_image.png`.
4. Decryption applies XOR again with the same key to restore the original image.

---

## 🖥️ Usage
```bash
  image_encryption.py
