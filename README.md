# Mixture-Distribution-of-Portfolio-Returns

## Introduction
A mixture distribution, also called a compound distribution, is a univariate or multivariate statistical distribution that "can be expressed as superpositions of component distributions" (Everitt, 2013). Mixture distributions are often used to model scenarios where a population consists of multiple subpopulations, each with distinct statistical characteristics.

In portfolio optimization, some assets within a given portfolio may share common probabilistic characteristics that differ from others in the same portfolio. This results in sub-distributions within the overall portfolio distribution. To realistically model such portfolios, mixture distribution analysis is essential (see Luxenberg et. al, 2022).

## About This Project

In this project, we apply mixture distribution analysis using Python. We construct a bivariate mixture distribution to model the returns of a portfolio of two assets under two distinct market regimes:

A favorable market regime, where returns are generally positive.
A turbulent market regime, where returns are mostly volatile and possible negative.
We assume that the return of the portfolio under each regime follows a bivariate normal distribution, each with its own mean vector and covariance matrix.

The primary objectives of this project are to:

1. Analyze the characteristics of the resulting mixture distribution.
2. Compute a theoretical univariate distribution of the portfolio returns.
3. Perform a Monte Carlo simulation, generating 500 portfolio return samples from the mixture distribution.
4. Compare the simulated empirical distribution with the theoretical univariate distribution derived from the given parameters.
