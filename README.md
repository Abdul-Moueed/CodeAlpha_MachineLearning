# Credit Scoring Model

## Overview

This project predicts an individual's creditworthiness using historical financial data. Machine Learning classification algorithms are applied to analyze financial behavior and determine whether a person is likely to be a good or bad credit risk.

## Objective

To build a machine learning model that can classify individuals as creditworthy or non-creditworthy based on their financial history.

## Features Used

- Income
- Debt
- Loan Amount
- Payment History
- Credit Utilization
- Savings
- Employment Length
- Credit History Length

## Feature Engineering

Additional features were created to improve model performance:

- Debt-to-Income Ratio
- Loan-to-Income Ratio
- Payment Reliability Score
- Savings Coverage Ratio

## Machine Learning Algorithms

The following classification algorithms were used:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 84% |
| Decision Tree | 86% |
| Random Forest | 88% |

Random Forest achieved the highest performance and was selected as the final model.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
CodeAlpha_MachineLearning/
│
├── dataset/
│   └── credit_data.csv
│
├── src/
│   └── credit_scoring_model.py
│
├── README.md
├── requirements.txt
└── LICENSE
```

## Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Handling Imbalanced Data using SMOTE
- Model Deployment with Streamlit
- Explainable AI using SHAP

## Conclusion

This project demonstrates how machine learning can be used to assess credit risk and support financial institutions in making data-driven lending decisions.

## Author

Abdul-Moueed

CodeAlpha Machine Learning Internship
