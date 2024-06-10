## Lending Club Loan Default Prediction - README
![image](https://github.com/marionrion/phase3-project2/assets/162312622/2531262d-bb54-40ff-8ad1-f18a10af2f93)

This project aims to develop a machine learning model to predict loan defaults on the LendingClub platform. By understanding borrower characteristics and loan details, we can create a more accurate and inclusive creditworthiness assessment system.

### Here's a breakdown of the project structure:
## Business Understanding
Overview: 
LendingClub connects borrowers and lenders, but traditional creditworthiness assessments can limit access to credit and lead to inefficiencies.
Challenge: 
Current methods might overlook creditworthy borrowers or lead to inaccurate assessments.
Solution:
Machine learning offers a data-driven approach to predict loan repayment behavior and automate credit assessment aspects.
Problem Statement: We aim to build a model that predicts loan defaults using LendingClub's borrower, loan, and repayment data.

## Exploring the Data
### Dataset Source
My dataset comprises 10,000 observations, encompassing 55 variables detailing borrower attributes, loan characteristics, and repayment history.

### Target Variable
My target variable, loan_status, signifies whether a loan has been paid or defaulted.

### Key Features
I examined a range of features including loan amount, term, interest rate, borrower employment details, income verification, and credit history.

Features: Key features include loan amount, term, interest rate, borrower employment details, income verification, and credit history.
![image](https://github.com/marionrion/phase3-project2/assets/162312622/77d6aabc-34bd-429f-a4de-5c82a24f971c)
This image represent the filtering process based on creditworthiness assessment.

## Model Selection and Evaluation
### Training Models
I employed a suite of machine learning algorithms including Decision Trees, Random Forests, and XGBoost to train our predictive models.

### Evaluation Metrics
My model performance is assessed using various metrics such as the Classification Report, Precision-Recall Curve (PRC), and the Area Under the Curve (AUC).

### Insights and Recommendations
Identified Factors
I uncovered key factors influencing loan defaults, including interest rates, employment history, loan purpose, and loan grades.

### Model Performance
My analysis reveals that the Random Forest model outperforms others, offering the highest AUC score and potential for accurate prediction.

### Future Recommendations
Further analysis with metrics like the F1-score and exploration of cost-sensitive learning techniques are recommended to address class imbalance and enhance model robustness.

## Conclusion
This project underscores the importance of leveraging machine learning for creditworthiness assessment, offering lenders valuable insights into borrower behavior and improving decision-making processes. With the right tools and techniques, we can empower lenders to make informed, data-driven decisions, ultimately leading to better outcomes for both lenders and borrowers.




















