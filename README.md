# 🌿 Plant Disease Detection using CNN

## 📌 Overview

The **Plant Disease Detection using Convolutional Neural Networks (CNN)** project is a deep learning approach to identify plant leaf diseases from images. It helps farmers and agricultural professionals detect diseases early to minimize crop loss and ensure healthy plant growth.

---

## 🧠 Objectives

- Automatically detect and classify plant diseases using CNN.
- Build an accurate and efficient deep learning model.
- Assist real-world agriculture through technology.

---

## 📁 Dataset

- **Dataset**: PlantVillage Dataset  
- **Source**: [Kaggle - PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease)  
- **Classes**: 38 categories (including healthy leaves)
- **Size**: 50,000+ labeled images

### Preprocessing Steps

- Image resizing to 128x128 pixels
- Normalization of pixel values
- Data augmentation (rotation, flip, zoom, etc.)

---

## 🧱 Tech Stack

- **Language**: Python
- **Libraries**: TensorFlow, Keras, NumPy, Matplotlib, OpenCV
- **Tools**: Jupyter Notebook / Google Colab

---

## 🏗️ Model Architecture

```plaintext
Input Layer: 128x128x3
↓
Conv2D + ReLU
↓
MaxPooling2D
↓
Conv2D + ReLU
↓
MaxPooling2D
↓
Dropout
↓
Flatten
↓
Dense Layer (ReLU)
↓
Dense Layer (Softmax)
