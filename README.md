# Telecom Customer Churn Analysis
This repository contains an exploratory data analysis (EDA) on a telecom churn dataset. The project focuses on understanding factors contributing to customer churn and identifying insights to help reduce churn.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Results and Observations](#results-and-observations)

### Project Overview
Customer churn is a crucial metric in the telecom industry, reflecting the percentage of customers who discontinue their service over a specific period. This EDA project analyzes various customer attributes to uncover patterns and features that contribute to customer churn. The insights gathered can help in designing strategies to retain customers and improve their experience.

### Dataset:
 [Telco Customer Churn](https://www.kaggle.com/bhartiprasad17/customer-churn-prediction/data)

The telecom churn dataset includes details about customer demographics, account information, usage patterns, and churn status. Each entry in the dataset represents an individual customer.

### Key Features:
- **Customer ID**: Unique identifier for each customer
- **Demographics**: Gender, age, and other customer-related information
- **Account Info**: Subscription details, tenure, billing method, etc.
- **Usage Patterns**: Call minutes, internet usage, etc.
- **Churn**: Indicates whether the customer has left the service (`1`) or stayed (`0`)

### Analysis Summary
The analysis is structured into the following steps:
1. **Data Cleaning**: Handling missing values, duplicates, and ensuring data consistency.

2. **Exploratory Data Analysis (EDA)**: Detailed exploration of the features, including:
   - Descriptive statistics
   - Visualization of key features influencing churn
   - Correlation analysis to identify strong relationships
## Some EDA Visualizations:
**a. Customer churn distribution-**

![Churn Distribution](https://github.com/user-attachments/assets/6ebd4ef0-b767-439e-ad79-296b220895b0)
> 26.6 % of customers switched to another firm.


**b. Customer churn by gender-**

![Screenshot 2024-11-12 000848](https://github.com/user-attachments/assets/b1d41fe3-c049-49c0-bb25-c41da492d8c2)
> Both male and female customers have similar churn rates, with the majority in each group not churning. This suggests that gender does not significantly impact churn likelihood in this dataset.


**c. Customer churn based on senior citizenship-**

![Screenshot 2024-11-12 001347](https://github.com/user-attachments/assets/08cbd999-c431-4cb4-813d-cb30cee8eaf4)
> Non-senior citizens have a much higher count in both churn and non-churn categories, while senior citizens have a lower count overall, with slightly more non-churners.
> This indicates that senior citizenship may not be a major factor in predicting churn.


**d. 
3. **Insights**: Summary of findings on factors influencing churn, including:
   - High churn rates among certain customer segments
   - Trends related to usage and billing that may predict churn
     
### Requirements
The notebook is built in Python and requires the following libraries:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization

### Results and Observations
Key findings from this EDA:

- Certain customer demographics show higher churn rates.
- Billing methods and contract types significantly affect churn.
- Long-term customers exhibit lower churn rates.

These insights can guide targeted customer retention strategies and help in identifying high-risk customers.
