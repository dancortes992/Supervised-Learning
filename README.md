# Costumer Churn Prediction
### Background

This project is part of the Tripleten data science practium. Focuses of the project is handling class inbalance in machine learning classification.

## Project Description

This project was tasked with analysis and model building on behalf of hypothetical client "Beta Bank" with the aim of retaining costumers.
Expected **F1 score** for this project is 0.59. Additionally comparison between **AUC-ROC** metric and F1 score was conducted.

## Data

Data provided to train model consists of clients past behaivior and termination of contracts with the bank. Available features in data include:

- RowNumber — data string index
- CustomerId — unique customer identifier
- Surname — surname
- CreditScore — credit score
- Geography — country of residence
- Gender — gender
- Age — age
- Tenure — period of maturation for a customer’s fixed deposit (years)
- Balance — account balance
- NumOfProducts — number of banking products used by the customer
- HasCrCard — customer has a credit card
- IsActiveMember — customer’s activeness
- EstimatedSalary — estimated salary
- Exited — сustomer has left

**Train data split ratio:** 3:1:1

**Models evaluated:** DecisionTreeClassifier, RandomForestClassifier, LogisticRegression

## Findings

AUC-ROC score of 0.85 in relation to F1 score(0.59) relays an over all high quility model capable of reliable predicting true positive classifications.

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, _sklearn_
