# credit-risk-classification
module 20
## Overview
This project aims to predict the credit risk associated with loans using a logistic regression model. The goal is to classify loans as either healthy (0) or high-risk (1) based on various financial indicators.
## Installation
To run the project, ensure you have the necessary libraries installed:
```bash
pip install -r requirements.txt

### 4. **Usage**
```markdown
## Usage
Load the Jupyter notebook and run the cells to train the model and evaluate its performance.
## Analysis

### Overview of the Analysis
The purpose of this analysis is to build a machine learning model to predict the credit risk of loans. By using logistic regression, the goal is to determine whether a loan is healthy or at high risk of defaulting.

### The Results
Accuracy Score: 0.99
Precision Score (Class 0): 1.00
Recall Score (Class 0): 1.00
Precision Score (Class 1): 0.86
Recall Score (Class 1): 0.91

The model was evaluated based on these metrics to determine its effectiveness in predicting loan statuses.

### Summary
The logistic regression model does a good job predicting the 0 (healthy loan) label, with high precision and recall, indicating that it correctly identifies most of the healthy loans without too many false positives.

For the 1 (high-risk loan) label, the performance might be slightly less accurate, depending on the precision and recall scores. If recall is lower, the model is missing some high-risk loans, and if precision is lower, it's incorrectly tagging some healthy loans as high-risk.

Overall, the F1-scores for both labels are reasonably balanced, suggesting that the model is effective in predicting both healthy and high-risk loans.

Given the accuracy, precision, and recall scores, the model is recommended for use in identifying potential credit risks. If the model's performance for high-risk loans meets the company's threshold, it can be deployed for risk management. Otherwise, further model tuning or alternative algorithms might be considered.

## Conclusion
The logistic regression model provides a balanced performance for predicting both healthy and high-risk loans. This analysis demonstrates the potential of machine learning models in credit risk management.

## References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

### Acknowledgment
I received assistance from ChatGPT for coding and formatting in this project. The guidance provided helped streamline the development process and improve the overall presentation of the results.
