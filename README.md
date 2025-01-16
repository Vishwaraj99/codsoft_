Titanic Logistic Regression Analysis
Project Overview
This project applies a logistic regression analysis on the Titanic dataset to predict passenger survival based on available features.

Requirements
Python Version: 3.x
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
Dataset Details
Source: Titanic dataset (available on Kaggle)
Filename: Titanic-Dataset.csv
Dataset Columns
Survived: Indicates survival (0 = No, 1 = Yes)
Pclass: Ticket class (1st, 2nd, 3rd class)
Sex: Gender (male, female)
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Fare: Ticket fare
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Excluded Columns
PassengerId, Name, Ticket, Cabin
These columns are irrelevant for survival prediction and were removed during preprocessing.
Model Features
The following columns were used to train the logistic regression model:

Pclass
Sex
Age
SibSp
Parch
Fare
Embarked
Steps to Execute
1. Preprocessing
Handle missing values by appropriate imputation.
Encode categorical variables (e.g., Sex, Embarked) into numerical values.
2. Model Building and Training
Train a logistic regression model using the preprocessed dataset.
3. Evaluation
Evaluate model performance using:
Accuracy
Confusion Matrix
Classification Report
Evaluation Metrics
Accuracy: Measures the proportion of correct predictions.
Confusion Matrix: Provides counts of:
True Positives
False Positives
True Negatives
False Negatives
Classification Report: Details:
Precision
Recall
F1-Score
Support
Example Results
Accuracy: 83%
Confusion Matrix:
lua
Copy
Edit
[[89  12]  
 [18  60]]  
Classification Report:
markdown
Copy
Edit
            Precision    Recall    F1-Score   Support  
   0            0.83       0.88       0.85        101  
   1            0.83       0.77       0.80         78  
   Overall      0.83       0.83       0.83        179  
About
This project demonstrates practical use of logistic regression for binary classification on real-world data.

Resources
Titanic dataset from Kaggle
Python libraries for data preprocessing and modeling
Additional Details
Languages: Python (Jupyter Notebook)
License: Open source
