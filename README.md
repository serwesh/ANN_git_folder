# 🧠 Handwritten Digit Classification using ANN (MNIST Dataset)

This project demonstrates a **multiclass image classification** model built using an **Artificial Neural Network (ANN)** to recognize **handwritten digits (0–9)** from the **MNIST dataset**.

---

## 📘 Project Overview

The MNIST dataset consists of **70,000 grayscale images** of handwritten digits:
- **60,000 training samples**
- **10,000 test samples**
- Each image is **28×28 pixels**

Our goal is to train an **Artificial Neural Network (ANN)** that can accurately classify these digits into **10 classes (0–9)**.

---

## 🧩 Model Architecture

| Layer Type | Description |
|-------------|--------------|
| Input Layer | 784 neurons (flattened 28×28 image) |
| Hidden Layer 1 | Dense layer with 128 neurons, ReLU activation |
| Hidden Layer 2 | Dense layer with 64 neurons, ReLU activation |
| Output Layer | Dense layer with 10 neurons, Softmax activation |

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Matplotlib / Seaborn  
- TensorFlow / Keras  
- vs code

---

## 🚀 How to Run the Project

### 1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/mnist-ann-classifier.git
cd mnist-ann-classifier
