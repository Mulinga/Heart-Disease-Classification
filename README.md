# 🫀 Heart Disease Classification - End-to-End ML Model

This project presents a complete end-to-end machine learning pipeline to predict the likelihood of heart disease based on clinical features. It includes data preprocessing, exploratory data analysis (EDA), model training using various classifiers, hyperparameter tuning, and evaluation metrics.

## 📌 Project Overview

Heart disease remains one of the leading causes of death globally. This model helps predict the presence of heart disease using a dataset containing patient information such as age, sex, chest pain type, blood pressure, cholesterol, and more.

By using machine learning, the goal is to create a predictive model that can assist healthcare providers in early diagnosis.

---

## 🧠 Machine Learning Workflow

The steps followed in this project include:

1. **Data Import and Cleaning**

   - Load dataset (from CSV)
   - Check for null values
   - Basic statistical summaries

2. **Exploratory Data Analysis (EDA)**

   - Visualization of data distributions (e.g., histograms, pairplots)
   - Correlation heatmaps
   - Class distribution analysis

3. **Data Preprocessing**

   - Feature selection and scaling (StandardScaler)
   - Encoding categorical features (LabelEncoder / OneHotEncoder if necessary)
   - Splitting into train-test sets

4. **Model Building**

   - Trained models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
     - XGBoost (if installed)
   - Hyperparameter tuning using GridSearchCV (where applicable)

5. **Model Evaluation**

   - Confusion Matrix
   - Accuracy Score
   - Precision, Recall, F1-score
   - ROC-AUC Curve
   - Classification reports

6. **Model Comparison**
   - Tabular and graphical comparison of model performance
   - Selection of the best-performing model

---

## 📂 Repository Structure
