# Task 8 - Decision Tree (Bank Marketing Subscription Prediction)

## Objective
Build an interpretable Decision Tree model to predict whether a customer will subscribe to a bank term deposit.

## Dataset
UCI Bank Marketing Dataset  
(Target variable: `y` – whether the client subscribed to a term deposit)

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Steps Performed
1. Loaded the Bank Marketing dataset and analyzed features related to customer subscription behavior.
2. Cleaned the dataset by handling unknown or inconsistent categorical values.
3. Encoded categorical features using One-Hot Encoding.
4. Split the dataset into training and testing sets using a fixed `random_state`.
5. Trained a Decision Tree Classifier with limited `max_depth` to avoid overfitting.
6. Visualized the decision tree using `plot_tree()` for interpretability.
7. Generated predictions on test data and evaluated using a classification report.
8. Compared training accuracy and testing accuracy to check overfitting.
9. Extracted decision rules from the tree to explain customer subscription behavior.

## Deliverables
- Notebook / Python script
- Decision tree visualization image
- Classification report

## Conclusion
Decision Trees provide clear, rule-based explanations for predictions. Limiting tree depth helps reduce overfitting while maintaining interpretability.
