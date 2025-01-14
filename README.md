Thier are ssome other codes and files are also availe but this readme files is mainly for the housing and sales code files you can see it 

Final year project 

The main goal of my project was to build predictive models to predcit housing prices based on property attributes. By handling challenges like missing values and outliers.
my aims was to create models that could capture the complex patterns in housing data.

Datasets
Connecticut Real Estate Sales Data:
Includes historical property transactions with details like sale amount, assessed value, and property type.
Source: Data.gov

USA Housing Listings Data:
Contains rental listings with features like rent price, property size, and amenities.
Source: Kaggle

Models
Linear Regression: A simple baseline model to compare with advanced methods.
Random Forest: Handles non-linear relationships and identifies important features.
LightGBM: A fast and efficient gradient boosting model, ideal for large datasets.
ANNs: Captures complex patterns and non-linear dependencies.

Preprocessing:
Handled missing values by imputation or column removal.
Transformed skewed features like Sale Amount and Price using log transformations.
Encoded categorical variables and scaled numerical features for better model compatibility.

Model Training:
Used tools like grid search and early stopping to optimize hyperparameters.
Evaluated models using metrics like MAE, RMSE, and R² Score.
