# 🩺 Ultrasound Breast Cancer Classification

A deep learning project for classifying breast ultrasound images into **benign**, **malignant**, and **normal** categories.  
This project uses both **custom CNN architectures** and **transfer learning (InceptionV3)** to detect cancer from ultrasound scans.

---

## 📌 Overview

Breast cancer detection using medical imaging is a critical step in early diagnosis and treatment.  
This project leverages **Convolutional Neural Networks (CNNs)** to analyze ultrasound images and classify them accurately.  
Multiple architectures were tested to find the optimal balance between accuracy and generalization.

---

## ⚙️ Features

- ✅ Data preprocessing (image resizing, normalization, augmentation)
- ✅ Multiple CNN architectures (baseline, dropout variations, filter tuning)
- ✅ **Transfer learning** with **InceptionV3**
- ✅ Model evaluation using classification metrics (accuracy, precision, recall, F1-score)
- ✅ Visualization of training/validation performance
- ✅ Confusion matrix and heatmaps for model analysis

---

## 📂 Dataset

The dataset is from [Kaggle: Breast Ultrasound Images Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)  
It contains three categories:
- **Benign**
- **Malignant**
- **Normal**

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy / Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/ultrasound-breast-cancer-classification.git
cd ultrasound-breast-cancer-classification

