# 🔢 Handwritten Digit Recognition with CNN  
> **Prodigy InfoTech – Data Science Internship Task 5**  
> Deep Learning-based Image Classification using MNIST Dataset

![Task 5 Banner](https://github.com/kindo-tk/PRODIGY_DS_05/blob/main/ds5.png)

---

## 📌 Project Objective
As part of Task 5 in the **Data Science Internship at Prodigy InfoTech**, this project focuses on building a **Convolutional Neural Network (CNN)** to recognize handwritten digits from the **MNIST dataset**.

The goal is to:
- Train a deep learning model on grayscale digit images
- Classify each image into one of the 10 classes (0–9)
- Evaluate its performance using standard metrics

---

## 🧠 Problem Statement
Build and evaluate a CNN-based image classifier that achieves high accuracy in recognizing handwritten digits.

---

## 📂 Dataset Used
- **Name**: MNIST (Modified National Institute of Standards and Technology)
- **Source**: `tensorflow.keras.datasets.mnist`
- **Details**:
  - 60,000 training images
  - 10,000 testing images
  - 28x28 grayscale images of digits (0–9)

---

## 🛠️ Tools & Libraries Used
- `Python`
- `TensorFlow` / `Keras`
- `NumPy`
- `Matplotlib`
- `Seaborn`
- `Jupyter Notebook`

---

## ⚙️ Model Architecture
- Input Layer: 28x28 pixel images
- 2 Convolutional Layers (with ReLU activation)
- MaxPooling Layer
- Flatten Layer
- Dense Layers (Fully Connected)
- Output Layer (Softmax for 10 classes)

---


## ✅ Conclusion & Learnings
- Built a CNN from scratch to classify digits with high accuracy
- Learned how to preprocess image data for deep learning
- Gained experience in tuning layers and dropout to reduce overfitting
- Applied real-world techniques like batch normalization and Adam optimizer

