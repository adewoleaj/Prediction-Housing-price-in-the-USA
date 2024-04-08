# Prediction-Housing-price-in-the-USA


## Overview

This repository contains a Python script for predicting housing prices using the USA housing dataset. The goal is to build a regression model to predict housing prices and evaluate its performance on both the training and test sets. Additionally, we determine if the model overfits or underfits and explore methods for improvement


## Dataset

The USA housing dataset consists of various features such as average area income, average area house age, average area number of rooms, average area number of bedrooms, and area. These features are used to predict house prices. The dataset contains 5000 data points, which are split into training and testing sets with a ratio of 80:20 (4000 to 1000).

## Methodology

  - **Exploratory Data Analysis (EDA):** We explore the dataset by checking its dimensions, column names, and displaying scatter plots of some features.
  - **Data Preprocessing:** We select features and the target variable, then split the data into training and test sets. The data is also scaled using StandardScaler.
  - **Model Building:** We build regression models using Linear Regression, Ridge Regression, and Lasso Regression algorithms.
  - **Model Evaluation:** We evaluate the models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared. We                             also calculate adjusted R-squared to penalize the models for adding unimportant features.

## Results

Overall, all three models (Linear Regression, Ridge Regression, and Lasso Regression) perform similarly in terms of their performance metrics on the test dataset. The R-squared values indicate that each model explains approximately 91.46% of the variance in the data. The mean absolute percentage error (MAPE) is around 7.48%, suggesting that, on average, the models' predictions deviate by approximately 7.48% from the actual prices.

Based on the provided performance metrics, all three models show similar performance on the test dataset. Therefore, the choice of the "best" model could depend on other factors such as interpretability, computational efficiency, or the specific goals of the analysis. It's recommended to consider these factors in the context of your project requirements to determine the most suitable model.

## Usage

To run the script:

   1. Clone this repository.
   2. Ensure you have the required packages installed (**pandas**, **numpy**, **seaborn**, **matplotlib**, **scikit-learn**).
   3. No additional configuration is required beyond the installation steps. However, you may need to adjust the path to your dataset and model directory according to your local setup
   4. Run the Python script housing_price_prediction.py


## Author

**_Adewole Adetoro Ajala_**

For any inquiries, please contact: woltoaj@gmail.com / woltoajai@gmail.com

Feel free to contribute or provide feedback!
