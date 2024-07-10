Decision Tree Classifier for Predicting Customer Purchases

Overview

This project involves building a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. 
The Bank Marketing dataset from the UCI Machine Learning Repository is used for this task.

Task Statement

Task-03: Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.
Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

Project Steps

1. Data Preparation
Loading Data: The dataset was loaded into a pandas DataFrame.
Data Cleaning: Missing values were handled appropriately.
Feature Encoding: Categorical features were encoded using one-hot encoding.
Target Encoding: The target variable was encoded (yes=1, no=0).
2. Model Training
Train-Test Split: The dataset was split into training and testing sets.
Model Selection: A Decision Tree Classifier from scikit-learn was selected.
Training: The model was trained on the training dataset.
3. Model Evaluation
Predictions: The trained model made predictions on the test set.
Accuracy: The model achieved an accuracy score of 89%.
Evaluation Metrics: Other key metrics such as precision, recall, and the confusion matrix were computed to evaluate the model's performance.
4. Visualization
Decision Tree Visualization: The decision-making process of the trained model was visualized using matplotlib to gain insights into customer behavior and predictive factors.
Results

The Decision Tree Classifier achieved an accuracy of 89% on the test set, demonstrating its effectiveness in predicting customer subscription to a term deposit.

Getting Started

Prerequisites
Ensure you have the following libraries installed:

pandas
numpy
scikit-learn
matplotlib
Installation


Install the required packages:


pip install -r requirements.txt
Usage
Run the Jupyter Notebook or Python script to see the results:


jupyter notebook decision_tree_classifier.ipynb
Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

Acknowledgements

This project was completed as part of an internship task at Prodigy Infotech.








