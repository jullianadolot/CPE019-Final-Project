# CPE019-Final-Project

# 🍎🍊 Fruit Classification using Deep Learning

This repository contains a deep learning-based image classification model for recognizing different types of fruits. The model is trained on a dataset consisting of six fruit categories: **apple, banana, mango, orange, strawberry, and grapes**.

## 📌 Project Overview

The goal of this project is to develop an image classifier that can accurately identify fruit types using Convolutional Neural Networks (CNN). This can be used in applications like smart farming, fruit quality control, and retail automation.

## 📁 Dataset

The dataset consists of labeled images of the following fruit classes:

- Apple
- Banana
- Mango
- Orange
- Strawberry
- Grapes

> 📷 Each image is preprocessed (resized and normalized) before being fed into the model.

## 🧠 Model Architecture

We used a Convolutional Neural Network (CNN) with the following architecture:

- Input layer: 128x128 RGB images
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten
- Dense (Fully Connected) → ReLU
- Dropout
- Output layer: Softmax (6 units)

Optionally, you can also use pretrained models like `EfficientNetB3` or `DenseNet121` via transfer learning for better performance on small datasets.

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fruit-classification.git
   cd fruit-classification
