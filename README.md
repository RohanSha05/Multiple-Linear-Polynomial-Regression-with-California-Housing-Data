# **MULTIPLE LINEAR & POLYNOMIAL REGRESSION**

## **PROJECT DESCRIPTION**
This repository contains a Google Colab notebook that introduces **Multiple Linear Regression** and **Polynomial Regression** using the **California Housing Dataset** from `scikit-learn`.  
The project demonstrates how regression models are implemented, evaluated, and compared on real-world data.

---

## **DATASET**
- **Name:** California Housing Dataset  
- **Source:** `sklearn.datasets.fetch_california_housing`  
- **Target Variable:** `MedHouseVal`

---

## **PROJECT STRUCTURE**

### **SECTION 0: SETUP & DATA EXPLORATION**
- Import required libraries (`NumPy`, `Pandas`, `Matplotlib`, `scikit-learn`)
- Load the dataset
- Explore:
  - Dataset shape
  - First rows
  - Dataset information
  - Summary statistics

---

### **SECTION 1: MULTIPLE LINEAR REGRESSION**
- Define target variable: **MedHouseVal**
- Select features:
  - `MedInc`
  - `HouseAge`
  - `AveRooms`
  - `AveBedrms`
  - `Population`
  - `AveOccup`
- Analyze correlations between features and target variable

---

### **SECTION 3: MULTIPLE LINEAR REGRESSION IMPLEMENTATION**
- Split data into training and test sets
- Train a **LinearRegression** model
- Inspect model coefficients and intercept
- Generate predictions
- Evaluate performance using:
  - **MAE (Mean Absolute Error)**
  - **RMSE (Root Mean Squared Error)**
  - **R² Score**
- Visualize:
  - Predicted vs actual values
  - Residual plots

---

### **SECTION 4: INTRODUCTION TO POLYNOMIAL REGRESSION**
- Explain the concept of polynomial regression
- Use **MedInc** as a single feature
- Fit and visualize a simple linear regression model

---

### **SECTION 6: POLYNOMIAL REGRESSION IMPLEMENTATION**
- Generate polynomial features using **PolynomialFeatures**
- Train models with polynomial degrees:
  - **1**
  - **2**
  - **3**
  - **5**
- Use **Pipeline** for feature transformation and regression
- Compare models using:
  - **R² Score**
  - **RMSE**

---

## **TECHNOLOGIES USED**
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **scikit-learn**
- **Google Colab**

---

## **HOW TO RUN**
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Run all cells in order.
3. The dataset is loaded directly from `scikit-learn` (no manual download required).

---

## **PURPOSE**
This project is intended for **educational purposes** and demonstrates:
- Multiple Linear Regression on real-world data
- Polynomial Regression and model complexity
- Model evaluation and visualization techniques
