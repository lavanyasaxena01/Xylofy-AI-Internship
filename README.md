# House Price Prediction using Machine Learning

## Project Overview

This project aims to predict house prices based on various property features such as area, number of bedrooms, bathrooms, parking spaces, stories, furnishing status, and additional amenities. The project uses machine learning regression techniques to estimate house prices and identify the factors that have the greatest impact on property value.

## Dataset

* **Dataset Name:** Housing Prices Dataset
* **Source:** Kaggle
* **File Used:** Housing.csv
* **Records:** 545 houses
* **Target Variable:** Price

## Objectives

* Explore and understand the housing dataset.
* Clean and preprocess the data.
* Convert categorical features into numerical format.
* Build machine learning models for price prediction.
* Compare model performance using evaluation metrics.
* Visualize important patterns and relationships in the data.
* Identify the key factors influencing house prices.

## Technologies and Libraries Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

### 1. Data Exploration

* Loaded the dataset using Pandas.
* Examined the first few records.
* Checked dataset dimensions and data types.
* Identified missing values and duplicate records.

### 2. Data Preprocessing

* Removed duplicate records.
* Handled categorical variables using one-hot encoding.
* Prepared features and target variables for model training.

### 3. Model Building

Two regression models were implemented:

#### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

#### Random Forest Regressor

* MAE: 1,013,969
* RMSE: 1,398,116
* R² Score: 0.613

### 4. Model Comparison

The Linear Regression model achieved better performance than the Random Forest Regressor, providing higher prediction accuracy and lower error values.

## Visualizations

The following visualizations were created:

1. Distribution of House Prices
2. Correlation Heatmap
3. Actual vs Predicted House Prices

## Key Findings

* Area is the most influential factor affecting house prices.
* Bathrooms, parking spaces, air conditioning, stories, and bedrooms also contribute significantly.
* Most houses belong to the lower and middle price ranges, while luxury houses are relatively rare.
* Linear Regression outperformed Random Forest, indicating a largely linear relationship between features and house prices.

## Business Recommendation

Real estate businesses should focus on properties with larger areas and premium amenities such as multiple bathrooms, parking facilities, and air conditioning, as these features have the strongest impact on market value.

## Author

**Lavanya Saxena**
B.Tech (Artificial Intelligence & Data Science)
Dr. Akhilesh Das Gupta Institute of Professional Studies (ADGIPS)
