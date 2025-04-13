# HealthCost-Explorer

> A regression modeling project to analyze and predict health insurance premiums using demographic and lifestyle factors. 

## 📊 Objective

To identify key drivers of health insurance charges and build a robust regression model using transformations, diagnostics, and interaction terms for accurate prediction.

---

## 🔍 Dataset

- Source: [Kaggle - Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance/data)
- 1,338 observations with variables: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`

---

## 🧠 Methods

- Exploratory Data Analysis (EDA)
- Linear Regression
- Interaction Terms (e.g., BMI × Smoker)
- Heteroscedasticity Checks (Residual plots, Scale-Location)
- Multicollinearity (VIF)
- Autocorrelation (Durbin-Watson Test)
- Log-transformations
- Outlier Removal (Cook’s Distance)

---

## 📈 Model Insights

- Initial R²: 0.747 → Final R²: **0.9526** (Adjusted: 0.9521)
- Test R²: **0.8298**
- Significant Predictors:
  - Age (+)
  - Number of Children (+)
  - Smoker × BMI interaction (strong positive)
- Applied log transformation and removed influential points for improved model fit

---

## 📁 Repository Structure

- `notebooks/`: R scripts or .Rmd notebooks with all code
- `reports/`: Detailed report of all the observations and plots generated throughput the EDA
- `data/`: Input dataset

---


## 👤 Author

Gayathri Ananya  
[LinkedIn](https://www.linkedin.com/in/gayathri-ananya-175584174) 
[Email](mailto:ananyabpgayathri25@gmail.com)

