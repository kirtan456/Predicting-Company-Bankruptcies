📌 Overview

This project focuses on predicting whether a company is likely to go bankrupt using machine learning techniques. Bankruptcy prediction is an important financial risk assessment task that helps investors, banks, and organizations make informed decisions.

The project includes data preprocessing, exploratory data analysis (EDA), feature selection, handling class imbalance, model training, hyperparameter tuning, and performance evaluation to identify the most effective predictive model.

🎯 Objectives
Predict whether a company will go bankrupt.
Perform comprehensive data preprocessing.
Handle class imbalance using resampling techniques.
Compare multiple machine learning models.
Improve prediction performance through feature selection and hyperparameter tuning.
Evaluate models using appropriate classification metrics.
📂 Dataset Information
Rows: 6,819
Columns: 96
Target Variable: Bankrupt?
Problem Type: Binary Classification
🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Imbalanced-learn (SMOTE, NearMiss)
📊 Exploratory Data Analysis (EDA)

The project includes:

Dataset overview
Missing value analysis
Duplicate value checking
Feature distribution analysis
Correlation heatmap
Pair plots
Violin plots
Class imbalance visualization

⚙️ Data Preprocessing

The preprocessing pipeline includes:

Handling missing values
Removing duplicate records
Low variance feature removal
Correlation-based feature selection
Train-Test Split
Handling imbalanced data using:
SMOTE
NearMiss

🤖 Machine Learning Models

The following models were implemented and compared:

Logistic Regression
Random Forest Classifier
XGBoost Classifier
🔍 Hyperparameter Tuning

The project uses GridSearchCV to optimize model parameters for improved performance.

📈 Evaluation Metrics

The models are evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
