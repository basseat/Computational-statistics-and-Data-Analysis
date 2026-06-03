# Exercise Sheet 4 – Bayesian Linear Regression

## Topic
Bayesian and frequentist parameter estimation for a multiple linear regression model predicting **life expectancy** from adult mortality and infant deaths (WHO Life Expectancy dataset).

## Tasks

### 1. Least Squares Estimation
Estimates β₀, β₁, β₂ and σ² for the model:

> y = β₀ + β₁x₁ + β₂x₂ + ε

using the closed-form OLS formula.

### 2. Bayesian Sequential Update
Implements a conjugate Normal-Inverse-Gamma Bayesian update loop, processing data year-by-year (2000–2015) and tracking how the posterior means of the regression coefficients evolve over time. Results are compared visually against the OLS estimates.

## Dependencies
`numpy`, `scipy`, `matplotlib`, `pandas`, `sympy`
