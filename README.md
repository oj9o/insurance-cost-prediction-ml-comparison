# insurance-cost-prediction-ml-comparison
Machine learning project comparing Linear Regression and Random Forest models to predict medical insurance charges using R.
Predicting Insurance Charges Using Machine Learning

Project Overview

This project investigates the factors that influence medical insurance charges and compares the performance of two machine learning regression models:

* Linear Regression
* Random Forest Regression

The objective was to identify the most influential variables affecting insurance costs and determine which model provides the most accurate predictions.

⸻

Business Problem

Medical insurance costs vary significantly between individuals. This project aims to answer two key questions:

1. Which factors have the greatest impact on insurance charges?
2. Which machine learning model predicts insurance charges more accurately?

⸻

Dataset

The project uses the Medical Cost Personal Dataset containing:

* 1,338 observations
* 7 variables

Features

* Age
* Sex
* BMI
* Children
* Smoker
* Region

Target Variable

* Insurance Charges

⸻

Data Exploration

Before building the models, exploratory data analysis (EDA) was performed to understand the dataset and identify important patterns.

Key findings include:

* No missing values were found.
* Insurance charges are right-skewed.
* Smokers generally have much higher insurance charges.
* Insurance costs tend to increase with age.

⸻

Data Preparation

The dataset was prepared by:

* Converting categorical variables into factors.
* Splitting the data into:
    * 80% Training Set
    * 20% Testing Set

This ensured that model performance was evaluated on unseen data.

⸻

Models Developed

1. Linear Regression

A Linear Regression model was used as the baseline model.

Performance:

* MAE: 3940.185
* RMSE: 5763.385
* R²: 0.734

Key findings:

* Smoking had the strongest positive effect on insurance charges.
* BMI and age were significant predictors.
* Sex and region had relatively little influence.

⸻

2. Random Forest Regression

A Random Forest model was trained to capture more complex and non-linear relationships.

Performance:

* MAE: 2801.824
* RMSE: 4396.833
* R²: 0.849

Feature Importance:

1. Smoker
2. Age
3. BMI
4. Children
5. Region
6. Sex

⸻

Model Comparison

Model	MAE	RMSE	R²
Linear Regression	3940.185	5763.385	0.734
Random Forest	2801.824	4396.833	0.849

⸻

Results

The Random Forest model achieved the best overall performance.

Compared with Linear Regression, it produced:

* Lower prediction error (MAE)
* Lower prediction error (RMSE)
* Higher R² value

The analysis also identified smoking as the strongest predictor of insurance charges, followed by age and BMI.

⸻

Technologies Used

* R
* Machine Learning
* Linear Regression
* Random Forest
* Data Visualization
* Exploratory Data Analysis (EDA)

⸻

Repository Contents

* Mouza_AlDarmaki_Insurance_Charges_ML_Project.ipynb – Complete project notebook
* Presentation.pdf – Project presentation
* insurance.csv – Dataset
* README.md – Project documentation

⸻

Author

Mouza AlDarmaki

Business Analytics Track

2026
