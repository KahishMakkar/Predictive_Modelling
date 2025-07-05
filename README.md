# Predictive_Modelling

# Machine Learning Projects: Regression with Statsmodels

This repository showcases two regression projects using Python's `statsmodels` library:
- **Linear Regression** for predicting car sales
- **Logistic Regression** for predicting loan approvals

These Jupyter Notebooks walk through data analysis, model building, and interpretation using statistical methods.

---

## 📁 Files

- `linear_regression.ipynb`  
  Predicts car sales based on vehicle attributes like price, engine size, horsepower, and fuel efficiency using OLS (Ordinary Least Squares).

- `logistic_regression.ipynb`  
  Classifies loan approvals using logistic regression (maximum likelihood estimation).

- `linear_regression_cars_sales.csv`  
  Dataset containing car features like price, mileage, engine size, and other specifications used to predict sales or resale value.


- `logistic_regression_bankloans.csv`  
  Dataset with applicant information such as age, education, employment history, income, and debt ratios, used to predict loan default.
---

## 📌 Project 1: Linear Regression (OLS)

### Objective:
Use linear regression to understand how vehicle features influence car sales.

### Key Steps:
- Import data with `pandas`
- Visualize relationships using `seaborn`
- Build OLS model with `statsmodels.api.OLS`
- Interpret coefficients, R², p-values, confidence intervals

### Dataset Preview:
| Manufacturer | Model   | Sales_in_thousands | Price_in_thousands | Engine_size | Horsepower | Fuel_efficiency |
|--------------|---------|--------------------|---------------------|-------------|------------|-----------------|
| Acura        | Integra | 16.919             | 21.50               | 1.8         | 140.0      | 28.0            |
| Acura        | TL      | 39.384             | 28.40               | 3.2         | 225.0      | 25.0            |
| ...          | ...     | ...                | ...                 | ...         | ...        | ...             |


---

## 📌 Project 2: Logistic Regression

### Objective:
Classify loan approvals based on customer attributes.

### Key Steps:
- Encode binary target
- Visualize distribution of features
- Build model using `statsmodels.api.Logit`
- Evaluate with accuracy, confusion matrix, and model summary

### Dataset Preview:
| age | ed | employ | address | income | debtinc | creddebt | othdebt | default |
|-----|----|--------|---------|--------|---------|----------|---------|---------|
| 41  |  3 |     17 |      12 |    176 |     9.3 |   11.36  |   5.01  |    1    |
| ... | .. |    ... |     ... |    ... |    ...  |   ...    |   ...   |   ...   |

---

## ✅ Requirements

Ensure the following libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn statsmodels
