# Credit_Risk_Analysis
 


# Overview of Project

Here is the list of deliverables for the analysis:
```````
•	Deliverable 1: Use Resampling Models to Predict Credit Risk
•	Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
•	Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
•	Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)
```````
We will be using are data preparation, statistical reasoning, and implement a machine learning model using sklearn is the Scikit-learn machine learning library for Python.

Specifically,

The files we will be using are the LoanStats_2019Q1.csv dataset and two starter code files: credit_risk_resampling_starter_code.ipynb and credit_risk_ensemble_starter_code.ipynb.

# Purpose:

Using the imbalanced-learn and scikit-learn libraries, to evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, using the oversampling RandomOverSampler and SMOTE algorithms, and then using the undersampling ClusterCentroids algorithm.

# Results:
Using these algorithms, to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

- A confusion matrix has been generated 
- An accuracy score for the model is calculated 
- An imbalanced classification report has been generated
## 1)	Oversampling RandomOverSampler 
![D1a](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D1a.PNG)
## 2)	SMOTE algorithms 
![D1b](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D1b.PNG)
## 3)	Undersampling ClusterCentroids algorithm 
![D1c](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D1c.PNG)
## 4)	combinatorial SMOTEENN algorithm
![D2a](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D2a.PNG)
## 5)	BalancedRandomForestClassifier algorithm
![D3a](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D3a.PNG)
The features are sorted in descending order by feature importance
![F](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/F.PNG)

## 6)	EasyEnsembleClassifier algorithm
![D3b](https://github.com/735713038455163/Credit_Risk_Analysis/blob/master/Pictures/D3b.PNG)

# Summary:
Balanced accuracy uses sensitivity and specificity to evaluate the performance of a classifier. The balanced accuracy is placed on a scale of 0 to 1. The closer to 1 the balanced accurracy is, the better the prediction of the model. For the credit card risk data set, all of the classifiers tested showed similar recall scores, and all had precision scores as low for high-risk loans and high for low-risk loans.
The Easy Ensemble AdaBoost Classifier model gave us the highest balanced accuracy score and precision which is the best fit for this dataset. 

# Key Take Aways
* Explain how a machine learning algorithm is used in data analytics.
* Create training and test groups from a given data set.
* Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Compare the advantages and disadvantages of each supervised learning algorithm.
* Determine which supervised learning algorithm is best used for a given data set or scenario.
* Use ensemble and resampling techniques to improve model performance.
