# customer-churn-prediction-ml
Machine Learning project to predict customer churn using classification models with EDA, preprocessing, and model evaluation.

# Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project aims to predict whether a customer will leave (churn) or stay using machine learning models.

The goal is to help businesses:

Identify high-risk customers

Improve retention strategies

Increase overall profitability

# 🎯 Problem Statement

Given customer demographic and service-related data, predict whether a customer is likely to churn.

This is a binary classification problem:

0 → Customer stays

1 → Customer churns

# 📂 Dataset Information

The dataset contains customer details such as:

Gender

Senior Citizen

Tenure

Monthly Charges

Total Charges

Contract Type

Internet Service

Payment Method

Churn (Target Variable)

# 🛠️ Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

# ⚙️ Project Workflow
1️⃣ Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Splitting into train and test sets

2️⃣ Exploratory Data Analysis (EDA)

Distribution of churn vs non-churn

Tenure analysis

Contract type comparison

Monthly charges impact

3️⃣ Model Building

Implemented and compared:

Logistic Regression

Decision Tree

Random Forest

4️⃣ Model Evaluation

Evaluated using:

Accuracy

Confusion Matrix

Precision

Recall

F1 Score

# 📈 Results

Random Forest performed best among tested models.

Important features influencing churn:

Contract Type

Tenure

Monthly Charges

# 💡 Key Insights

Customers with short tenure are more likely to churn.

Customers on month-to-month contracts have higher churn rates.

Higher monthly charges increase churn probability.

🚀 How to Run This Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git

Install dependencies:

pip install -r requirements.txt

Open the notebook:

jupyter notebook

# 📌 Future Improvements

Hyperparameter tuning

Cross-validation

Deploy model using Streamlit

Add ROC-AUC comparison

Use XGBoost for better performance

# 👨‍💻 About Me

I am currently pursuing MSc in Statistics and building projects in:

Data Analysis

Machine Learning

Python & SQL

Business Intelligence

📌 Actively looking for internship opportunities in Data Analytics / ML.
