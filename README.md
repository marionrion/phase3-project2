## Lending Club Loan Default Prediction - README
![image](https://github.com/marionrion/phase3-project2/assets/162312622/2531262d-bb54-40ff-8ad1-f18a10af2f93)
This project aims to develop a machine learning model to predict loan defaults on the LendingClub platform. By understanding borrower characteristics and loan details, we can create a more accurate and inclusive creditworthiness assessment system.

### Here's a breakdown of the project structure:
## Business Understanding
Overview: LendingClub connects borrowers and lenders, but traditional creditworthiness assessments can limit access to credit and lead to inefficiencies.
Challenge: Current methods might overlook creditworthy borrowers or lead to inaccurate assessments.
Solution: Machine learning offers a data-driven approach to predict loan repayment behavior and automate credit assessment aspects.
Problem Statement: We aim to build a model that predicts loan defaults using LendingClub's borrower, loan, and repayment data.

### Data Understanding
Source: The LendingClub dataset from Kaggle containing 10,000 observations across 55 variables.
Target Variable: loan_status (paid or defaulted)
Features: Key features include loan amount, term, interest rate, borrower employment details, income verification, and credit history.
![image](https://github.com/marionrion/phase3-project2/assets/162312622/77d6aabc-34bd-429f-a4de-5c82a24f971c)
This image can represent the filtering process based on creditworthiness assessment.

##  Models
The project employs various machine learning models for training and evaluation:

Training Models: Decision Tree, Random Forest, XGBoost
Evaluation Metrics: Classification Report, Precision-Recall Curve (PRC), Area Under the Curve (AUC)

## Results
We identified factors influencing loan defaults, including interest rate, employment length, loan purpose, and loan grade.
The Random Forest model achieved the highest AUC score, indicating its potential for accurate prediction.
Further analysis with F1-score and cost-sensitive learning is recommended for a more informed decision, especially considering class imbalance.

## Recommendations and Conclusion
This study identified borrower characteristics (employment history) and loan details (interest rate) as important factors influencing loan defaults.  Therefore, a Random Forest model could be a valuable tool for lenders to predict such defaults.




















