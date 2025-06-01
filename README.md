# pima-diabetes-analysis
Logistic regression and EDA using the Pima Indians Diabetes dataset.
This repository contains a notebook that performs exploratory data analysis (EDA) and logistic regression modeling using the **Pima Indians Diabetes Dataset**.  
The dataset includes clinical data from female patients of Pima Indian heritage (aged 21 or older) and is widely used for binary classification tasks related to diabetes prediction.

---

## Objectives

- Perform exploratory data analysis to understand variable relationships
- Fit a logistic regression model to predict the presence of diabetes (`Outcome`)
- Interpret the model using coefficients and odds ratios

---

## Dataset Source

The dataset is publicly available on Kaggle:

🔗 [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## Libraries Used

- `pandas` — data manipulation  
- `numpy` — numerical operations  
- `seaborn` & `matplotlib` — data visualization  
- `statsmodels` — statistical modeling (logistic regression)  
- `plotly` — interactive visualization of leverage points  

---

## Notebook Contents

- Dataset loading and description  
- Descriptive statistics and correlation matrix  
- Scatter plot matrix (with and without class coloring)  
- Logistic regression model with interpretation of coefficients and p-values  
- Calculation and interpretation of odds ratios    

---

## Key Insights

- **Glucose** and **BMI** were identified as the most statistically significant predictors of diabetes.
- Odds ratios provided a more interpretable measure of impact for each variable.
- High-leverage observations were explored using interactive visualizations.

---

## How to Use

You can run the notebook on [Google Colab](https://colab.research.google.com/) by uploading the `diabetes.csv` file manually or by fetching it via Kaggle's API.

