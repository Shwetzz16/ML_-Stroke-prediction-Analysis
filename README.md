# ML-Stroke-prediction-Analysis
# 🧠 Stroke Prediction Using Machine Learning

This project uses machine learning to predict whether a patient is likely to experience a **stroke** based on clinical and demographic features.  
The goal is to assist early medical intervention by identifying high-risk individuals.

---

## 📌 Dataset Description
The dataset contains patient health records with the following features:

| Feature | Description |
|--------|-------------|
| gender | Male / Female / Other |
| age | Age of the patient |
| hypertension | 1 = has hypertension, 0 = does not |
| heart_disease | 1 = has heart disease, 0 = does not |
| ever_married | Marital status |
| work_type | Type of employment |
| Residence_type | Urban / Rural |
| avg_glucose_level | Average glucose level |
| bmi | Body Mass Index |
| smoking_status | Smoking behavior |
| stroke | **Target variable** (1 = stroke, 0 = no stroke)

Dataset source (Kaggle):  
https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

---

## 🎯 Project Objective
- Perform **data cleaning** and handle missing values.
- Conduct **Exploratory Data Analysis (EDA)** to understand variable influence.
- Train **Machine Learning models** to predict stroke risk.
- Evaluate and compare model performance.

---

## 🧠 Machine Learning Steps Performed
1. **Data Preprocessing**
   - Handled missing BMI values
   - Converted categorical columns to numeric form using encoding
   - Standardized numeric columns where needed

2. **Exploratory Data Analysis**
   - Histograms for numerical column distributions  
   - Countplots for categorical features  
   - Correlation heatmap  
   - Feature-to-stroke relationship analysis  

3. **Model Training**
   Models used in the notebook include:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM) *(if included)*

4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

---

## ✅ Key Insights
- **Age**, **Average Glucose Level**, and **BMI** showed stronger influence on stroke probability.
- Patients with **hypertension** and **heart disease** had significantly higher stroke risk.
- Imbalanced dataset required careful evaluation using **recall** (important for medical predictions).

---



