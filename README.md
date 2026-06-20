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

## 📊 Final Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---------|---------|---------|---------|---------|
| Logistic Regression | 80.33% | 79.49% | 88.57% | 83.78% |
| Random Forest | 78.69% | 82.35% | 80.00% | 81.16% |
| KNN | 73.77% | 77.14% | 77.14% | 77.14% |

## 🏆 Best Model

### Logistic Regression

Selected because it achieved:

- Highest Accuracy
- Highest Recall
- Highest F1 Score

The model correctly identified 31 out of 35 heart disease patients while missing only 4 cases.

## 💡 Key Insights

1. Logistic Regression achieved the best overall performance after hyperparameter tuning.
2. Recall proved to be the most important metric for healthcare applications.
3. Cross-validation improved model reliability and reduced overfitting risk.
4. Hyperparameter tuning significantly improved Logistic Regression performance.
5. Machine Learning can assist in early heart disease detection and clinical decision-making.


## 🚀 Project Outcome

This project demonstrates:

✔ Data Preprocessing

✔ Feature Engineering

✔ Model Building

✔ Cross Validation

✔ Hyperparameter Tuning

✔ Model Evaluation

✔ Healthcare Data Analytics
