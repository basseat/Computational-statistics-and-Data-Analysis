# Exercise Sheet 5 – Optimisation & Hypothesis Testing

## Tasks

### Task 1 – Logistic Regression (Bernoulli/Logistic Model)
Fits a two-parameter logistic model p(yᵢ=1|xᵢ) = σ(β(xᵢ−θ)) to binary data using two optimisation methods:

- **Gradient Descent** – fixed learning rate, converges in ~thousands of iterations.
- **Newton-Raphson** – second-order method with Armijo backtracking line search, converges in ~6 iterations.

Both methods recover the same MLE: β ≈ 2.414, θ ≈ 0.438.

### Task 2 – COVID-19 Reproduction Rate & Sign Test
Estimates the weekly reproduction number R̂ for 16 European countries before (09.03.2020) and after (23.03.2020) social distancing measures, then applies a **non-parametric sign test** to assess whether distancing significantly reduced R.

Result: p-value ≈ 0.002 → reject H₀ at α = 0.05; statistically significant reduction in R.

## Dependencies
`numpy`, `pandas`, `matplotlib`, `scipy`
