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


**d. Customer churn with respect to customers having dependents-**

![Screenshot 2024-11-12 214354](https://github.com/user-attachments/assets/bc37f696-bf7b-44ea-9f29-eaf5860c18c2)
> Customers without dependents have a higher churn rate compared to those with dependents. This suggests that having dependents might be associated with greater customer retention.


**e. Customer Churn based on Phone Service-**

![Screenshot 2024-11-12 215006](https://github.com/user-attachments/assets/e1e7c78c-49fa-4453-b764-34153a2e7832)
> Customers with phone service have a higher churn rate compared to those without it, though most still do not churn. This suggests that having phone service might slightly increase the likelihood of churn.


**f. Churn Distribution by Internet Service Type-**

![Screenshot 2024-11-12 220825](https://github.com/user-attachments/assets/68155784-bab0-491d-b4bd-edc23f4fa394)
> Customers with fiber optic internet have a higher churn rate compared to those with DSL or no internet service, suggesting that fiber optic users may be more likely to leave.


**g. customer churn rates based on contract type-** 

![Screenshot 2024-11-12 221238](https://github.com/user-attachments/assets/fb0e5993-4ddc-4821-887e-b1d90356155d)
> The graph shows that month-to-month contracts have the highest churn, while one-year and two-year contracts show significantly lower churn rates.


**h. Customer Churn with respect to Paperless Billing-**

![Screenshot 2024-11-12 221732](https://github.com/user-attachments/assets/d01257bf-16db-462d-af83-30991d08dba4)
> Customers with paperless billing are more likely to churn compared to those who do not use paperless billing.


**i. customer churn rates by tenure group-**

![Screenshot 2024-11-12 222025](https://github.com/user-attachments/assets/aaad8408-9833-4bc0-86fe-a72cd9a16565)
> Customers with shorter tenures (1-12 months) have the highest churn, while churn decreases significantly with longer tenure.

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
