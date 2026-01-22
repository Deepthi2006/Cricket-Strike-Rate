# 🏏 Cricket Strike Rate Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting a cricket player’s **strike rate** using historical batting data. Multiple machine learning models were trained and evaluated, and **XGBoost** was selected as the final model due to its superior predictive performance. A **Flask-based web application** was developed to provide a simple and interactive frontend for real-time predictions.

---

## 🎯 Objective

* Analyze batting performance data
* Train multiple regression models to predict strike rate
* Compare model performance
* Use **XGBoost** for final prediction
* Deploy the model using **Flask** with a user-friendly interface

---

## 📂 Dataset

The dataset contains batting-related features such as:

* Matches played
* Runs scored
* Balls faced
* Fours
* Sixes
* Average
* Other performance metrics

(Target Variable: **Strike Rate**)

---

## 🧠 Machine Learning Models Used

The following models were trained and compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor (SVR)
* **XGBoost Regressor (Final Model)**

### ✔ Why XGBoost?

* Handles non-linear relationships effectively
* Reduces overfitting using regularization
* Delivered the **lowest error and highest accuracy** among all models

---

## ⚙️ Workflow

1. Data Loading & Exploration
2. Data Cleaning and Preprocessing
3. Feature Selection
4. Model Training (Multiple Models)
5. Model Evaluation & Comparison
6. Final Model Selection (XGBoost)
7. Model Serialization
8. Flask Web Application Integration

---

## 🌐 Web Application (Flask)

A Flask-based frontend allows users to:

* Enter player batting statistics
* Submit inputs via a web form
* Instantly receive the **predicted strike rate**

### Technologies Used:

* Flask (Backend)
* HTML & CSS (Frontend)
* Pickle / Joblib (Model loading)

---

## 📁 Project Structure

```
Cricket-Strike-Rate-Prediction/
│
├── data/
│   └── cricket_data.csv
│
├── model/
│   └── xgboost_model.pkl
│
├── app.py
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
├── notebooks/
│   └── model_training.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Flask App

```bash
python app.py
```

### 3️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📊 Model Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

XGBoost showed the best overall performance across all metrics.

---

## 🔍 Key Insights

* Strike rate strongly depends on balls faced and boundary frequency
* Ensemble models outperform traditional regression models
* XGBoost effectively captures complex batting patterns

---

## 🔮 Future Enhancements

* Add player role-based prediction (opener, finisher, all-rounder)
* Deploy using Docker / Cloud platform
* Improve UI with charts and player comparisons
* Use live match data for real-time prediction

---

## 🧾 Conclusion

This project demonstrates an end-to-end machine learning pipeline—from data preprocessing and model selection to deployment using Flask. The use of **XGBoost** ensures accurate predictions, while the web interface makes the solution accessible and practical.

---
