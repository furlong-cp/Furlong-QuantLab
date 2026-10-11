# Furlong QuantLab

A quantitative finance and numerical computing project exploring option valuation, sensitivity analysis, Monte Carlo methods, and portfolio risk using C++ and Python.

## Overview

Quantitative finance combines mathematical modeling, numerical algorithms, and computational implementation.

Furlong QuantLab aims to implement core pricing methods, validate numerical results, and investigate the trade-offs between accuracy and computational cost.

## Core Modules

### 1. Option Pricing

* Black–Scholes European option pricing
* Binomial-tree pricing
* Monte Carlo pricing
* Implied-volatility estimation

### 2. Sensitivity Analysis

* Delta
* Gamma
* Vega
* Theta
* Rho

### 3. Numerical Methods

* Root-finding for implied volatility
* Monte Carlo convergence analysis
* Variance-reduction techniques
* Numerical stability and error analysis

### 4. Risk Analysis

* Portfolio valuation
* Scenario analysis
* Sensitivity-based risk measurements
* Aggregation of instrument-level exposures

## Technical Stack

* C++20 for numerical implementations
* Python for independent validation and visualization
* NumPy and SciPy for reference calculations
* CMake
* GoogleTest

## Validation Methodology

* Compare independent implementations.
* Test mathematical boundary cases.
* Check option-price bounds and monotonicity properties.
* Compare analytical Greeks with finite-difference estimates.
* Study convergence as simulation counts increase.
* Report numerical error alongside runtime.

## Research Questions

* How does Monte Carlo error scale with the number of simulations?
* How do variance-reduction methods affect convergence?
* What are the numerical trade-offs between pricing algorithms?
* How accurately can implied volatility be recovered from a theoretical option price?
* How do portfolio sensitivities change under different market scenarios?

## Project Status

Under development. Pricing accuracy, benchmark results, and supported model assumptions will be documented as modules are completed.

## Limitations

Models rely on assumptions that may not reflect actual market conditions. Numerical accuracy and theoretical pricing consistency do not establish trading profitability.

## Objective

Build a tested and reproducible quantitative finance library that connects mathematical theory with efficient implementation.
