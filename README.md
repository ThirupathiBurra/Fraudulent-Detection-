Fraud Detection 


Project Overview:-

This project develops a machine learning model to proactively detect fraudulent financial transactions for a financial company. Using a large real-world dataset, the goal is to identify and flag suspicious activities such as account takeovers, unauthorized transfers, and cash-outs.

Dataset:--

The dataset contains over 6.3 million transaction records with the following key features:

step: Time unit in hours (744 steps = 30 days)

type: Transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER)

amount: Transaction amount in local currency

nameOrig: Customer initiating the transaction

oldbalanceOrg / newbalanceOrig: Initial and new balances of the origin account

nameDest: Recipient customer

oldbalanceDest / newbalanceDest: Initial and new balances of the destination account (missing for merchants)

isFraud: Indicator if transaction was fraudulent

isFlaggedFraud: Flag for transfers > 200,000 as potential fraud

Project Structure:--

Data Cleaning: Handling missing values, outliers, and multicollinearity

Exploratory Data Analysis (EDA): Visualizing distributions and fraud patterns

Feature Engineering: Encoding categorical variables, creating balance change and fraud flag features

Model Development: Training and evaluating Logistic Regression, Random Forest, and XGBoost models with class imbalance handling

Model Interpretation: Using SHAP values to identify key fraud predictors

Business Recommendations: Proposing prevention strategies and infrastructure updates

Evaluation Metrics: ROC AUC, Precision, Recall, Confusion Matrix

Technologies Used
Python 3.x

Pandas, NumPy for data processing

Matplotlib, Seaborn for visualization

Scikit-learn for modeling and evaluation

XGBoost for gradient boosting model

SHAP for model interpretability

Google Colab for notebook development


Key Findings
Large transaction amounts and balance changes are strong fraud indicators

Transfers and cash-outs have higher fraud likelihood

Flagging transactions above 200,000 reduces fraud risk effectively

Tree-based models like Random Forest and XGBoost perform best on this task

Recommendations
Implement real-time fraud scoring with alerts for flagged transactions

Use multi-factor authentication for high-risk transaction types

Continuously retrain models with updated data to adapt to new fraud patterns

Integrate fraud detection system into secure and scalable infrastructure

Contact
For any questions or collaborations, please contact:

Thirupathi Burra
burrathirupathi453@gmail.com 
https://www.linkedin.com/in/thirupathi-burra-49658b2a6/
