# Titanic ML Challenge

Python notebook containing my solution for the [Titanic](https://www.kaggle.com/competitions/titanic) ML Challenge hosted on Kaggle.

## Goal
  
The goal of the challenge is to build a predictive model using passenger data (ie name, age, gender, socio-economic class, etc).

## Data visualization and Feature Engineering

The first part of the notebook focuses on analyzing the data by plotting with matplotlib and seaborn the distribution of some features. In the second part, **new features** are created. In particular, we inferred the passenger social status/job by retrieving their title (e.g. Mr., Mrs, Master., etc) using python regular expressions.

## The model

In the last part, the scikit-learn library is used to find the best hyperparametres for the **Random Forest Classifier** through RandomizedSearchCV.

## The performance

The model's accuracy during cross validation is 83%, while its accuracy on the test set is around the **80%**.
