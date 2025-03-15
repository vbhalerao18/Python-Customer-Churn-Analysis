# Customer Churn Analysis

## Overview
This project analyzes customer churn to identify factors contributing to customer retention and churn. The analysis includes data preprocessing, exploratory data analysis (EDA), and insights derived from visualizations.

## Dataset
The dataset contains customer information, including:
- Demographic details (e.g., SeniorCitizen)
- Service subscriptions (e.g., InternetService, PhoneService, TechSupport)
- Payment details (e.g., PaymentMethod, MonthlyCharges, TotalCharges)
- Churn status (whether the customer left or stayed)

## Key Steps in Analysis
1. **Data Preprocessing**
   - Replaced missing values with 0 where applicable.
   - Converted binary categorical values (e.g., `SeniorCitizen` from 0/1 to Yes/No).
   
2. **Exploratory Data Analysis (EDA)**
   - Visualized overall churn rate (~26.54%).
   - Identified that senior citizens have a higher churn rate.
   - Found that customers with shorter tenure (1-2 months) are more likely to churn.
   - Analyzed the impact of various services (e.g., customers with DSL InternetService and OnlineSecurity tend to stay longer).
   - Observed that customers using **electronic checks** as a payment method have a higher churn rate.

## Insights & Conclusion
- Customers who use services like **OnlineSecurity and TechSupport** are less likely to churn.
- Short-term customers have a higher risk of churning.
- **Payment method impacts churn**: Electronic check users show a higher churn rate compared to those using credit cards or bank transfers.

## Dependencies
- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

