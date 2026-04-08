# Machine-Learning-seller-account-health-decision-tree
Decision Tree to predict seller account health risk from operational performance metrics.

# Seller Account Health Risk Prediction Using Decision Trees

Binary classification using Decision Tree to predict Amazon seller account 
health risk from operational performance metrics.

## Important Note on Dataset

The dataset used in this project is completely fabricated and synthetically 
generated for learning purposes only. It does not represent any real seller 
data, internal Amazon records, or proprietary business information. Any 
resemblance to actual seller accounts is purely coincidental.

## Project Scope

This project applies a Decision Tree Classifier to predict whether an Amazon 
seller's account is Healthy or At Risk based on operational performance metrics. 
The dataset consists of 1000 synthetic seller records with features covering 
defect rates, shipment performance, policy violations, and seller profile attributes.

## Features Used

- policy_violation_count
- order_defect_rate
- late_shipment_rate
- return_rate
- negative_feedback_rate
- fulfillment_type
- seller_category

## Results

- Accuracy: 95.5%
- Top predictors: policy_violation_count and order_defect_rate
- Algorithm: Decision Tree Classifier (max_depth=4, min_samples_leaf=10)

## Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
