# Date Fruit Classification using Deep Learning  in (PyTorch)

## Overview

This project presents a Deep Learning based multi-class classification system for identifying different varieties of date fruits using an Artificial Neural Network (ANN) implemented in PyTorch.

The model is trained on real-world agricultural data containing physical and morphological characteristics of date fruits. The project demonstrates a complete machine learning workflow including preprocessing, feature scaling, tensor conversion, ANN model development, training, and evaluation.

---

## Features

- Data preprocessing using Pandas and NumPy
- Label encoding for categorical target classes
- Feature scaling using StandardScaler
- Artificial Neural Network implementation using PyTorch
- Multi-class classification
- Batch training using DataLoader
- Model evaluation using classification accuracy
- Clean and modular deep learning pipeline

---

## Tech Stack

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Dataset

Dataset Used:
- `DateFruit_Dataset.csv`

Target Column:
- `Class`

The dataset contains multiple numerical features representing the characteristics of different date fruit varieties.

---

## Project Workflow

1. Load Dataset
2. Data Cleaning & ValidatioNS
3. Label Encoding
4. Feature Scaling
5. Train-Test Split
6. Tensor Conversion
7. ANN Model Building
8. Model Training
9. Model Evaluation

---

## Neural Network Architecture

```text
Input Layer
   ↓
Hidden Layer (64 Neurons + ReLU)
   ↓
Hidden Layer (64 Neurons + ReLU)
   ↓
Output Layer (7 Classes)
