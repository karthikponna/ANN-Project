# ANN-Project
This repository contains code for predicting customer churn in a bank using an Artificial Neural Network (ANN). 
The model is trained on a dataset containing customer details from the previous 6 months, and it aims to predict whether a new customer will stay or leave the bank.

# Dataset
The dataset used for training and testing the model is from the 'Churn_Modelling.csv' file. It includes features such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, active member status, and estimated salary.

# Code Structure
artificial_neural_network.ipynb: Jupyter Notebook containing the Python code for loading the dataset, preprocessing, building, training, and evaluating the ANN model.
Churn_Modelling.csv: The dataset used for training and testing the model.

# Dependencies
NumPy
Pandas
TensorFlow
Scikit-learn
# Results
The trained ANN model achieved an accuracy of 86.05% on the test set. The confusion matrix provides insights into the model's performance, showing the number of true positives, true negatives, false positives, and false negatives.
