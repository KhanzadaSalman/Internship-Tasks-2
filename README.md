# ❤️ Heart Disease Prediction (Task 3)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

This repository contains the source code for **Task 3: Heart Disease Prediction**, completed as part of the AI/ML Engineering Internship.

## 📌 Objective
To build a machine learning model that predicts whether a patient is at risk of heart disease based on clinical features like age, cholesterol, and blood pressure.

## 📂 Dataset
* **Source:** Heart Disease UCI Dataset (Kaggle).
* **Key Features:** Age, Sex, CP (Chest Pain Type), Trestbps (Resting Blood Pressure), Chol (Cholesterol), etc.
* **Target:** 0 (Healthy) vs 1 (Heart Disease).

## 🛠️ Technologies Used
* **Pandas & NumPy:** For data cleaning (handling missing values, converting text to numbers).
* **Matplotlib & Seaborn:** For EDA (Correlation Heatmap).
* **Scikit-Learn:** For Model Training (Logistic Regression vs. Random Forest).

## 📊 Model Performance
| Model | Accuracy | Analysis |
| :--- | :--- | :--- |
| **Logistic Regression** | 80% | Good baseline, but struggles with complex patterns. |
| **Random Forest** | **85%** | **Best Performer.** Captures non-linear relationships in medical data. |

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
