# Loan Approval Prediction Using Machine Learning

## Overview

This project uses machine learning to predict whether a loan application will be approved or rejected, based on historical applicant data. The aim is to assist financial institutions in making faster, fairer, and more accurate loan decisions.

## Objectives

- Build a classification model to automate the loan approval process.
- Reduce human bias and increase efficiency in decision-making.
- Explore the impact of different applicant features on approval outcomes.

## Dataset

- Source: Google Drive Dataset Link
- Size: ~600 records
- Target Variable: Loan_Status (Y/N)
- Key Features:
  - Applicant Income
  - Credit History
  - Education
  - Loan Amount
  - No. of dependants, etc.

## Technologies Used

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## ML Models Applied

- Logistic Regression
- Decision Tree
- Random Forest ✅ (Best Performer)
- Support Vector Machine (SVM)

## Results

- Best Accuracy: ~85% using Random Forest
- Top Influencing Features: Credit History, Loan Amount, Income
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score

## Key Insights

- Good credit history and higher income strongly influence approval.
- Graduates and self-employed applicants had slightly better outcomes.
- Loan amount and education level also contributed to model decisions.

## Recommendations

- Deploy the Random Forest model in a production environment.
- Monitor and retrain the model periodically.
- Use explainable AI (e.g., SHAP) for transparency.
- Conduct bias analysis regularly.
- Collect more behavioral and transaction-level data to improve accuracy.

---

## **Connect**
Feel free to reach out with any questions or feedback:
- **Email:** jafar397.mj@gmail.com
---

Thank you for exploring this analysis!
