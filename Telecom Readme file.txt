Objective:
In the telecom industry, customers can choose from multiple service providers and frequently switch from one operator to another. This highly competitive market experiences an average annual churn rate of 15-25%. Given that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has become crucial. The objective of this project is to reduce customer churn by predicting which customers are at high risk of leaving.

Project Summary:
Data Preprocessing and Cleaning:

Handling Missing Values:
Identified and removed columns with a high percentage of null values.
Dropped rows with any null values to ensure data quality.
Data Type Transformation:
Converted columns containing dates from object types to datetime types for better analysis.
Column Selection:
Filtered out columns based on the threshold of null values to focus on relevant data.
Python Visualizations:
Generated box plots and ROC curves to visualize feature distributions and model performance.
Modeling and Evaluation:

Pipeline Construction:
Built data preprocessing and modeling pipelines for efficient workflow management.
Random Forest Model:
Implemented a Random Forest classifier to predict customer churn.
Tuned hyperparameters to optimize model performance.
Model Evaluation Metrics:
Calculated AUC-ROC to measure the model's ability to distinguish between churn and non-churn.
Computed specificity and sensitivity to understand the model's accuracy in predicting true negatives and true positives, respectively.
Conclusion:
This project focuses on predicting customer churn in the telecom industry using a Random Forest classifier. By effectively preprocessing data, constructing robust pipelines, and evaluating the model using metrics like AUC-ROC, specificity, and sensitivity, the project aims to provide actionable insights to reduce customer churn and retain customers, thereby saving significant costs associated with customer acquisition.