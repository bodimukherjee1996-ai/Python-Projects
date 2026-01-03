# Airbnb Data Analysis & Price Prediction

## Introduction

Welcome to the Airbnb Data Analysis & Price Prediction project. This project focuses on analyzing Airbnb listings data to uncover insights about pricing patterns, location-based trends, and property characteristics. In addition, predictive models are built to estimate listing prices based on key features, helping hosts and stakeholders make data-driven pricing decisions.

## Dataset

The dataset used in this project contains Airbnb listing information, including property details, host attributes, location data, room types, availability, and pricing.  
It consists of both numerical and categorical variables and represents real-world short-term rental market dynamics.

*(If sourced from a public dataset such as Inside Airbnb or Kaggle, the link can be added here.)*

## Project Objectives

The main objectives of this project are:

1. **Exploratory Data Analysis (EDA)**:  
   Analyze Airbnb listings to understand price distributions, popular locations, room types, and availability patterns.

2. **Feature Impact Analysis**:  
   Identify which factors (location, room type, number of reviews, availability, etc.) most influence listing prices.

3. **Data Preparation**:  
   Clean the dataset, handle missing values, encode categorical variables, and prepare features for modeling.

4. **Price Prediction**:  
   Build machine learning models to predict Airbnb listing prices based on property and location features.

5. **Business Insights**:  
   Generate actionable insights that can help hosts optimize pricing strategies and understand market behavior.

## Data Preprocessing

The following preprocessing steps were applied:

- **Missing Value Treatment**: Handled missing or inconsistent values across numerical and categorical features.
- **Outlier Handling**: Examined extreme price values to reduce skewness and improve model performance.
- **Encoding Categorical Variables**: Converted categorical features such as room type and neighborhood into numerical representations.
- **Feature Scaling**: Scaled numerical features where required to improve model convergence and performance.

## Exploratory Data Analysis (EDA)

During the EDA phase, the following analyses were performed:

- **Price Distribution Analysis**: Examined how prices vary across listings and identified skewness and outliers.
- **Location-Based Trends**: Compared average prices across neighborhoods and regions.
- **Room Type Analysis**: Analyzed pricing differences between entire homes, private rooms, and shared rooms.
- **Availability & Reviews**: Studied the relationship between availability, number of reviews, and pricing.
- **Correlation Analysis**: Identified relationships between numerical variables and listing prices.

Visualizations such as histograms, box plots, bar charts, and correlation heatmaps were used extensively.

## Model Building

Multiple machine learning models were explored to predict Airbnb listing prices, including:

- **Linear Regression**: Baseline model for understanding linear relationships.
- **Decision Tree Regressor**: Captured non-linear patterns in pricing behavior.
- **Ensemble Models (if applicable)**: Improved predictive performance by reducing bias and variance.

Hyperparameters were tuned to achieve optimal performance.

## Model Evaluation

Model performance was evaluated using appropriate regression metrics, including:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

These metrics helped assess how accurately the models predicted listing prices and generalized to unseen data.

## Key Insights

Some high-level insights from the analysis include:

- Location and room type are among the strongest drivers of Airbnb pricing.
- Entire homes consistently command higher prices than private or shared rooms.
- Listings with higher review counts and better availability patterns tend to show more stable pricing.
- Extreme price outliers can significantly distort model performance if not handled carefully.

## Tools & Technologies

- **Python**
- **pandas, numpy**
- **matplotlib, seaborn**
- **scikit-learn**
- **Jupyter Notebook**

## How to Run

To reproduce the analysis and results:

1. Clone the repository:
