# Credit Risk Analysis Project

## Overview
This project focuses on predicting loan default risk using machine learning and data analytics techniques.  
A large-scale financial dataset containing **100,000 observations** and **18 variables** was analyzed to classify loans as either:

- Fully Paid
- Charged Off

The project includes:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Predictive Modeling
- Model Evaluation & Comparison

---

## Project Objectives
The main objectives of this project are:

- Analyze borrower financial behavior
- Detect patterns related to loan default risk
- Build predictive machine learning models
- Compare model performances using multiple evaluation metrics
- Identify the most important financial risk indicators

---

## Dataset Information

- **Rows:** 100,000
- **Columns:** 18
- **Target Variable:** Loan Status

### Important Features
- Credit Score
- Annual Income
- Monthly Debt
- Current Loan Amount
- Current Credit Balance
- Maximum Open Credit
- Number of Open Accounts
- Bankruptcies
- Tax Liens

---

## Technologies & Libraries Used

### Programming Language
- Python

### Data Analysis & Visualization
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn

---

## Data Preprocessing Steps

Several preprocessing operations were applied before model training:

### Data Cleaning
- Removed unnecessary spaces
- Converted object columns into numeric format
- Cleaned financial string values
- Removed high-cardinality ID variables

### Missing Value Handling
- Median imputation
- Missing value analysis

### Feature Engineering
- One-hot encoding
- Binary target mapping
- Feature alignment

### Scaling
- StandardScaler applied for SVM

---

## Exploratory Data Analysis (EDA)

The dataset was explored using:

- Descriptive statistics
- Histograms
- Boxplots
- Correlation analysis
- Class distribution analysis
- Group comparisons by loan status

### Key Findings
- Financial variables contain significant outliers
- Dataset is moderately imbalanced
- Credit Score strongly affects default risk
- Random Forest identified financial variables as dominant predictors

---

## Machine Learning Models

Three different predictive analytics algorithms were implemented:

### 1. Logistic Regression
Baseline classification model for credit risk prediction.

**Performance**
- Accuracy: ~82%
- ROC-AUC: ~0.73

### 2. Random Forest
Ensemble-based classification algorithm.

**Performance**
- Accuracy: ~82%
- ROC-AUC: ~0.80

### 3. Support Vector Machine (SVM)
RBF-kernel based classification model.

**Performance**
- Accuracy: ~82%
- ROC-AUC: ~0.69

---

## Best Performing Model

### Random Forest achieved the strongest overall performance.

Reasons:
- Highest ROC-AUC score
- Better nonlinear pattern detection
- Strong classification stability
- Better discrimination between risky and non-risky borrowers

---

## Feature Importance

Top variables affecting credit risk prediction:

1. Credit Score
2. Current Loan Amount
3. Monthly Debt
4. Maximum Open Credit
5. Current Credit Balance
6. Annual Income

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- ROC-AUC
- Confusion Matrix
- Classification Report
- ROC Curves

---

## Project Structure

```bash
Credit-Risk-Analysis/
│
├── data/
├── notebooks/
├── images/
├── models/
├── README.md
└── requirements.txt

## 👨‍💻 Author

**Sami Sevdi**  
Industrial Engineering Student  
Interested in Data Science, Machine Learning, and Predictive Analytics
