# Report

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model on a dataset of lending data. The goal is to determine how well the model can predict whether a loan will be healthy (low-risk) or non-healthy (high-risk).

## Results

* Imbalanced Model:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384


* Over Sampled Model:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384


## Summary

Overall both the logistic regression models well at 95% or above, imbalanced model at 95% recall, and oversampled model at 99% recal. Therefore, the over sampled model was able to better predict whether a loan will be healthy or non-healthy. 

### Recommendation

I recommend that the company use the oversampled model to predict the risk of loans. The model has a high accuracy score, precision score, and recall score, which mean it is reliable and can be used to make accurate predictions. 
By using the model the company can benefit in the following ways:
* Reduction in risk of loan defaults.
* Faster identification and increased approval of good loans.
* Opportunity to streamlined loan application process.

In conclusion the logistic regression model can prove to be benefical in many ways and can be used to help the company make better decisions about which loans to approve and which loans to reject.