# PRODIGY_DS_03
Decision Tree model to predict customer subscription behavior using the Bank Marketing dataset. Built as part of the Prodigy InfoTech Data Science Internship.


# Task-03: Decision Tree Classifier – Bank Marketing Dataset

## 🎯 Objective
Build a Decision Tree model to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data.

## 📁 Dataset
- Source: [UCI Bank Marketing Dataset](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)
- File: `bank.csv`
- Features include: age, job, marital status, education, balance, duration of contact, etc.
- Target: `y` (yes/no for subscription)

## 📊 Tools Used
- Python
- Scikit-learn
- Pandas, Seaborn, Matplotlib
- Google Colab

## 🧠 Methods
- Label encoding for categorical features
- Decision Tree Classifier (entropy criterion)
- Train-test split (80-20)
- Performance metrics: Accuracy, Classification Report, Confusion Matrix
- Tree visualization

## 📈 Results
- Accuracy: 90.2%
- Precision (positive class): 57%
- Recall (positive class): 38%
- Model performs well for negative class (non-subscribers), but could be improved for positive class

## ✅ Status
Task completed as part of the Data Science Internship at **Prodigy InfoTech**
