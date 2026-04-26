# ML-Customer-Churn-Project1
# TeleConnect ML Assignment
##  Project Overview

This project focuses on solving two business problems:

* Predict customer churn (Classification)
* Forecast monthly revenue (Regression)

---

##  Dataset

* Source: Kaggle Telco Customer Churn Dataset
* Records: 7043 customers
* Features: 21

---

##  Workflow

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing & Feature Engineering
3. Classification Models
4. Regression Models
5. Model Interpretation (SHAP, PDP)

---

##  Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* SVM
* KNN

---

##  Results

* Best Classification Model: Random Forest

* ROC-AUC Score: ~0.92

* Best Regression Model: Random Forest Regressor

* RMSE:~ 1.5

---

##  Key Insight

Customers with short tenure and high monthly charges are more likely to churn.
Long-term customers tend to generate stable revenue.

---

##  Libraries Used

pandas, numpy, matplotlib, seaborn, scikit-learn, shap

---

##  Project Structure

ML-Customer-Churn-Assignment/
├── data/
├── notebooks/
│   ├── churn_classification.ipynb
│   ├── revenue_regression.ipynb
├── report.pdf
├── requirements.txt
└── README.md

---

##  How to Run

pip install -r requirements.txt
jupyter notebook

---

##  Notes

* Make sure notebooks run without errors
* Update RMSE value before submission
* Keep repository public
