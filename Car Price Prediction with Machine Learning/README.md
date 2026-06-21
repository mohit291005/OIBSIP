# Car Price Prediction with Machine Learning

## Objective

The objective of this project is to build a machine learning model that predicts the selling price of a used car based on various features such as car age, kilometers driven, fuel type, seller type, transmission type, ownership history, and brand.

## Dataset

The dataset used in this project is the **Car Details from CarDekho Dataset**, which contains information about used cars listed for sale.

### Features

* Name
* Year
* Selling Price (Target Variable)
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

Loaded the CarDekho dataset containing used car details.

### 2. Data Cleaning

* Checked for missing values
* Removed duplicate records
* Standardized categorical values

### 3. Feature Engineering

* Calculated **Car Age** from the manufacturing year
* Extracted **Brand Name** from the car name

### 4. Exploratory Data Analysis (EDA)

* Distribution of selling prices
* Selling price vs fuel type
* Selling price vs car age
* Correlation analysis

### 5. Data Preprocessing

* One-Hot Encoding for categorical variables
* Feature selection and preparation

### 6. Model Building

The following regression models were trained:

* Linear Regression
* Random Forest Regressor

### 7. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 8. Feature Importance Analysis

Identified the most influential factors affecting car prices.

## Results

Random Forest Regressor achieved the best performance and provided more accurate predictions compared to Linear Regression.

Key factors influencing car prices:

* Car Age
* Kilometers Driven
* Brand
* Fuel Type
* Transmission Type

## Conclusion

This project demonstrates how machine learning can be used to predict used car prices accurately. The model can assist buyers and sellers in estimating a fair market value for vehicles based on their characteristics.

## Author

Mohit Joshi

## Internship

Oasis Infobyte Data Science Internship (OIBSIP)
