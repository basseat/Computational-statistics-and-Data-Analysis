# Exercise Sheet 6 – Hypothesis Testing & MCMC

## Tasks

### Task 1 – Two-Sample t-Test
Tests whether two independent samples X_A and X_B have equal means at significance level α = 0.01, using the pooled two-sample t-statistic. Result: p ≈ 0.39 → fail to reject H₀.

### Task 2 – Chi-Squared Variance Test
Tests whether a sample's variance is consistent with a known precision (σ = 0.2 K) using the χ²-statistic. Performed in two variants: unknown mean (χ²(n−1)) and known mean μ = 10.1 K (χ²(n)). Both cases fail to reject H₀.

### Task 3 – MCMC Parameter Estimation (Metropolis-Hastings)
Fits a **damped harmonic oscillator** ODE to displacement data by sampling the posterior of (c, k) using the Metropolis-Hastings algorithm. The likelihood is defined via MSE between simulated and observed trajectories. Results include 2D and marginal posterior histograms after a burn-in of 20 000 iterations with thinning by 5.

## Dependencies
`numpy`, `scipy`, `matplotlib`, `pandas`, `sympy`
