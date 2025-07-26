# Supervised-Learning-Pipeline-for-Phishing-Website-Classification

## 📌 Overview

This project implements an intelligent phishing detection system using machine learning models, with a focus on **CatBoost**, **Random Forest**, **LightGBM**, and **Decision Tree** algorithms. The primary goal is to detect phishing websites in real time with high accuracy and low false negative rates.

The final application, **PhishGuard**, provides a web-based interface to classify URLs as phishing or legitimate using the trained CatBoost model.

---

## 🚀 Features

- ✅ Real-time phishing website detection via a Django web app.
- 📊 Utilizes optimized **CatBoost** model with **97.23% accuracy** and **1.4% false negative rate**.
- 🧠 Trained on a clean, balanced dataset with 11,000 records and 30 features.
- 🧪 Evaluated using precision, recall, F1-score, and confusion matrix.
- 📉 Compared with other models and previous research to validate effectiveness.

---

## 📂 Dataset

- **Source**: Kaggle  
- **Name**: [Phishing Website Detector](https://www.kaggle.com/datasets/eswarchandt/phishing-website-detector)  
- **Details**:
  - 11,000 records
  - 30 features
  - Target labels: `-1` (phishing) and `1` (legitimate)

---

## 🧰 Tech Stack

- **Languages**: Python, Django
- **IDE**: VS Code
- **Libraries**:
  - `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`
  - `catboost`, `lightgbm`
  - `pickle` for model serialization
- **Database**: Django ORM

---

## 📊 Model Performance

| Model                   | Test Accuracy | Validation Accuracy | False Negatives |
|------------------------|---------------|---------------------|-----------------|
| CatBoost (1000 it)     | 97.28%        | 97.68%              | **17**          |
| Random Forest          | 96.87%        | 97.40%              | 28              |
| LightGBM               | 95.80%        | 96.40%              | 33              |
| SVM                    | 94.68%        | 95.14%              | 36              |
| Decision Tree          | 91.64%        | 92.00%              | 51              |

---
