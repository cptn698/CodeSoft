# Titanic-Survival-Prediction
Internship Task Md Ayyan@codesoft, Is  to predict Titanic passenger survival using logistic regression.

## Overview

This repository contains a comprehensive machine learning project for predicting passenger survival on the Titanic. We use the Titanic dataset,from kaggle, to build a predictive model. The primary objective is to determine the likelihood of a passenger surviving or not during the tragic Titanic disaster based on various passenger attributes.


## Dataset Description

The Titanic dataset is well-documented and includes the following columns:

- **PassengerId**: A unique identifier for each passenger.
- **Survived**: Target variable (0 = Not Survived, 1 = Survived).
- **Pclass**: Passenger class (1st, 2nd, or 3rd class).
- **Name**: Passenger's name.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Cabin**: Cabin number.
- **Embarked**: Port where the passenger boarded (C = Cherbourg, Q = Queenstown, S = Southampton).


<h1>Data Preprocessing
</h1>

<p>Handling Missing Values</p>
<p>
  
* some common approaches:
  - df.dropna(axis=0, inplace=True) <mark># Drops rows with any missing value</mark>
  - df.fillna(method='ffill', inplace=True)  <mark> # Forward fill missing values</mark>
  - df['is_missing_age'] = df['Age'].isnull().astype(int)


  <h2>Encoding categorical variables </h2>Here are some common techniques:
<mark> 
</mark>

<mark> Label Encoding:--</mark>
Assigns a unique integer to each category.
Useful for ordinal variables (where order matters).

<mark> One-Hot Encoding (Dummy Variables):--</mark>
Creates binary columns for each category.
Useful for nominal variables (where order doesn’t matter)

<mark> Target Encoding (Mean Encoding):--</mark>
Replaces each category with the mean of the target variable for that category.
Useful for high-cardinality categorical features.



  
</p>

