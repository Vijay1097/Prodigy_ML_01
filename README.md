# 🏡 House Price Prediction using Linear Regression

![Task Banner](TASK-1.jpg)

## 📌 Task Description

**Task-01**  
Implement a **linear regression model** to predict the prices of houses based on:
- Square footage (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of bathrooms (`FullBath + 0.5 × HalfBath`)

**Dataset**: [Kaggle - House Prices Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

---

## 📁 Dataset Overview

- Train Dataset Shape: `(1460, 81)`
- Test Dataset Shape: `(1459, 80)`
- Target Variable: `SalePrice`

---

## 🧹 Data Preprocessing

- Selected Features:
  - `GrLivArea` (Square Footage)
  - `BedroomAbvGr` (Number of Bedrooms)
  - `TotalBathrooms = FullBath + 0.5 * HalfBath`
- Checked and handled missing values
- Standardized the features using `StandardScaler`

---



## 📈 Model Evaluation

### Training Performance:
- RMSE: `$XXXXX.XX`
- MAE: `$XXXXX.XX`
- R² Score: `0.XXXX`

### Test Performance:
- RMSE: `$XXXXX.XX`
- MAE: `$XXXXX.XX`
- R² Score: `0.XXXX`

> 📷 *Insert Actual vs Predicted and Residual plots here*

![Model Evaluation](https://github.com/Vijay1097/Prodigy_ML_01/blob/main/output%201.png)

---

## 📌 Model Insights

- **Coefficients:**
  - `GrLivArea`: $XXXX.XX
  - `BedroomAbvGr`: $XXXX.XX
  - `TotalBathrooms`: $XXXX.XX
- **Intercept**: $XXXX.XX

### Linear Regression Equation:
