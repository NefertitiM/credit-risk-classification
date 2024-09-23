# Credit Risk Classification

A lending activity dataset from a peer-to-peer lending services company was used to build a logistic regression model that identifies the credit risk of borrowers.

The logistic regression model has shown an overall accuracy of 99% in predicting healthy (0) and high-risk (1) loans.

- **Healthy loans** are predicted with:
  - Precision: 1.00
  - Recall: 0.99
- **High-risk loans** are predicted with:
  - Precision: 0.86
  - Recall: 0.94

There is a large discrepancy in sample size between the two types of loans in the "support" column. This may explain the lower precision and recall values for high-risk loans (0.86,0.94) in comparsion to the perfect precision and nearly perfect recall score for healthy loans; having more samples to evaluate may raise that score.

The high accuracy and F1 scores suggest that the model is reliable in distinguishing between healthy and high-risk loans.

Overall, the accuracy of this model is 99%, and the macro and weighted averages are also above 90%, making this an excellent model for evaluating loan risk. I would highly recommend any company adopt this model into their business.
