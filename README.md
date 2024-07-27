# neural-network-challenge-1
## Student Loan Risk Assessment with Deep Learning
Project Overview
This project demonstrates the use of deep learning techniques to assess the risk associated with student loans. It uses a neural network model to predict credit rankings based on various student and loan-related features.
Files in the Repository: student_loan_model.keras
This file contains the trained neural network model for predicting credit rankings of student loans.
student_loans_with_deep_learning.ipynb
This Jupyter Notebook includes the code for data preprocessing, model building, training, evaluation, and prediction. It covers the entire workflow from loading the data to making predictions using the trained model.

Data Description
The project uses a dataset (student-loans.csv) with the following features:

payment_history
location_parameter
stem_degree_score
gpa_ranking
alumni_success
study_major_code
time_to_completion
finance_workshop_score
cohort_ranking
total_loan_score
financial_aid_score
credit_ranking (target variable)

Model Architecture
The neural network model consists of:

Input layer with 11 features
Two hidden layers with ReLU activation
Output layer with sigmoid activation for binary classification

Key Components

Data Preprocessing:
Loading and exploring the dataset
Splitting data into features (X) and target (y)
Scaling features using StandardScaler

Model Building and Training:
Creating a Sequential model using TensorFlow/Keras
Compiling the model with binary crossentropy loss and adam optimizer
Training the model for 50 epochs


Model Evaluation:
Evaluating model performance on test data
Generating classification report

Prediction:
Making predictions on test data
Rounding predictions to binary results