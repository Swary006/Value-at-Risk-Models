📊 Value-at-Risk (VaR) Models in Python
📌 Project Overview

This repository contains three Value-at-Risk (VaR) models implemented in Python:

   • Historical Method

   • Parametric (Variance-Covariance) Method

   • Monte Carlo Simulation (with correlated asset returns)

Each model is designed for portfolio-level risk estimation and includes:

   • CVaR (Expected Shortfall) — Basel III / FRTB compliant tail-risk measure

   • Backtesting — Validation of VaR predictions against historical returns

   • Python + yFinance — Real market data retrieval for accuracy and realism

🛠 Features

  • Multiple confidence levels (90%, 95%, 99%)

  • Custom portfolio weights or equal weighting

  • Support for multi-day VaR scaling

  • Plots for VaR, CVaR, and breach events

  • Backtesting breach counts and rates

📈 Methodology Summary
1. Historical Method

   • Uses actual past portfolio returns to estimate VaR without distributional assumptions.

   • CVaR calculated as mean of losses beyond VaR threshold.

2. Parametric Method

   • Assumes normally distributed returns.

   • VaR & CVaR calculated using analytical formulas from mean & standard deviation of portfolio returns.

3. Monte Carlo Simulation

   • Simulates correlated portfolio returns using Cholesky decomposition.

   • Estimates VaR & CVaR from simulated loss distribution.

🛠️ Installation & Usage

  Clone the repo

    git clone https://github.com/Swary006/Value-at-Risk-Models.git
    cd Value-at-Risk-Models

  Install dependencies

    pip install -r requirements.txt

  Run the notebooks

  Open Jupyter and run any of the .ipynb files:
  
    jupyter notebook

📚 Skills Demonstrated

  • Financial risk modelling (VaR, CVaR)

  • Monte Carlo simulation with correlation

  • Backtesting & model validation

  • Data acquisition with yfinance

  • Python data analysis (pandas, numpy, matplotlib)
