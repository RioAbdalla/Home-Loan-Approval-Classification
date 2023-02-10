# Home Loan Approval Classification
## Summary
The data consisted of a dummy data applicant's socioeconomic characteristics. The data originated from kaggle.com, which is accessible to the public. Multiple columns are both numerical and categorical. Numerical values are unstandardized and categorical data are not encoded.
## Objective
To determine approval of home loans based on their loaner's socioeconomic characteristics, BRI needs an example to later predict with their data and parameter.
## Problem Definition
To determine approval of a home loan, many parameters are needed. With many available, Kaggle has shown a starting point on which parameters should be used. Although further parameter analysis is required, Kaggle data is sufficient to demonstrate the classification model's capabilities.  In this case, BRI needs an example of how to do a classification model. With Kaggle data, it is a starting point for them to determine parameters and show classification model capabilities. Later, BRI is expected to be able to do the same with more parameters and better results.
## Steps
1. EDA
2. Fill missing values, nan values, and delete duplicate data
3. Encode and One hot key categorical values
4. standarize numerical values
5. Check correlation for feature analysis
6. Vanilla modeling with logistic regression
7. Model evaluation with Random Forest 
8. Model evaluation with XGBoost
9. ROC/AUC Curve Evaluation
## Results
Model able to predict Home Loan Approval with 77% Accuracy, F1 Score of 84%, and a better prediction than random(ROC/AUC Curve)
