# Massage Business Member Churn Analysis

*This project is a member churn analysis for a small business client. As requested, the datasets provided will not be shared.*

## Provided Dataset Description
- Member: Partial member records with multiple demographics and membership-related data.
- Sales: Transaction details for massage items with member ID.
- Deposits: Transaction details for gift card items with member ID.
- Schedule: Schedule details for massage appointments with member ID.
- Therapist Metrics: Therapists' performance metrics with their names.
- Therapist Turnover: Therapists' monthly turnover with their names.

## Methods
1. The datasets were preliminarily cleaned, merged, and visualized to find data patterns for the next steps.
2. Features were selected with business domain knowledge and then examined by visualizations and statistical tests.
3. Built Logistic Regression, Decision Tree, Random Forest, SVM, and KNN classification models for comprehensive comparison and selected Logistic Regression model for its high recall and accuracy.
4. Tuned hyperparameters for logistic regression with k-fold cross-validation to enhance model precision without overfitting, achieved 100% recall for the churn class and 94% accuracy for both classes on the test set.
5. Results were explained in business language and presented to the stakeholder.

## Results
The model achieved 100% recall for the churn class and 94% accuracy for both classes on the test set, indicating a highly effective model in predicting member churn with minimized retention cost.
