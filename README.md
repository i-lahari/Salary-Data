# Salary-Data:

Fitting Simple Linear Regression Model on Salary Data

**Overview:**

This project implements Simple Linear Regression from scratch to predict salaries based on years of experience. The implementation demonstrates the fundamental concepts of linear regression without using built-in machine learning libraries.

**Dataset:**

The dataset contains two columns:

- Years of Experience
- Salary

**Insights:**

- No outliers in both the columns
- Majority of them are paid around 60,000
- Most of them have 3-5 years of experience
- The frequencies are not uniform, with some bins (e.g., around 8 years) having fewer counts compared to others
- Positive Corelation - Salary is increasing as the number of years in experience increases.
- **Holds Linear Relationship** between dependent and independent variables - Satisfied the assumption of linear regression

**Approach:**

Implemented OLS (Ordinary Least Squares) regression using:

**Slope (m):**

$m = Σ((X_i - mean(X)) * (y_i - mean(y))) / Σ((X_i - mean(X))^2)$

Where:

>X_i: Individual years of experience

>y_i: Individual salary values

>mean(X): Average years of experience

>mean(y): Average salary

**Intercept (b):**

$b = mean(y) - m * mean(X)$

This gives us the linear equation: y = mx + b, where y is the predicted salary for years of experience x.

**Final Results:**

**Slope :** 9339.081723815194

**Intercept : ** 24985.530162511714
