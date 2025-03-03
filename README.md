# Credit Risk Analysis Report

## Overview of the Analysis
This analysis aims to assess the effectiveness of a logistic regression model in predicting credit risk. By leveraging loan data, the model determines whether a loan is **healthy (0)** or **high-risk (1)** based on various financial factors. The goal is to evaluate the model's accuracy and reliability to support informed decision-making in loan approvals.

## Results
- **Accuracy Score:** 99%
- **Healthy Loans (`0`) Performance:**  
  - Precision: 1.00 (100%)
  - Recall: 0.99 (99%)
  - F1-score: 1.00 (100%)
- **High-Risk Loans (`1`) Performance:**  
  - Precision: 0.84 (84%)
  - Recall: 0.94 (94%)
  - F1-score: 0.89 (89%)

## Summary
The logistic regression model demonstrates high accuracy (99%), effectively identifying healthy loans with 100% precision and 99% recall. It also performs well in detecting high-risk loans, achieving 84% precision and 94% recall. However, the slightly lower precision for high-risk loans indicates some **false positives, meaning a few healthy loans are misclassified as high-risk.

### Recommendation
While the model is effective, its lower precision for high-risk loans could lead to unnecessary rejections. If the goal is to minimize false positives, optimization should be considered.

