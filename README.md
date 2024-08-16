**Credit Risk Analysis Report
**
Overview of the Analysis
This analysis aims to create a machine learning model to predict if a borrower might default on a loan. The model uses past loan data to classify loans as either "healthy" or "high-risk." This helps the company manage credit risk, make better lending decisions, and reduce financial losses.

Model Performance
Here are the key performance metrics of the logistic regression model:

- Accuracy: The model correctly classifies loans most of the time.
- Precision:
Healthy loans (0): 1.00 - The model correctly identifies all healthy loans with no mistakes.
High-risk loans (1): 0.86 - Of the loans predicted as high-risk, 86% were actually high-risk.
- Recall:
Healthy loans (0): 1.00 - The model finds all healthy loans with no misses.
High-risk loans (1): 0.91 - The model correctly identifies 91% of high-risk loans, but it misses 9%.


Summary of Results
The logistic regression model works very well, especially for predicting healthy loans. It is highly reliable, with perfect precision and recall for healthy loans, meaning it correctly identifies all of them.

For high-risk loans, the model also performs well, with a precision of 0.86 and recall of 0.91. This means it is good at finding high-risk loans but sometimes makes mistakes, either by classifying a healthy loan as high-risk or missing a high-risk loan.


I recommend using this logistic regression model for the company’s credit risk analysis. The model is reliable in predicting healthy loans and performs well in identifying high-risk loans, making it a useful tool to reduce financial risk and improve lending decisions.

However, because there is a small chance of misclassifying high-risk loans, it’s important to regularly check and retrain the model with new data to improve its accuracy and reduce mistakes.
