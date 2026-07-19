# Pneumonia-Detection-Using-Chest-Xray
Deep learning project for detecting pneumonia from chest X-ray images using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.
# 🩺 Pneumonia Detection Using Chest X-Ray Images

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Overview

This project implements a Convolutional Neural Network (CNN) for detecting **Pneumonia** from chest X-ray images.

The model is trained using TensorFlow and Keras on a publicly available chest X-ray dataset. It classifies X-ray images into two categories:

- 🫁 Normal
- 🦠 Pneumonia

The project includes data preprocessing, augmentation, CNN model development, training, evaluation, and prediction visualization.

---

## 🚀 Features

- Image preprocessing
- Data augmentation
- CNN-based classification
- Early Stopping
- Learning Rate Reduction
- Model Checkpointing
- Accuracy & Loss visualization
- Model evaluation

---

## 📂 Dataset

**Chest X-Ray Images (Pneumonia)**

Dataset Link:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Classes:

- NORMAL
- PNEUMONIA

> **Note:** The dataset is not included in this repository due to its large size.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Model Architecture

The CNN consists of:

- Conv2D
- ReLU Activation
- MaxPooling2D
- Dropout
- Flatten
- Dense Layers
- Softmax Output

---

## 📈 Results

| Metric | Value |
|---------|-------|
| Training Accuracy | 93.73% |
| Best Validation Accuracy | 81.25% |
| Test Accuracy | **74.68%** |

Early stopping restored the best-performing model.

---

## 📷 Project Screenshots

### Training

![Training](images/training_epochs.png)

### Accuracy & Loss

![Accuracy](images/accuracy_loss_graph.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Akankshya-35-45/Pneumonia-Detection-Using-Chest-Xray.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
jupyter notebook
```

or open the notebook in **Google Colab**.

---

## 👩‍💻 Author

**Akankshya Dibyadarsinee Rout**

- GitHub: https://github.com/Akankshya-35-45


---
