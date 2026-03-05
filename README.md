Titanic Survival Prediction

Project Goal: Predict whether Titanic passengers survived using a Logistic Regression model.

Dataset: Passenger info including gender, age, class, family size, fare, and port of embarkation.

Features: Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, FamilySize (SibSp + Parch + 1)

Data Preprocessing:

Removed unnecessary columns (PassengerId, Name, Ticket, Cabin)

Encoded categorical variables (Sex: male=1, female=0; Embarked: One-Hot Encoding)

EDA Key Insights:

1st class passengers had higher survival rates

Women were more likely to survive than men

Port of embarkation and family size influenced survival

Model: Logistic Regression with train/test split and RobustScaler

Evaluation: Accuracy, Confusion Matrix, Classification Report

Technologies: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
