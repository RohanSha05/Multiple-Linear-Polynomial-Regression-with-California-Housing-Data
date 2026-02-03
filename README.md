# Multiple-Linear-Polynomial-Regression-with-California-Housing-Data
This repository contains a Google Colab notebook that introduces Multiple Linear Regression and Polynomial Regression using the California Housing dataset from sklearn. The notebook walks through both the theory and practical implementation of regression models, making it suitable for beginners and early-intermediate learners in machine learning.
Section 0: Setup & Data Exploration

Imports required libraries (NumPy, Pandas, Matplotlib, scikit-learn)

Loads the California Housing dataset

Displays:

Dataset shape

First few rows

Dataset information (.info())

Summary statistics (.describe())

Section 1: Multiple Linear Regression

Defines:

Target variable: MedHouseVal

Features: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup

Checks data shapes

Visualizes correlations between features and the target variable

Section 3: Multiple Linear Regression — Full Implementation

Splits data into training and test sets

Trains a LinearRegression model

Examines:

Model coefficients

Intercept

Makes predictions on training and test data

Evaluates model performance using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² score

Visualizes:

Predicted vs. actual values

Residual plots

Section 4: Introduction to Polynomial Regression

Introduces polynomial regression conceptually

Uses a single feature (MedInc) to predict house value

Fits a simple linear model

Visualizes the linear relationship to build intuition

Section 6: Polynomial Regression — Implementation

Applies polynomial regression using PolynomialFeatures

Tests multiple polynomial degrees: 1, 2, 3, and 5

Uses Pipeline to combine feature transformation and regression

Compares model performance using:

R² score

RMSE

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

scikit-learn

Google Colab

🚀 How to Run

Open the notebook in Google Colab or a local Jupyter environment.

Run the cells in order from top to bottom.

No additional dataset download is required—the dataset is loaded directly from scikit-learn.

🎯 Learning Outcomes

By the end of this notebook, you will understand:

How multiple linear regression works on real data

How to evaluate regression models effectively

Why and when polynomial regression can improve performance

The trade-off between model complexity and overfitting

📌 Dataset

California Housing Dataset
Source: sklearn.datasets.fetch_california_housing
