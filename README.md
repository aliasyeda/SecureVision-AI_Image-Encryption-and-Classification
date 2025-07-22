# SecureVision-AI_Image-Encryption-and-Classification

# 🔐 SecureVision-AI: Image Encryption & AI Classification System

This project combines **Cybersecurity** and **Artificial Intelligence** by implementing **AES encryption** on images and using a **pretrained deep learning model (MobileNetV2)** to classify decrypted images.

---

## 📌 Project Overview

This project has two main parts:

1. 🔒 **Image Encryption & Decryption** using AES (Advanced Encryption Standard)
2. 🧠 **Image Classification** using a Pretrained MobileNetV2 model

The goal is to show how we can **secure visual data** and still use **AI** to extract insights from it.

---

---

## 🛠️ Technologies Used

- Python 3
- [PyCryptodome](https://pypi.org/project/pycryptodome/) – for AES encryption
- [TensorFlow](https://www.tensorflow.org/) – for MobileNetV2 model
- [OpenCV](https://opencv.org/) – for image handling

---

## 💡 Features

🔒 Image Encryption/Decryption using AES (Advanced Encryption Standard)

🤖 AI Image Classification using MobileNetV2

📂 Entire flow is handled in one notebook (no separate .py files)

🔍 View top 3 predictions after decryption

---

## 🔐 AES Image Encryption & Decryption

### ✅ Steps Performed:
- Import AES and Padding modules from PyCryptodome
- Read the image as bytes
- Encrypt using AES (CBC mode with random IV)
- Save as `.aes` encrypted file
- Decrypt using the same key & IV
- Save decrypted image

### 🔑 Why AES?
AES is a symmetric encryption algorithm widely used for data security. It encrypts your image to prevent unauthorized access.

---

## 🧠  Image Classification with MobileNetV2

### ✅ Steps Performed:
- Load the decrypted image
- Preprocess the image for MobileNetV2 input
- Use TensorFlow's pretrained model
- Predict the top 3 classes from ImageNet
- Print class names and confidence scores

---

## 🔄 Workflow Steps

📤 Encrypt the Image (Nature.jpg) ➝ saved as encrypted_Nature.aes

📥 Decrypt the Image ➝ saved as decrypted_Nature.jpg

🧠 Classify using AI (MobileNetV2) ➝ shows top-3 predictions

---
## 🖼️ Sample Output

✅ Nature.jpg encrypted and saved as 'encrypted_Nature.aes'
✅ Image decrypted and saved as 'decrypted_Nature.jpg'
🔍 Top Predictions:
👉 bannister (33.53%)
👉 worm_fence (12.97%)
👉 valley (10.34%)


---

## 🚀 How to Run

### 1️⃣ Install Requirements
`
pip install pycryptodome tensorflow opencv-python


## ✅ Final Output

Encrypted and secured image file

Decrypted image for AI analysis

Classification results from the MobileNetV2 model


---

📃 License
This project is open-source and free to use under the MIT License.

---

## 🏆 Project Purpose

This project is developed for demonstrating the power of combining encryption + AI for digital image security.

---



## 👨‍💻 Author

Developed by
**Syeda Alia Samia**  
GitHub:[Syeda Alia Samia](https://github.com/your-github-username)
