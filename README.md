# Bharat-task-2
# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning algorithms. The dataset contains information about various attributes of passengers, such as their socio-economic status, age, gender, and more. The goal is to build a classification model that can accurately predict whether a passenger survived or not.

## Problem Statement

The problem is a binary classification task: given the information about a passenger, we need to determine whether they survived the sinking of the Titanic.

## Dataset

The dataset used for this project is the famous Titanic dataset, which contains the following attributes:

- PassengerId: Unique identifier for each passenger
- Survived: Survival status (0 = Did not survive, 1 = Survived)
- Pclass: Ticket class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
- Name: Passenger's name
- Sex: Passenger's sex (male or female)
- Age: Passenger's age in years
- SibSp: Number of siblings/spouses aboard the Titanic
- Parch: Number of parents/children aboard the Titanic
- Ticket: Ticket number
- Fare: Fare paid for the ticket
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Steps to Run the Project

1. Clone the repository or download the project files.

2. Preprocess the dataset:
   - Handle missing values by imputing or removing them.
   - Encode categorical variables, such as gender and embarkation port, using one-hot encoding or label encoding.

3. Explore and analyze the dataset:
   - Conduct exploratory data analysis (EDA) to gain insights into the dataset.
   - Visualize the data using plots and charts.

4. Train and evaluate different classification algorithms:
   - Split the preprocessed dataset into training and testing sets.
   - Train and evaluate the following algorithms:
     - Logistic Regression
     - Decision Trees
     - Random Forests
     - Gradient Boosting
     - Support Vector Machines (SVM)
     - Neural Networks

5. Choose the best-performing algorithm:
   - Compare the accuracy scores of the different algorithms.
   - Select the algorithm with the highest accuracy as the best-performing algorithm for this task (e.g., Gradient Boosting).

6. Use the best algorithm to make predictions:
   - Train the best algorithm (Gradient Boosting) on the entire preprocessed dataset.
   - Provide input data (passenger information) to the trained model:
     - Prompt the user to enter the passenger information, such as ticket class, sex, age, fare, and other relevant attributes.
     - Pass the user-provided input to the trained Gradient Boosting model.
     - Obtain the predicted survival status for the input data (0 = Did not survive, 1 = Survived).

## Conclusion

This project demonstrates the process of predicting survival on the Titanic using machine learning algorithms. By analyzing the dataset, preprocessing the data, training various algorithms, and evaluating their performance, we can determine the best algorithm for this classification task (e.g., Gradient Boosting). The chosen algorithm can then be used to predict the survival status of new passengers based on their information. The client can test their input by providing the required passenger information and obtaining the predicted survival outcome.
