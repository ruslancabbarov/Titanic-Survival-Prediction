Titanic Survival Prediction
Project Overview

This project analyzes the Titanic dataset and builds a Logistic Regression model to predict whether a passenger survived or not.

The workflow includes data cleaning, feature engineering, exploratory data analysis (EDA), preprocessing, and model evaluation.

Dataset

The dataset contains information about Titanic passengers such as:

Passenger class (Pclass)

Gender (Sex)

Age

Siblings/Spouses (SibSp)

Parents/Children (Parch)

Fare (Fare)

Port of embarkation (Embarked)

Survival status (Survived)

Target variable:

Survived

1 → Survived

0 → Did not survive



Data Preprocessing

Removed unnecessary columns (PassengerId, Name, Ticket, Cabin)

Converted categorical variables into numerical format using One-Hot Encoding

Encoded Sex feature (male = 1, female = 0)



Feature Engineering

A new feature called FamilySize was created:

FamilySize = SibSp + Parch + 1

This represents the total number of family members traveling together.



Exploratory Data Analysis (EDA)

Visualizations were used to analyze relationships between features and survival, including:

Embarked vs Survived with Pclass

Sex vs Survival rate

FamilySize vs Survival



Key observations:

1st class passengers had higher survival rates

Women had significantly higher survival probability

Survival rate varied depending on the port of embarkation


Model

A Logistic Regression model was trained using:

Train/Test split

Feature scaling with RobustScaler

Model Evaluation


The model was evaluated using:

Confusion Matrix

Classification Report

Accuracy Score



Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn