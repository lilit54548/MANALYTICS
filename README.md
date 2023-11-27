# MANALYTICS

## Survival Analysis by Lilit
Overview

This Jupyter Notebook provides a guide to performing survival analysis. 

### Main Topics:
Importing Libraries
Reading and Transforming the Data
Fitting AFT (Accelerated Failure Time) Models
Weibull, Log-Normal, and Log-Logistic Models
Comparing Models
Plotting Analysis Results
Feature Selection and Significance
Customer Lifetime Value (CLV) Analysis
Visualizing CLV vs. Features
Drawing Conclusions
Calculating Retention Budget
Experimenting with Feature Scaling

### Libraries Used
Lifelines
Matplotlib
Numpy
Pandas
Seaborn
Warnings
Getting Started

### To get started with this notebook:


- Install the required libraries using pip:
- Copy code
- Open the notebook in a Jupyter environment to explore the analysis.

### Data


Total Rows: 1000

Total Columns: 15

Column Names and Data Types:

- ID (int64): Unique identifier for each customer
- region (object): Geographical region of the customer
- tenure (int64): Duration of service usage (in months)
- age (int64): Age of the customer
- marital (object): Marital status of the customer
- address (int64): Duration of residence at the current address (in years)
- income (int64): Customer's income
- ed (object): Education level of the customer
- retire (object): Retirement status
- gender (object): Gender of the customer
- voice (object): Voice mail service usage
- internet (object): Internet service usage
- forward (object): Call forwarding service usage
- custcat (object): Customer category
- churn (object): Churn status (whether the customer has left the service)
- 
Missing Values: There are no missing values in the dataset.
