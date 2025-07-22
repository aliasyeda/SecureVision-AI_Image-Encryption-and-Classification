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

## 🔐 Part 1: AES Image Encryption & Decryption

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

## 🧠 Part 2: Image Classification with MobileNetV2

### ✅ Steps Performed:
- Load the decrypted image
- Preprocess the image for MobileNetV2 input
- Use TensorFlow's pretrained model
- Predict the top 3 classes from ImageNet
- Print class names and confidence scores

### 🔍 Output Example:
🔍 Top Predictions:
👉 bannister (33.53%)
👉 worm_fence (12.97%)
👉 valley (10.34%)

yaml
Copy
Edit

---

## 🚀 How to Run

### 1️⃣ Install Requirements
```bash
pip install pycryptodome tensorflow opencv-python
2️⃣ Run Encryption/Decryption
bash
Copy
Edit
python encryption_decryption.py
3️⃣ Run Image Classification
bash
Copy
Edit
python classification.py
✅ Final Output
Encrypted and secured image file

Decrypted image for AI analysis

Classification results from the MobileNetV2 model


📃 License
This project is open-source and free to use under the MIT License.





## 👨‍💻 Author

Developed by
**Syeda Alia Samia**  
GitHub:[Syeda Alia Samia](https://github.com/your-github-username)
