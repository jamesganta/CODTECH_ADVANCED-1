# CODTECH_ADVANCED-1

Name : James Timothy Ganta

Company : CODTECH IT SOLUTIONS 

ID : CT6WDS2703 

Domain : Machine Learning 

Duration : 6 weeks (Dec 5th 2024 to Jan 20th 2025)

# Overview of the task

A decision tree is a non-parametric supervised learning algorithm
used for both classification and regression tasks. It resembles a
flowchart-like tree structure, where each internal node denotes a
feature (or attribute), the branch represents a decision rule, and
each leaf node represents the outcome. The topmost node in a decision
tree is known as the root node. It 1  recursively partitions data based
on the attribute value. This flowchart-like structure mimics human-level
decision-making, making decision trees easily understandable and
interpretable.   
1.
www.datacamp.com
www.datacamp.com

Here's a step-by-step guide on how to implement a decision tree model
using scikit-learn to classify or predict outcomes on a chosen dataset:

Import necessary libraries:

Python

import pandas as pd
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
Load the dataset:

Code snippet

data = pd.read_csv("your_dataset.csv")
Preprocess the data (if necessary):

Handle missing values using techniques like imputation or deletion.
Encode categorical features using techniques like one-hot encoding or label encoding.
Define the feature matrix (X) and target variable (y):

Python

X = data.drop("target_column", axis=1)  # Features
y = data["target_column"]  # Target variable
Split the data into training and testing sets:

Python

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
Create a decision tree classifier object:

Python

model = DecisionTreeClassifier()
Train the model on the training data:

Python

model.fit(X_train, y_train)

# Output of the Task
![Screenshot 1946-10-28 at 12 59 10 PM](https://github.com/user-attachments/assets/700b9db5-601e-4f04-8991-cebd6792f1d9)

