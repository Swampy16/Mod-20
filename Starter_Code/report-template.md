# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The primary objective of this analysis was to build a machine learning model capable of predicting the risk associated with loans based on various financial indicators. This model aims to assist financial institutions in assessing loan applications by identifying potentially high-risk borrowers, thereby minimizing defaults and improving overall portfolio performance.

## Results 

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Accuracy Score: 0.99
The model correctly predicts 99% of the loan statuses in the testing dataset.
Precision (for healthy loans - 0): 1.00
The model has perfect precision for predicting healthy loans, indicating that all predicted healthy loans are indeed healthy.
Recall (for healthy loans - 0): 1.00
The model correctly identifies all actual healthy loans, with no healthy loans missed.
Precision (for high-risk loans - 1): 0.87
The model predicts high-risk loans with 87% accuracy, meaning 13% of predicted high-risk loans are actually healthy.
Recall (for high-risk loans - 1): 0.94
The model successfully identifies 94% of all actual high-risk loans, missing 6% of them.
F1-Score (for high-risk loans - 1): 0.90
This score reflects a good balance between precision and recall for high-risk loans, indicating strong model performance.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The Logistic Regression model appears to be the best performing model based on the analysis. It achieved an accuracy score of 0.99, which indicates that it correctly predicted 99% of the loan statuses in the testing dataset. Additionally, the model demonstrated perfect precision and recall for healthy loans (0) and maintained good precision and recall for high-risk loans (1), with scores of 0.87 and 0.94, respectively.

If you do not recommend any of the models, please justify your reasoning.
