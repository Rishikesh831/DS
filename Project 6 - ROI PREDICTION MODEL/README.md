# ROI Prediction Model

This project focuses on building a machine learning model to predict Return on Investment (ROI) for a dataset of 101 customers based on financial and demographic features. The final model is deployed and visualized using Power BI.

---

## 📌 Problem Statement

Predict ROI for customers using their financial attributes such as income, credit score, and other relevant features. The objective is to assist in data-driven decision-making regarding investment strategies.

---

## 🔍 Project Workflow

### 1. **Data Cleaning (Excel)**
- Handled missing values through imputation and removal.
- Standardized data formatting and ensured consistency.

### 2. **Feature Engineering (Jupyter Notebook 1)**
- Created additional features (e.g., income-to-loan ratio).
- Removed irrelevant and redundant columns.

### 3. **Model Development (Jupyter Notebook 2)**
- Used **XGBoost** for regression-based prediction.
- Performed hyperparameter tuning and cross-validation.
- Evaluated the model using appropriate metrics.

### 4. **Model Serialization**
- Saved the trained model using .pkl for deployment
### 5. **Model Deployment**
-Deployed the model succesfully in PowerBI and Streamlit. 

