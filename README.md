# PRODIGY_ML_03

# 🐶🐱 Dogs vs Cats Image Classification using SVM

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-SVM-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)

## 📌 Project Overview

This project implements a **Support Vector Machine (SVM)** classifier to distinguish between images of cats and dogs from the popular Kaggle Dogs vs Cats dataset.

Instead of using deep learning, this project demonstrates how traditional machine learning techniques combined with feature engineering can effectively solve image classification problems.

---

## 🎯 Objective

Build an image classification pipeline that:

✅ Reads and processes raw images

✅ Extracts meaningful visual features

✅ Trains an SVM classifier

✅ Predicts whether an image contains a Cat or Dog

✅ Visualizes model predictions

---

## 🗂️ Dataset

**Source:** Kaggle Dogs vs Cats Dataset

📷 Total Images: 25,000+

🐱 Cat Images

🐶 Dog Images

For faster training, a balanced subset of the dataset was used.

---

## ⚙️ Technologies Used

| Tool | Purpose |
|--------|----------|
| Python | Programming Language |
| OpenCV | Image Processing |
| Scikit-Learn | Machine Learning |
| Scikit-Image | HOG Feature Extraction |
| Matplotlib | Visualization |
| NumPy | Numerical Operations |

---

## 🔍 Workflow

### 1️⃣ Image Preprocessing

- Convert images to grayscale
- Resize images to a fixed resolution
- Normalize pixel values

### 2️⃣ Feature Extraction

Histogram of Oriented Gradients (**HOG**) was used to capture shape and edge information from images.

### 3️⃣ Data Standardization

Features were scaled using StandardScaler to improve SVM performance.

### 4️⃣ Model Training

A Support Vector Machine classifier with an RBF kernel was trained on extracted HOG features.

### 5️⃣ Evaluation

Performance was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Visual Prediction Grid

---

## 📊 Model Performance

| Metric | Value |
|----------|---------|
| Algorithm | Support Vector Machine |
| Kernel | RBF |
| Feature Extractor | HOG |
| Classification Type | Binary |

> Performance may vary depending on dataset size and selected parameters.

---

## 🖼️ Sample Prediction Output

The model generates a visual prediction grid displaying:

🟢 Correct Predictions

🔴 Incorrect Predictions

Example:

```
True: Cat   Pred: Cat
True: Dog   Pred: Dog
True: Cat   Pred: Dog
```

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install numpy opencv-python matplotlib scikit-learn scikit-image
```

### Run the Project

```bash
python cats_dogs_visual_svm.py
```

---

## 📁 Project Structure

```text
PRODIGY_ML_03/
│
├── train/
├── cats_dogs_visual_svm.py
├── prediction_grid.png
├── README.md
```

---

## 💡 Key Learning Outcomes

✔ Computer Vision Fundamentals

✔ Feature Engineering using HOG

✔ Image Classification using SVM

✔ Model Evaluation Techniques

✔ Real-world Machine Learning Workflow

---

## 🏢 Internship Task

**Task-03**

Machine Learning Internship @ Prodigy InfoTech

Implement a Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle dataset.

---

⭐ If you found this project useful, consider giving it a star!
