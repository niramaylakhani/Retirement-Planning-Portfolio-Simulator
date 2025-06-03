# Retirement-Planning-Portfolio-Simulator

This project is a simulation-based retirement planning tool designed to assess the sustainability of retirement withdrawals over time, factoring in investment returns, inflation, and stress scenarios. It was developed as part of a coursework project.

## 📈 Overview

The simulator allows users to:
- Generate return simulations for equities and bonds using historical statistics.
- Blend them into a rebalanced portfolio based on user-defined weights.
- Calculate sustainable withdrawals lasting until a desired horizon age with 95% confidence.
- Estimate the required starting portfolio value for a given distribution goal.
- Run stress tests simulating early losses.

## 🔧 Features

- User Inputs: Initial Portfolio Value, Age, Asset Allocation, Desired Withdrawal, Inflation Rate
- Monte Carlo Simulations: 100 paths of bond and equity returns
- Portfolio Rebalancing: Annual rebalancing of assets
- Percentile Summary Table: 25th, 50th, and 75th percentile outcomes
- Sustainability Calculator: Determine the maximum sustainable withdrawal
- Requirement Estimator: Calculate the starting assets required
- Stress Testing: Apply a 10% drawdown in the first two years

## 📊 Inputs & Assumptions

- Portfolio Value and Asset Weights (user-defined)
- Inflation estimate used to adjust distributions
- Historical return means and standard deviations (used for random sampling)
- Annual rebalancing

## 🧪 Monte Carlo Simulation

Simulates 100 return paths using:
- Equity and bond return distributions
- Portfolio-weighted blending
- Random sampling with annual compounding

## 💻 Usage

The tool is built in Excel with VBA macros (see `.xlsm` file). Enable macros to use the simulation features.

## 📁 Files

- `Project 3.xlsm` — Excel file with simulation and input interface
- `Project Three.pdf` — Project description and grading rubric

## 📌 License

This project is developed for educational purposes and is not intended for professional financial planning without validation.

---

