# Module 12 Report Template

## Overview of the Analysis

* Purpose of the analysis:
    * To predict the likelihood of a loan being high-risk (defaulting), using a logistic regression model of machine learning. The dataset contains information on various loans, and the model aims to classify these loans as either healthy (0) or high-risk (1).

## Results
**Confusion Matrix**
![]()
- True Negatives (TN): 14,924 (healthy loans correctly classified)
- False Positives (FP): 77 (healthy loans incorrectly classified as high-risk)
- False Negatives (FN): 31 (high-risk loans incorrectly classified as healthy)
- True Positives (TP): 476 (high-risk loans correctly classified)

**Classification Report**
![]()
- Precision:
  - Class 0 (healthy loan): 1.00
  - Class 1 (high-risk loan): 0.86
- Recall:
  - Class 0 (healthy loan): 0.99
  - Class 1 (high-risk loan): 0.94
- F1-Score:
  - Class 0 (healthy loan): 1.00
  - Class 1 (high-risk loan): 0.90
- Support:
  - Class 0 (healthy loan): 15,001
  - Class 1 (high-risk loan): 507
    
**Overall Metrics**
  - Accuracy: 0.99
  - Macro Average:
      - Precision: 0.93
      - Recall: 0.97
      - F1-Score: 0.95
  - Weighted Average:
      - Precision: 0.99
      - Recall: 0.99
      - F1-Score: 0.99
     
**Interpretation**
 -Class 0 (healthy loan): The model performs exceptionally well, with a precision, recall, and F1-score of 1.00, indicating that it almost perfectly identifies healthy loans. 

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
Perhaps using alternative models such as Random Forest, or Isolation Forest, which is designed to detect outliers potentially creating an improved detection of high-risk loans.  Another attempt to improve high-risk loan predicting could be to add another feature or features to the loan data set.  There are several data tuning methods and models which could be used.  A best practice approach to any data set may be to 'get to know' and understand the data set well, and clearly define what the purpose of the analysis is. 
