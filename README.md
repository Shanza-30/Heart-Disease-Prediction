# ❤️ Heart Disease Prediction using Machine Learning

## 📖 Project Overview
Heart disease is one of the leading causes of death worldwide. This project aims to build a machine learning–based binary classification system to predict whether a person is at risk of heart disease based on medical attributes such as age, cholesterol, blood pressure, and heart rate.

The project follows a complete end-to-end ML pipeline, from data preprocessing and exploratory data analysis to model training, evaluation, and deployment-ready model saving.

## 🎯 Objective
To predict the presence of heart disease (**0 = No Disease, 1 = Disease**) using supervised machine learning models and evaluate them using standard medical ML metrics.

## 📂 Dataset
- **Source:** UCI Heart Disease Dataset (Cleveland)  
- **Platform:** Kaggle  
- **Type:** Structured medical data  
- **Target Variable:** target  

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning
- Loaded dataset using Pandas  
- Checked data types and missing values  
- Handled missing values using median imputation  

### 2️⃣ Exploratory Data Analysis (EDA)
 Target variable distribution analysis  
- Correlation heatmap to identify important relationships  
- Feature-wise statistical analysis  

### 3️⃣ Data Preprocessing
- Feature–target separation  
- Train-test split  
- Feature scaling using StandardScaler (for Logistic Regression )  

## 🧠 Machine Learning Models Used
- Logistic Regression (baseline model)  
- Random Forest Classifier  

## 📊 Model Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- ROC Curve & ROC-AUC Score  
- Classification Report (Precision, Recall, F1-score)  

## 🔍 Feature Importance Analysis
- Extracted and visualized feature importance using Decision Tree / Random Forest  
- Identified key medical factors influencing heart disease prediction  

## 💾 Model Saving
- Trained models saved using Pickle  

## 🛠️ Technologies & Tools
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Pickle  

## 📌 Skills Demonstrated
- Binary Classification  
- Medical Data Understanding  
- Exploratory Data Analysis (EDA)  
- Model Evaluation (ROC-AUC, Confusion Matrix)  
- Feature Importance Analysis  
- Handling Imbalanced Datasets  
- Deployment-ready ML modeling  

## 🚀 Future Improvements
- Hyperparameter tuning  
- Model comparison using cross-validation  
- Flask / Streamlit web app deployment  
- Integration with real-time medical inputs  
