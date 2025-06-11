# MNIST-Digit-classification-using-neural-network
# 🧠 MNIST Digit Recognition using CNN

This project demonstrates a deep learning approach to **handwritten digit classification** using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. It is built with TensorFlow and Keras and visualized using Matplotlib.

---

## 🚀 Demo

The model achieves **~99% accuracy** on validation data and **excellent generalization** on the test set. Below is a sample result of prediction vs. true labels on the MNIST images.

---

## 📌 Features

- Clean and modular Jupyter Notebook
- Data preprocessing and normalization
- CNN architecture with Conv2D, MaxPooling, Dropout, and Dense layers
- Real-time training metrics (loss & accuracy plots)
- Test set evaluation and prediction visualization
- Model saving (`.h5`) for future use

---

## 🧰 Tech Stack

- Python 🐍
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📚 Dataset

- **MNIST** — A benchmark dataset of 70,000 grayscale images of handwritten digits (28x28 pixels).
- Loaded directly using `tf.keras.datasets.mnist`.

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/mnist-digit-recognition-CNN.git
cd mnist-digit-recognition-CNN
pip install -r requirements.txt
