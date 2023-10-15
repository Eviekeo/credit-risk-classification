# credit-risk-classification

## Overview of the Analysis

The purpose of the analysis was to assess the performance of the logistic regression model in respect to predicting whether the credit risk of a loan (i.e. healthy or high-risk). 
The data was based on the following financial information; loan size, interest rate, borrower income, total debt, number of accounts held, derogatory marks and debt to income ratio. As part of the assessment, we were required to predict the credit risk of the particular loan, that is whether it was healthy (0) or a high risk (1) loan.  

The stages of machine learning that were relevant to this analysis are listed below:
1. Data splitting: splitting the data into testing and training datasets
2. Model creation: creating a logistic regression model using the inital data
3. Predicting: after fitting the model using the training data, it is used to make predictions.
4. Evaluating: the performance of the model is assessed based on its ability to predict. It is assessed against the test values. The following scores are used as part of this evaluation: accuracy, precision and recall.  

This assessment utilises the logisitic regression method.

## Results
- Accuracy: the model achieved an overall accuracy score of 0.99 which indicates that the model was able to correctly classify 99% of cases. 
- Precision: the model scored 1.00 and 0.87 for healthy and high risk loans respectively, which suggests that the model is very good at prediciting true positives for healthy loans. The lower score for high risk loans indicates that the model predicts some false positives, more so for high risk loans than for healthy loans.
- Recall: the model scored 1.00 and 0.89 for healthy and high risk loans respectively. This suggests that it detects less false negatives for healthy loans than it does for high risk loans, however it is noted that the model still performs well for both classes.
        

## Summary
The problem we would be trying to solve would be to predict high risk loans so that preventative measures could be implemented, or to help us identify which loans require closer monitoring for risk of default. As such, it is more important to predict 1's than 0's. The model demonstrates strong predictive capabilities for healthy loans, as evident from the scores discussed above. Moreover, it performs commendably in predicting high-risk loans, albeit with slightly lower precision and recall scores compared to healthy loans. Overall, the model has a high accuracy score of 0.99. Considering these insights, I would recommend this model to be used. 
