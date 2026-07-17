#  Customer Churn Prediction

An end-to-end machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, subscribed services, and account information.

---

##  Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project uses machine learning to identify customers who are likely to leave a telecom service, helping businesses improve customer retention strategies.

The complete machine learning workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, cross-validation, feature importance analysis, and model saving.

---

##  Problem Statement

Develop a machine learning model to predict whether a telecom customer will churn using historical customer data.

---

##  Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains **7,043** customer records with demographic information, account details, subscribed services, billing information, and customer churn status.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

##  Project Workflow

1. Problem Definition
2. Data Collection
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Feature Encoding
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Hyperparameter Tuning
11. Cross Validation
12. Feature Importance
13. Save Best Model

---

##  Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

##  Final Model Performance

**Best Model:** Logistic Regression

| Metric | Score |
|---------|-------|
| Accuracy | **80.55%** |
| Precision | **65.63%** |
| Recall | **56.15%** |
| F1 Score | **60.52%** |
| ROC-AUC | **84.22%** |

### Best Hyperparameters

- C = 100
- Penalty = L1
- Solver = liblinear

---

##  Cross Validation Results

| Metric | Average Score |
|---------|---------------|
| Accuracy | **80.35%** |
| Precision | **65.31%** |
| Recall | **55.32%** |
| F1 Score | **59.89%** |
| ROC-AUC | **84.53%** |

---

##  Feature Importance

Feature importance analysis identified the most influential factors affecting customer churn. The results indicate that contract type, internet service, online backup, payment method, and additional service subscriptions play a significant role in predicting customer churn.

---

##  Model Saving

The final Logistic Regression model was saved using the Joblib library for future predictions and deployment.

---

##  Project Structure

```
Customer-Churn-Prediction/
│
├── Customer-Churn-Prediction.ipynb
├── customer_churn_model.pkl
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 🚀 Future Improvements

- Handle class imbalance using SMOTE.
- Experiment with CatBoost and LightGBM.
- Deploy the model using Streamlit or Flask.
- Monitor model performance on new customer data.

---

## 👨‍💻 Author

**Omkar Kavathekar**

If you found this project useful, consider giving it a ⭐ on GitHub.
