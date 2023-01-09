# Udacity Data Science Capstone Project


## Introduction

This project uses the user demographics data, offers data and transaction data to determine if a cterian offer is going to be completed or not. The types of offers considered in this project are only BOGO and DISCOUNT offers.


## Files in the repository

- data </br>
| - portfolio.json  #contains data of the offers </br>
| - profile.json  #contains data of the users </br>
| - transcript.json  #contains data about the transactions, offer received, offer viewed and offer completed </br>

- project </br>
|- ML.ipynb </br>

- README.md </br>


## Libraries used

Data Transformation -> Pandas, Numpy, json, datetime
Model building -> sklearn
Data Visualization -> seaborn, matplotlib


## Summary of Results

The model trained is a Gradient Boosting Classifier with the below parameters:

{'clf__learning_rate': 0.1,
 'clf__max_depth': 5,
 'clf__min_samples_leaf': 10,
 'clf__min_samples_split': 2,
 'clf__n_estimators': 200}

The model accuarcy on the training dataset is 0.73 and accuracy on the test dataset is 0.71. The major features contributing to the model were membership_period, scocial and income.


## Acknowledgment

- Data Source : 
Starbucks users data was provided by Udacity.

- Useful Resources :  
Gradient Boosting Classifier documentaton -> https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
Sklearn pipeline documentation -> https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html
Sklearn Logistic Regression documentation -> https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html


## Link to the Blog post

https://medium.com/@sxsubra.das/udacity-data-science-capstone-project-789bfa3fed6f

