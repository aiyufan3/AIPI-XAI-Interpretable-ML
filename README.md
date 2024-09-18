# AIPI-XAI-Interpretable-ML
## Telecom Customer Churn Prediction Using Interpretable Models

This project aims to predict customer churn for a telecommunications company using **interpretable machine learning models**. The goal is to help the company understand which factors contribute to customer churn and provide actionable insights for customer retention. 

## Dataset

The dataset used in this project is from Kaggle: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It contains customer demographics, account information, and service details, including whether or not the customer churned. The target variable is **Churn** (Yes/No).

### Key Features:
- **CustomerID**: Unique customer identifier.
- **SeniorCitizen**: Binary flag indicating if the customer is a senior citizen.
- **Tenure**: Number of months the customer has stayed with the company.
- **MonthlyCharges**: The monthly amount charged to the customer.
- **TotalCharges**: The total amount charged to the customer.


## Project Structure

- **`telco_churn_analysis.ipynb`**: Google Colab notebook with the entire analysis, including data preprocessing, model building, and evaluation.
- **`README.md`**: This file, providing an overview of the project and instructions.
- **`data/`**: Folder containing the dataset (if needed).

## Exploratory Data Analysis (EDA)

Exploratory data analysis is conducted to evaluate model assumptions, check for linearity, and understand feature distributions. Visualizations include:
- Correlation matrix for checking relationships between numerical variables.
- Histograms of key features like tenure and monthly charges.
- Churn distribution to visualize class imbalance.

## Model Comparison and Recommendations

- **Linear Regression**: Easy to interpret but not well-suited for predicting binary outcomes like churn.
- **Logistic Regression**: Balances simplicity and accuracy, making it the recommended model for predicting churn. Provides interpretable coefficients for each feature.
- **GAM**: Offers flexibility by capturing non-linear patterns, but may be more complex for business users to interpret. Recommended when more complex relationships are found in the data.

## How to Run the Notebook

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/telecom-churn-prediction.git](https://github.com/aiyufan3/AIPI-XAI-Interpretable-ML.git)
