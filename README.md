# Heart Disease Prediction - ML Classification Project

A machine learning classification project that predicts the presence of heart disease using clinical patient data. This project implements and compares multiple classification algorithms with hyperparameter tuning to achieve optimal predictive performance.

---

### 🏥 Overview
This repository contains a complete machine learning pipeline for heart disease prediction using **scikit-learn**. The project demonstrates fundamental data science workflows including:
* **Exploratory Data Analysis (EDA)**
* **Model Comparison**
* **Hyperparameter Optimization**
* **Performance Evaluation**

### 📊 Dataset
* **File:** `heart-disease.csv`
* **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, old peak, slope, CA, and thal.
* **Target:** Binary classification (0 = No disease, 1 = Disease present)

---

### 🛠 Key Components

#### 1. Exploratory Data Analysis (EDA)
* Data distribution and class balance analysis.
* Correlation matrix heatmap visualization.
* Feature analysis across disease presence/absence groups.

#### 2. Model Comparison
I tested three primary algorithms:
* **Logistic Regression**
* **K-Nearest Neighbors (KNN)**
* **Random Forest Classifier**

#### 3. Hyperparameter Optimization
* **RandomizedSearchCV** for Logistic Regression ($C$ parameter tuning).
* **RandomizedSearchCV** for Random Forest (`n_estimators`, `max_depth`, etc.).
* **Cross-validation (CV=5)** for robust performance estimation.

#### 4. Model Evaluation
* Accuracy scoring & Confusion matrices.
* Precision, Recall, and F1-Score.
* **ROC curves** and **ROC-AUC scores**.

---

### 💻 Tools & Libraries
* **pandas** - Data manipulation
* **scikit-learn** - ML algorithms and evaluation
* **matplotlib & seaborn** - Data visualization
* **numpy** - Numerical computing
