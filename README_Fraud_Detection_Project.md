
# Fraud Detection Using Machine Learning

## Overview
This project builds a machine learning system to detect fraudulent financial transactions using the IEEE-CIS Fraud Detection dataset. 
The goal is to identify suspicious transactions by analyzing transaction patterns and behavioral signals.

The project demonstrates a full data science workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## Project Objectives
- Detect fraudulent transactions using machine learning models
- Handle highly imbalanced fraud data
- Compare multiple models
- Evaluate models using proper classification metrics

---

## Dataset

Dataset used: **IEEE-CIS Fraud Detection Dataset**

Files:
- train_transaction.csv
- train_identity.csv

Target variable:

isFraud  
0 → Legitimate transaction  
1 → Fraudulent transaction

---

## Project Workflow

### 1. Data Loading
Transaction and identity datasets are merged using:

TransactionID

---

### 2. Data Preprocessing
Steps performed:

- Handling missing values
- Removing high-missing columns
- Encoding categorical variables
- Feature scaling
- Feature selection

---

### 3. Exploratory Data Analysis

Key analyses:

- Fraud vs non-fraud distribution
- Transaction amount patterns
- Missing value analysis
- Correlation analysis

---

### 4. Handling Imbalanced Data

Fraud datasets are highly imbalanced. The project addresses this using:

- Class weighting
- F1-score evaluation
- Precision / Recall analysis

---

## Machine Learning Models

Models implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- CatBoost

Tree-based ensemble models typically perform best for fraud detection tasks.

---

## Model Evaluation

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

Important metric:

F1-score

because fraud detection datasets are highly imbalanced.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

Fraud_Detection_Project
│
├── Fraud_Detection_Project.ipynb
├── train_transaction.csv
├── train_identity.csv
└── README.md

---

## Key Insights

- Fraud detection datasets are extremely imbalanced
- Tree-based ensemble models perform best
- Feature engineering significantly improves fraud detection

---

## Future Improvements

Possible improvements:

- Deep learning models
- Advanced feature engineering
- Real-time fraud detection pipelines
- Deployment as an API service

---

## Author

Junior Data Scientist / Data Engineer

Passionate about machine learning, data pipelines, and building intelligent data-driven systems.
