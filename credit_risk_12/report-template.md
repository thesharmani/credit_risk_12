# Module 12  

# Background

Lending companies provide loans to borrowers with the expectation that the borrower will either return the loaned asset or pay back the loan. If a borrower does not fulfill these expectations, it can result in a loss for the lender, known as credit risk. In this analysis,  machine learning is used to analyze data from a peer-to-peer lending company to build a model that can predict the likelihood that a borrower will be able to repay a loan or return a loaned asset.

# Analysis

A machine learning model was used to classify loans as either low-risk or high-risk based on the loan status provided by the lending company. Logistic regression was utilized for this task, as it is well-suited for predicting probabilities of a target variable in classification problems. 

After training the model on the lending company's dataset, it was determined that the model performs better at predicting low-risk loans than high-risk loans. This discrepancy is likely due to imbalanced class distribution in the dataset, with more low-risk loans than high-risk loans.

Creation of a Logic Regression Model with the oversampled data proved more accurate. 

## Results


* Machine Learning Model 1:
  * The model generated an accuracy score of 95%



* Machine Learning Model 2:
  * The model generated an accuracy score of 99%

## Summary

The logistic regression model trained on oversampled data performed better than the model trained on imbalanced data. This is because the oversampled data was balanced, resulting in a higher accuracy score and a higher recall for non-healthy loans. This indicates that the model is less likely to make mistakes when classifying high-risk loans.
