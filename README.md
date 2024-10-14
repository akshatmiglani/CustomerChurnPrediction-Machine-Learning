# Customer Churn - TELCO

## Aim:
This project aims to create a logistic regression model to predict customer churn for a telecommunications company. Churn refers to the phenomenon where customers stop using a company's services. Understanding and predicting churn is crucial for businesses as it helps them retain customers, improve service quality, and ultimately enhance profitability.

In this project, we will implement a logistic regression model from scratch in both Python and C++. Logistic regression is chosen due to its effectiveness in binary classification problems, such as predicting whether a customer will churn or not based on various features.


## Dataset details:
The dataset used in this project contains information about customer demographics, account information, and services used. Below are the key features included in the dataset:

### Services
- **Phone Service**: Yes, No
- **Multiple Lines**: Yes, No, No Phone Service
- **Internet Service**: DSL, Fiber Optic, No
- **Online Security**: Yes, No, No Internet Service
- **Online Backup**: Yes, No, No Internet Service
- **Device Protection**: Yes, No, No Internet Service
- **Tech Support**: Yes, No, No Internet Service
- **Streaming TV**: Yes, No, No Internet Service
- **Streaming Movies**: Yes, No, No Internet Service

### Customer Demographics
- **CustomerID**: Unique value for each customer
- **Gender**: The type of gender each customer (Female, Male)
- **Senior Citizen**: Whether the customer is a senior citizen (Yes, No)
- **Partner**: Whether the customer has a partner or not (Yes, No)
- **Dependents**: Whether the customer has a dependent or not (Yes, No)

### Account Information
- **Tenure**: How long the customer has stayed with the company
- **Contract**: The type of contract the customer has (Month-to-Month, One year, Two years)
- **Paperless Billing**: Whether the customer has paperless billing (Yes, No)
- **Payment Method**: Payment method used by the customer (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **Monthly Charges**: Amount charged to the customer monthly
- **Total Charges**: The total amount charged to the customer