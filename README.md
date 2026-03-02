#  Ridge vs Lasso Regression on California Housing Dataset

This project demonstrates the implementation and comparison of Ridge and Lasso Regression models using the California Housing dataset.

The objective is to understand how regularization techniques impact model performance and generalization.

---

##  Project Overview

Regularization helps prevent overfitting by penalizing large coefficients.

- **Ridge Regression (L2 Regularization)** → Shrinks coefficients but keeps all features.
- **Lasso Regression (L1 Regularization)** → Shrinks coefficients and performs feature selection by setting some coefficients to zero.

Both models are evaluated using the *R² Score*.

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Dataset

- California Housing Dataset  
- Loaded using `sklearn.datasets.fetch_california_housing.`

Target Variable:
- Median House Value

---

##  Steps Performed

1. Loaded the dataset
2. Performed train-test split
3. Applied feature scaling using StandardScaler
4. Implemented:
   - Ridge Regression
   - Lasso Regression
5. Selected optimal alpha value
6. Evaluated models using R² Score

---

##  Model Results

- **Ridge Regression R² Score:** 0.34  
- **Lasso Regression R² Score:** 0.59  

Lasso Regression outperformed Ridge Regression in this project, indicating better feature selection and improved model generalization.

Aurthor 
Amisha Srivastava
