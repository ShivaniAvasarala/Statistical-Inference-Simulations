# Statistical Inference Simulations

This repository contains Python simulations and visualizations for key concepts in statistical inference, focusing on the Central Limit Theorem (CLT) and Confidence Intervals (CI).

## Project Overview

This project aims to demonstrate and explore fundamental statistical concepts through practical simulations using real and simulated data. It consists of two main components:

1. Central Limit Theorem Simulations
2. Confidence Interval Estimations

## 1. Central Limit Theorem Simulations

### Key Features:
- Demonstrates the CLT using Gaussian and skewed (exponential) population distributions
- Explores the effect of sample size on sampling distributions
- Investigates the impact of population skewness on the CLT
- Verifies the empirical rule (68-95-99.7 rule) for sampling distributions

### Experiments:
- Sampling from Gaussian and exponential populations
- Comparison of theoretical and simulated standard deviations
- Visualization of sampling distributions for various sample sizes
- Analysis of CLT applicability for different levels of population skewness

## 2. Confidence Interval Estimations

### Key Features:
- Calculates and analyzes confidence intervals for planet orbital periods
- Compares CI performance when population standard deviation is known vs. unknown
- Demonstrates the practical application and interpretation of confidence intervals

### Experiments:
- CI estimation using the 'planets' dataset from seaborn
- Simulation of 95% and 99% confidence intervals
- Analysis of CI coverage for known and unknown population standard deviation cases

## Dataset
- The CI project uses the 'planets' dataset from the seaborn library

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Key Findings
- CLT simulations demonstrate the convergence to normality as sample size increases
- CI simulations reveal unexpected behavior in coverage probabilities, especially when the population standard deviation is unknown

## How to Run
1. Clone this repository
2. Ensure you have the required libraries installed
3. Run the Jupyter notebooks or Python scripts in each project folder

## Future Work
- Explore additional distributions and their effects on the CLT
- Investigate alternative methods for constructing robust confidence intervals
- Extend the analysis to other statistical inference concepts
