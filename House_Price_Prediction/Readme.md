House Price Prediction using Machine Learning
Project Overview

This project aims to build and evaluate multiple Machine Learning models to predict house prices based on various property-related features. The workflow follows a complete data science pipeline including data understanding, preprocessing, visualization, model building, hyperparameter tuning, and performance comparison.

A Jupyter Notebook containing the full implementation and a video walkthrough explaining the notebook are provided as part of the assignment submission.

Dataset Information

The dataset consists of the following files:

train.csv – Training dataset containing features and the target variable (price)

test.csv – Test dataset with the target variable hidden

sample_submission.csv – Sample submission file in the correct format

Column Description
Column Name	Description
id	Unique identifier
area_type	Type of area
availability	Availability status of the house
location	Location of the house
size	BHK configuration (Bedrooms, Hall, Kitchen)
total_sqft	Total area in square feet
bath	Number of bathrooms
balcony	Number of balconies
price	House price (Target variable)
Project Workflow
1. Data Understanding

Identified and documented data types of all columns

Converted non-standard columns into usable numerical formats

2. Exploratory Data Analysis

Generated descriptive statistics (minimum, maximum, mean, median)

Analyzed distributions and relationships between features and price

3. Data Cleaning

Identified and handled missing values through imputation or removal

Checked and removed duplicate records

Detected outliers and provided justification for retaining or removing them

4. Data Visualization

At least three visualizations were created, including:

Price distribution

Relationship between price and total square feet

Price variation across locations or BHK types
Each visualization includes meaningful insights.

5. Feature Engineering

Scaled numerical features where required

Encoded categorical variables using suitable techniques

Provided reasoning for scaling and encoding choices

Model Building

A minimum of seven Machine Learning models were trained and evaluated, including:

Linear Regression

Ridge Regression

Lasso Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor / XGBoost / Extra Trees Regressor

Hyperparameter Tuning

Hyperparameter tuning performed on at least three models

Used GridSearchCV and/or RandomizedSearchCV for optimization

Model Evaluation and Comparison

Models evaluated using appropriate regression metrics (R², RMSE)

Performance compared on a validation dataset

Best-performing model selected based on evaluation results

Final Submission

Predictions generated for the test dataset

Submission file created following the format of sample_submission.csv

Video Walkthrough

A detailed video walkthrough explaining the notebook and approach is available at the link below:

Video URL: (Add your Google Drive link here)
(Access set to “Anyone with the link – Viewer”)

Repository Structure
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── notebook/
│   └── House_Price_Prediction.ipynb
├── submission/
│   └── submission.csv
├── README.md

Tools and Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Conclusion

This project demonstrates an end-to-end Machine Learning regression workflow, covering data preprocessing, visualization, model development, hyperparameter tuning, and performance evaluation in a structured and reproducible manner.
