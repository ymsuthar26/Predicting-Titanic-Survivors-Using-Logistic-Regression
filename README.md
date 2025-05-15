# Predicting-Titanic-Survivors-Using-Logistic-Regression
The dataset used is the classic Titanic dataset available from Kaggle. It contains data for 891 passengers, including attributes like age, sex, class, fare, and survival status.

## Tools used
Pandas
NumPy
Matplotlib 
Seaborn
Scikit-learn

## Data Exploration

Checked data types and null values.
Reviewed distribution of passengers and survival counts.


## Data Cleaning & Preprocessing

Filled missing Age values with mean.
Dropped Cabin due to >77% missing values.
Filled missing Embarked with mode ('S').
Removed irrelevant features (PassengerId, Name, Ticket).
Converted categorical data (Sex, Embarked) using one-hot encoding.


## Outlier Treatment

Detected outliers using boxplots.
Capped extreme Fare values using IQR method.

## Prediction System

Created a simple user input-based prediction script to test survival based on custom input values.

## Results

Accuracy: ~82%
Precision/Recall: Good performance on both classes.
Final model provides a balanced trade-off between precision and recall.
