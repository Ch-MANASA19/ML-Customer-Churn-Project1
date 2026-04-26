TeleConnect ML Assignment
📌 Project Overview

This project presents an end-to-end machine learning solution for analyzing customer behavior, with a focus on churn prediction and revenue forecasting.

The assignment is structured across multiple stages and has been implemented using two well-organized notebooks for clarity and modular execution.

📊 Dataset
Telco Customer Churn Dataset (Kaggle)
Total Records: 7043
Features: 21
⚙️ Implementation Details
📘 01_EDA.ipynb

This notebook focuses on initial data exploration and visualization:

Data loading and inspection
Churn distribution analysis
Feature-level exploration
Visual insights using plots and charts
📘 02_preprocessing.ipynb

This notebook covers the core machine learning pipeline:

🔹 Data Preprocessing
Handling missing values
Data type transformations
Encoding categorical variables
🔹 Classification — Churn Prediction
Logistic Regression
Random Forest
Evaluation using Accuracy and ROC-AUC
🔹 Regression — Revenue Forecasting
Linear Regression
Random Forest Regressor
Evaluation using RMSE
🔹 Model Interpretation & Business Recommendations
Feature importance analysis
Identification of key churn drivers
Actionable business insights derived from model outcomes
🏆 Results
Best Classification Model: Random Forest (ROC-AUC ≈ 0.92)
Best Regression Model: Random Forest Regressor
RMSE: ~1.5
💡 Key Insights
Customers with shorter tenure show a higher likelihood of churn
Higher monthly charges correlate with increased churn probability
Long-term customers contribute significantly to stable revenue streams
📁 Project Structure
01_EDA.ipynb
02_preprocessing.ipynb
report.pdf
requirements.txt
README.md
▶️ How to Run

pip install -r requirements.txt
jupyter notebook
