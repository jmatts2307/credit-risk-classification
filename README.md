# credit-risk-classification

Overview of the Analysis:

This analysis aims to assess loan risk by training a logistic regression model on lending data. The goal is to predict whether a loan is healthy (0) or high-risk (1) based on various borrower financial information. This helps financial institutions make informed lending decisions and limit financial risks. 

Financial Data Overview:

This dataset includes:
-Loan Size - The amount of money borrowed.

-Interest Rate - The rate charged on the loan.

-Borrower Income - The annual income of the borrower.

-Debt-to-Income Ratio - The borrower's debt as a proportion of their income.

-Number of Accounts – The number of credit accounts held by the borrower.

-Derogatory Marks – Negative indicators on the borrower’s credit history.

-Total Debt – The total outstanding debt of the borrower.


Target Variable:

Loan status where:
- 0 = Healthy Loan (low risk)

- 1 = High-Risk Loan (likely to default)


Machine Learning Process:

1. Data Preprocessing:
- separated features (X) from the target variable (y).

- split the data into training (75%) and testing (25%) sets.

2. Model Selection and Training:
- used Logistic Regression due to its effectiveness in binary classification problems.

- trained the model on the training dataset (X_train, y_train).

3. Model Evaluation:
- generated predictions on the original dataset (X_test).

-evaluated performance using accuracy, precision, recall, and F1-score.

-used a confusion matrix and a classification report to assess model effectiveness.


Results:

Accuracy: The model correctly predicts loan status in 99% of cases.

Precision: 
-Healthy Loan (0):  100%
-High-Risk Loan (1): 87%

Recall:
-Healthy Loan (0): 100%
-High-Risk Loan (1): 95%

F1-score:
-Healthy Loan (0): 100%
-High-Risk Loan (1): 91%



Summary:

The logistic regression model displays high accuracy and strong classification performance, especially when identifying healthy loans with 100% precision and recall. The model however slightly underperforms in predicting high-risk loans with 87% precision, but its 95% recall ensures that most high-risk loans are accurately identified. 

Recommendation:

The logistic regression model in highly effective for credit risk classification, and therefore should be utilized for lending decisions as it correctly classifies most loans. Possible further improvements could be to try alternative models such as Neural Networks for comparison. 

