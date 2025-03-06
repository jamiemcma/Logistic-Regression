# Logistic-Regression

Logistic Regression was developed to predict the probability of default within a loan portfolio, where default = 1 indicates the a customer has failed to pay the loan obligation while default = 0 reprsents customers who are able to repay their loans.

The model assigns a credit score to new loan applicants. Applicants with a higher score, representing lower credit risk, who are more likely to be eligible for a loan. Meanwhile, for those customers with lower score, indicating higher credit risk, may face rejection.

To enhance the model performance, the Weight of Evidence (WOE) methodonlogy was used to transform and standardize the variables, ensuring better predictive power. Morevoer, Points-to-Double-the-Odds (PDO) approach was used to scale the credit score, for more interpretable and consistent.

The model can be used for credit adjudication, pricing model and line assignment.

Few Steps as shown as below:
1. Input and understand the raw dataset
2. Croast Classing and Fine Classing by using WOE and IV
3. Select the Potential Variables for Model Development
4. Split the Dataset to Train and Test Dataset
5. Model Development
6. Model Performance Evaluation by using KS and GINI
7. Transform the PD to Score Points
8. Portfolio Binning for Score Distribution
9. Implementation of Score


Data source: https://www.kaggle.com/code/banuprakashv/loan-default-prediction-eda-ml
