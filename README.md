# Mixture-Distribution-of-Portfolio-Returns
In this project, we apply mixture distribution analysis using Python. We construct a bivariate mixture distribution to model the returns of a portfolio of two assets under two distinct market regimes:

A favorable market regime, where returns are generally positive.
A turbulent market regime, where returns are mostly volatile and possible negative.
We assume that the return of the portfolio under each regime follows a bivariate normal distribution, each with its own mean vector and covariance matrix.

The primary objectives of this project are to:

1. Analyze the characteristics of the resulting mixture distribution.
2. Compute a theoretical univariate distribution of the portfolio returns.
3. Perform a Monte Carlo simulation, generating 500 portfolio return samples from the mixture distribution.
4. Compare the simulated empirical distribution with the theoretical univariate distribution derived from the given parameters.
