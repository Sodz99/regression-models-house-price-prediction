# Build Regression Models in Python for House Price Prediction

The goal is to predict sale prices for homes in Pune city.

## Overview
The price of a house is based on several characteristics such as location, total area, number of rooms, various amenities available, etc. In this project, we will perform house price prediction for 200 apartments in Pune city. Different regression models such as Linear, Random Forest, XGBoost, etc., will be implemented. Also, multi-layer perceptron (MLP) models will be implemented using scikit-learn and TensorFlow. This house price prediction project will help you predict the price of houses based on various features and house properties.

## Data
We are given a real estate dataset with around 200 rows and 17 different variables that play an important role in predicting our target variable, i.e., price.

_Data is not included in this repository._

## Approach
1. Data Cleaning
- Importing the required libraries and reading the dataset.
- Preliminary exploration
- Check for the outliers and remove outliers.
- Dropping of redundant feature columns
- Missing value handling
- Regularizing the categorical columns
- Save the cleaned data
2. Data Analysis
- Import the required libraries and read the cleaned dataset.
- Converting binary columns to dummy variables
- Feature Engineering
- Univariate and Bivariate analysis
- Check for correlation
- Feature selection
- Data Scaling
- Saving the final updated dataset
3. Model Building
- Data preparation
- Performing train test split
- Linear Regression
- Ridge Regression
- Lasso Regressor
- Elastic Net
- Random Forest Regressor
- XGBoost Regressor
- K-Nearest Neighbours Regressor
- Support Vector Regressor
4. Model Validation
- Mean Squared Error
- R2 score
- Plot for residuals
5. Performs the grid search and cross-validation for the given regressor
6. Fitting the model and making predictions on the test data
7. Checking for Feature Importance
8. Model comparisons.
9. MLP (Multi-Layer Perceptron) Models
- MLP Regression with scikit-learn
- Regression with TensorFlow

Modular code overview

Once you unzip the modular_code.zip file, you can find the following folders within it.
- input
- src
- output
- lib
1. Input folder - It contains all the data that we have for analysis.
- Real_Estate Data.xlsx

2. Src folder - This is the most important folder of the project. This folder contains all the modularized code for all the above steps in a modularized manner. This folder consists of:
- engine.py
- ML_Pipeline The ML_pipeline is a folder that contains all the functions put into different python files, which are appropriately named. These python functions are then called inside the engine.py file.

## Tech stack
⮚ Language - Python ⮚ Libraries - sklearn, pandas, NumPy, matplotlib, seaborn, xgboost

## How to run
```bash
pip install -r modular-code/requirements.txt
python modular-code/src/engine.py
```
Notebooks: [`resd_analysis.ipynb`](modular-code/lib/resd_analysis.ipynb), [`resd_cleaning.ipynb`](modular-code/lib/resd_cleaning.ipynb), [`resd_mlp.ipynb`](modular-code/lib/resd_mlp.ipynb), [`resd_models.ipynb`](modular-code/lib/resd_models.ipynb)

## Project structure
```
.gitignore
README.md
modular-code/
  lib/
    resd_analysis.ipynb
    resd_cleaning.ipynb
    resd_mlp.ipynb
    resd_models.ipynb
  readme.md
  requirements.txt
  src/
    ML_Pipeline/
    engine.py
```

## Credits
Based on a ProjectPro guided project.
