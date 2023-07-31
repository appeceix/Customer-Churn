# Predict Customer Churn with Python and Machine Learning

In this project, we aim to build a predictive model that can predict customer churn using Machine Learning. Customer churn refers to customers who may intend to leave a service or product in the future.

## Project Overview
The project implements a predictive model using Python. We will be using a dataset containing customer information to train and evaluate our model.

## Dataset
The dataset can be downloaded from the following link: churn.csv

### Data Description
The dataset contains the following columns:

- customerID: Unique identifier for each customer
- gender: Gender of the customer
- SeniorCitizen: Whether the customer is a senior citizen (1) or not (0)
- Partner: Whether the customer has a partner (Yes or No)
- Dependents: Whether the customer has dependents (Yes or No)
- tenure: Number of months the customer has been with the company
- PhoneService: Whether the customer has a phone service (Yes or No)
- MultipleLines: Whether the customer has multiple lines (Yes, No, or No phone service)
- InternetService: Type of internet service (DSL, Fiber optic, or No)
- OnlineSecurity: Whether the customer has online security (Yes, No, or No internet service)
- OnlineBackup: Whether the customer has online backup (Yes, No, or No internet service)
- DeviceProtection: Whether the customer has device protection (Yes, No, or No internet service)
- TechSupport: Whether the customer has tech support (Yes, No, or No internet service)
- StreamingTV: Whether the customer has streaming TV (Yes, No, or No internet service)
- StreamingMovies: Whether the customer has streaming movies (Yes, No, or No internet service)
- Contract: Type of contract (Month-to-month, One year, or Two year)
- PaperlessBilling: Whether the customer has paperless billing (Yes or No)
- PaymentMethod: Payment method used by the customer
- MonthlyCharges: Monthly charges of the customer
- TotalCharges: Total charges of the customer
- Churn: Whether the customer churned (Yes or No)


## Data Exploration and Preprocessing
We begin by exploring the data, checking for missing values, and visualizing the distribution of customer churn. We will convert non-numeric columns to numeric using label encoding and scale the data using StandardScaler.

## Model Building
We use a logistic regression model for predicting customer churn. The data is split into training and testing sets (80% training and 20% testing), and the model is trained on the training data.

## Model Evaluation
After training the model, we make predictions on the test data and evaluate the model's performance using precision, recall, and F1-score.

## Instructions
To run the code, ensure that you have the required libraries installed (NumPy, Pandas, Scikit-learn, Matplotlib, and Seaborn). Download the dataset and place it in the same directory as the code. Then, execute the code in a Python environment.

Feel free to customize the code and dataset according to your needs. Happy coding!