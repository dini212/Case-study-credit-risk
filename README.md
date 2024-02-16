# Case Study of Credit Risk 


## Introduction
A lending credit risk analysis is a final task of Rakamin Academy id/x partners data scientist project based internship program. The goal of this task is to apply the knowledge for real world as junior data scientist.
In this scenario, I have been tasked with building a model to predict credit risk using a dataset provided by the company, consisting of both accepted and rejected loan data. Additionally, I am responsible for preparing visual media to present the solution to the client. The following steps of building model prediction : preprocessing data, modeling data, and evaluation. The dataset is from website of Rakamin Academy.

## Background

Credit risk analysis is a process to asses borrower’s ability to repay a loan or credit. In this project, the analysis conducted build predictive models to determine individuals who are likely to repay loans or credit. Two models, namely Random Forest and XGBoost, are utilized for comparison. Additionally, an examination of which serve as the most important features for predicting credit risk will be conducted.

## Dataset

The dataset to be used in this project contains information about issued loans. It comprises 73 variables, but not all of them will be used. Those with high cardinality or those with only one unique value will be discarded. This is to prevent overfitting of the model and inefficiencies in computation.


## Preprocessing

Preprocessing is conducted to reselect the data to be used and eliminate unsuitable data. This ensures that the data to be used is easier to process by models such as Random Forest and XGBoost. In this project, data preprocessing will involve format conversion and handling missing values.

## Modelling

Model that will be used are Random Forest and XGBoost. And for the evalution will use AUC Score and Kolmogorov-Smirnov (KS).

<img width="374" alt="image" src="https://github.com/dini212/Case-study-credit-risk/assets/62368732/534b6802-ef80-4526-8c39-bfefe07543e7"> <img width="362" alt="image" src="https://github.com/dini212/Case-study-credit-risk/assets/62368732/05ff3686-df7e-4821-b53c-789cc06b4ac7"> <img width="361" alt="image" src="https://github.com/dini212/Case-study-credit-risk/assets/62368732/3c10ac80-f586-48b3-95fe-46eb63d4aad1">



## Conclusion

1.	Based on the evaluation metrics, XGBoost model generally outperformed the Random Forest model in terms of predictive accuracy. The higher AUC score model suggests that XGBoost model provides better discrimination between the positive and negative classes, making it more effective in distinguishing between creditworthy and non-creditworthy borrowers. However, it's important to consider other factors before making the final decision.
2.	Variable recoveries has a high level of importance in the both models of XGBoost and Random forest. This indicates that the amount recovered from previously problematic loans can greatly influence the predictions made by the model.
3.	A KS score of 0.57 indicates that the model has a moderate to good dicriminatory power in distinguishing between high-risk and low-risk groups.

