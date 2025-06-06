# Loan-default-risk-prediction

## Overview

This project focuses on building a predictive model to assess the likelihood that a borrower will default on a loan. Using key financial and personal features such as income, loan amount, credit score, interest rate, and Debt-to-Income (DTI) ratio, the model aims to provide accurate risk assessments to support lending decisions.

## Dataset

The dataset includes borrower financial attributes and loan information, enabling the prediction of loan repayment outcomes.

## Features Used

- Income
- Loan Amount
- Credit Score
- Interest Rate
- Debt-to-Income Ratio (DTI)

## Methodology

- Data preprocessing and exploratory data analysis (EDA) to understand feature distributions and correlations.
- Feature engineering to enhance model input quality.
- Model selection based on performance metrics such as accuracy, precision, recall, and AUC.
- Final model validation on a test set to ensure generalizability.

## Results

The best performing model achieved an accuracy of **88.37%** in predicting loan default risk, demonstrating strong potential for practical application in financial risk assessment.

## Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib, Seaborn

## Usage

1. Clone the repository.
2. Open the Jupyter notebook `Loan_default_risk_prediction.ipynb` to explore the complete analysis and modeling process.
3. Modify and run the notebook cells to experiment with different models or datasets.

## Future Work

- Incorporate additional features such as employment history and credit utilization.
- Experiment with advanced models like neural networks.
- Deploy the model as a web service for real-time risk prediction.
