# OLA-Driver-Attrition-Prediction
Overview:

This project aims to predict driver attrition at Ola by leveraging ensemble learning techniques. The model helps in identifying drivers who are likely to leave the company, allowing Ola to implement retention strategies effectively.

Project Objective:

- Predict whether a driver will leave Ola based on various attributes.
- Prioritize model metrics like recall and ROC-AUC due to the competitive nature of the industry.
- Identify key factors contributing to driver attrition using feature importance.
  
Data:

The dataset includes monthly data for a subset of drivers from 2019 and 2020, covering features such as age, income, education level, city, and quarterly ratings.

Key Features:

1. Data Preprocessing:

   Imputation of missing values using KNN and handling of categorical variables through one-hot encoding.
2. Feature Engineering:
  
   Created new features like "Increased Rating" and "Salary Increased" to enhance model prediction.
3. Modeling:
  
   Implemented ensemble methods including Random Forest, Gradient Boosting, and XGBoost to predict driver attrition.
   
Insights:
- Identified important features like Last Quarterly Rating, Total Business Value, and Increased Rating, which significantly impact driver retention.
  
Recommendations:

- Introduce incentives such as overtime pay and career development pathways to reduce turnover.
- Focus on drivers with lower incomes and ratings for targeted support to improve job satisfaction.
