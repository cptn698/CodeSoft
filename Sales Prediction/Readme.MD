# Sales Prediction
Internship Task Md Ayyan@codesoft, Is  to predict Sales on Linear regression.

## Overview

This repository contains a comprehensive machine learning project for predicting sales. We use the Advertisement dataset,from kaggle, to build a predictive model.


## Dataset Description

The advertisement dataset is well-documented and includes the following columns:

- **TV**: 
- **Radio**:
- **Newspaper**: 
- **Sales**:


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


