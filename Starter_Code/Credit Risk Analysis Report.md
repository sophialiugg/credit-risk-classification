# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
   - The purpose of this analysis is to create a model for credit risk classifications that can identify the credit worthiness of borrowers, in addition to predict whether a loan is likely to be a healthy loan or a high-risk loan.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
   - loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.
* Describe the stages of the machine learning process you went through as part of this analysis.
   - Begin with data cleaning and exploratory analysis with the data. Then, select the x and y for testing and split by training and testing data. Next, fit the model and evaluatethe accuracy of test samples.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
   - Logistic Regression Model was used.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
       - Accuracy Score : 99%
       which means that the model correctly predicts the loan labels 99% of the time
       - Precision Score: 92% 
       which suggests that 92% of predicted positives were correct
       - Recall Score: 95% 
       whcih suggests that the model was 95% precise in measuring true positive values our of all positive predictions made
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 

   - Overall, the logistic regression model demonstrates strong predictive performance for both healthy and high-risk loans, with high precision and recall values for both healthy and high-risk loans. The model predicts both '0's and '1's with 99% accuracy. Therefore, I would recommend on using the Logistic Regression Model. Also, it seems more vital to accurately predict high-risk loans than to correctly predict healthy loans in this particular instance. 


