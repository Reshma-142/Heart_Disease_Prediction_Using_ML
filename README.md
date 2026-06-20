# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict the presence of heart disease using patient medical data. Multiple machine learning algorithms were trained, evaluated, and compared to identify the most effective model for disease prediction.


## 🎯 Problem Statement

Build, train, and evaluate machine learning models to predict heart disease and determine the best-performing algorithm using appropriate evaluation metrics.


## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

## 📂 Dataset Information

The dataset contains patient health information such as:

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Thalassemia
- Heart Disease Target Variable

Target Variable:
- 0 = No Heart Disease
- 1 = Heart Disease


## 🔍 Project Workflow

### Step 1: Data Exploration & Preprocessing
- Loaded and explored dataset
- Checked missing values and duplicates
- Split data into training and testing sets
- Applied feature scaling where required

### Step 2: Feature Engineering
- Performed correlation analysis
- Identified important features
- Analyzed feature relationships with target variable

### Step 3: Model Training
Trained and compared:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

### Step 4: Cross Validation & Hyperparameter Tuning
- Applied 5-Fold Cross Validation
- Used GridSearchCV for parameter optimization
- Selected Recall as the primary evaluation metric

### Step 5: Model Evaluation
Evaluated models using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix



| Model               |   Accuracy |  Precision |     Recall |   F1 Score |
| ------------------- | ---------: | ---------: | ---------: | ---------: |
| Logistic Regression |     80.33% |     75.61% | **93.94%** |     83.78% |
| KNN                 |     80.33% |     76.92% |     90.91% |     83.33% |
| **Random Forest**   | **83.61%** | **81.08%** |     90.91% | **85.71%** |


🏆 **Best Model: Random Forest**
Why Random Forest?
Highest Accuracy (83.61%)
Highest Precision (81.08%)
Highest F1 Score (85.71%)
Strong Recall (90.91%)

Although Logistic Regression has a slightly higher Recall (93.94%), Random Forest provides the best overall balance across all evaluation metrics.

💡 Key Insights
1. Random Forest emerged as the best-performing model, achieving the highest Accuracy (83.61%), Precision (81.08%), and F1 Score (85.71%).
2. Logistic Regression achieved the highest Recall (93.94%), making it highly effective at identifying patients with heart disease.
3. Cross-validation and hyperparameter tuning improved model reliability, helping to select the most robust algorithm.
4. Random Forest provided the best balance between Precision and Recall, resulting in superior overall performance.
5. Machine Learning can effectively support early heart disease detection by analyzing patient health indicators and predicting disease risk.


🚀 Project Outcome

This project successfully demonstrated:

✔ Data Cleaning & Preprocessing

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Feature Scaling

✔ Train-Test Splitting

✔ Cross Validation (K-Fold)

✔ Hyperparameter Tuning (GridSearchCV)

✔ Model Building & Comparison

✔ Model Evaluation using Accuracy, Precision, Recall & F1 Score

✔ Confusion Matrix Analysis

✔ Healthcare Data Analytics & Predictive Modeling

✔ Selection of the Best Performing Model (Random Forest)
