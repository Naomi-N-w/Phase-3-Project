# Phase-3-Project
## Overview
The goal of this project is to predict whether a bank customer will subscribe to a term deposit using historical marketing campaign data.

## Business and Data Understanding
#### Objectives
 + Identify key factors  in the customer's attributes influencing subscription likelihood
 + Assess and  identify key factors  in the campaign's attributes influencing subscription likelihood.
 + Accurately predict subscription behavior using machine learning

#### Stakeholders
+ Marketing Team: Optimize campaign targeting and messaging strategies.
+ Sales Executive: Increase conversion rates and ROI from outreach efforts.
+ Data Analysts: Build and evaluate predictive models; uncover meaningful customer patterns.

#### Dataset
+ Source: Kaggle – Bank Marketing Campaign Dataset
+ Features: 16 input features + 1 target (deposit)
 #### Key Variables:
 + Customer’s attribute  :(age, job, marital status, education balance, loan, housing)
 + Campaign details :(contact method, duration, previous outcomes, day/month)

## Modelling
 ##### Models Used:
   + Logistic Regression 
   + Decision Tree  to enhance accuracy
   + Ridge and Lasso regularization


## Evaluation
![image](https://github.com/user-attachments/assets/399092d7-1d38-478a-989b-aaf3b858ae25)
![image](https://github.com/user-attachments/assets/b6b06202-ffef-4780-a2bf-3f4958e82b01)
![image](https://github.com/user-attachments/assets/de3daf4a-b852-488e-b980-0f6686026a50)
![image](https://github.com/user-attachments/assets/e4118dc2-defa-4a0c-a86f-0e8df5c9a03d)
+ Logistic Regression: Good interpretation and performance.
+ Decision Tree: Best overall performance, strong ROC-AUC.

## Conclusions
+ Predicting whether a customer will subscribe to a term deposit was successfully addressed using a Decision Tree model.
+ The model was able to correctly predict customer behavior 79%(ROC-AUC) of the time, and it was very good at telling the difference between people who would and wouldn’t subscribe to a term deposit.
+ The precision and recall scores show that the model performs well in identifying both positive and negative classes.This helps avoid wasting time on the wrong people and increases the chances of getting real subscribers








