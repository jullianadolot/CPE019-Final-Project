# 🍎🍊 CPE019-Final-Project Fruit Classification using Deep Learning

This repository contains a deep learning-based image classification model for recognizing different types of fruits. The model is trained on a dataset consisting of six fruit categories: **apple, banana, mango, orange, strawberry, grapes, cherry, coconut, lemon, and eggplant**.

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
- Cherry
- Coconut
- Lemon
- Eggplant

> 📷 Each image is preprocessed (resized and normalized) before being fed into the model.

## 🧠 Model Architecture

We used a Convolutional Neural Network (CNN) with the following architecture:

- Input layer: 128x128 RGB images
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten
- Dense (Fully Connected) → ReLU
- Dropout
- Output layer: Softmax (10 units)
