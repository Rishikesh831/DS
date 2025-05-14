# 📊 Customer Churn Prediction using SVC

This project is a machine learning pipeline for predicting telecom customer churn using Support Vector Classification (SVC). The end goal was to not just build a high-performing model but also deploy it with an intuitive Streamlit interface.

---

## 🚀 Project Overview

* **Problem**: Predict whether a telecom customer will leave the service based on demographics and usage data.
* **Model**: SVC (Support Vector Classifier) with hyperparameter tuning.
* **Interface**: Streamlit app for real-time prediction.

---

## 🗂️ Files Included

* `app.py` – Streamlit app file for deployment
* `churn_pipeline.pkl` – Trained pipeline including preprocessing and SVC model
* `column_order.pkl` – Ordered list of final features used for inference
* `README.md` – Project documentation
* `requirements.txt` – Dependencies needed for the project

---


## 🔧 How It Works

1. User enters customer details in the Streamlit UI.
2. Input is preprocessed and scaled using the saved pipeline.
3. The trained SVC model predicts churn.
4. Result is displayed as **Churn** or **No Churn**.

---

## 🧠 Machine Learning Details

* Algorithm: Support Vector Classifier (SVC)
* Preprocessing:

  * Binary encoding for `Yes/No`, `Male/Female`
  * Custom encoding for `MultipleLines`, etc.
  * One-hot encoding for multi-class fields
  * Feature scaling with StandardScaler
* Model selection: GridSearchCV with 5-fold CV and F1 scoring

---

## 📈 Evaluation

* Evaluation Metric: `f1_score` (to handle class imbalance)
* F1 Score (Class 0): High
* F1 Score (Class 1): \~0.59

---

## 📌 Future Improvements

* Handle more advanced categorical encodings (e.g. frequency or target encoding)
* Explore ensemble methods like XGBoost for better minority class handling
* Containerize with Docker for production deployment

---
