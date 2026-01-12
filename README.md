# 🐾 Animal Image Classification using Deep Learning (Inception-V3)

End-to-end deep learning project for multi-class image classification using a custom Inception-V3 inspired CNN, trained on a large-scale real-world dataset.

---

## 🚀 Quick Highlights (For Recruiters)
- **Domain:** Computer Vision | Deep Learning | CNNs
- **Dataset:** Animals-10 (~26K images, 10 classes)
- **Architecture:** Custom Inception-V3 (from scratch)
- **Frameworks:** TensorFlow, Keras
- **Techniques:** Data Augmentation, Batch Normalization, Dropout, Fine-Tuning
- **Evaluation:** Accuracy, Confusion Matrix, Classification Report
- **Deployment Ready:** Model saved in `.keras` format

---

## 🎯 Problem Statement
Classify animal images into **10 distinct categories** with high accuracy while ensuring **generalization and robustness** on unseen data.

---

## 🧠 Solution Approach
- Built a **custom Inception-V3 inspired CNN** to extract multi-scale image features
- Applied **data augmentation** to reduce overfitting
- Used **Batch Normalization and Dropout** for training stability
- Implemented **learning rate scheduling** and **early stopping**
- Fine-tuned the model for improved validation performance

---

## 🏗️ Model Architecture (High Level)
- Convolution + MaxPooling layers
- Multiple Inception modules with parallel convolution paths
- Global Average Pooling
- Fully Connected layers
- Softmax output layer (10 classes)

---

## 📂 Dataset Information
**Source:** Kaggle – Animals-10  
**Images:** ~26,000  
**Classes:** Dog, Cat, Horse, Elephant, Butterfly, Chicken, Cow, Sheep, Spider, Squirrel  

Italian class labels were translated to English for readability.

---

## 📊 Results & Evaluation
- Achieved strong validation accuracy on a challenging multi-class dataset
- Demonstrated good generalization with minimal overfitting
- Evaluated using:
  - Training vs Validation Accuracy/Loss curves
  - Confusion Matrix
  - Precision, Recall, and F1-Score per class

---

## 🛠️ Tech Stack
- **Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Visualization:** Matplotlib
- **Evaluation:** Scikit-learn
- **Platform:** Google Colab
- **Data Source:** Kaggle API

---

## ▶️ How to Run
```bash
pip install tensorflow kaggle scikit-learn matplotlib
