# Portfolio Optimisation Using Evolutionary Algorithms and Machine Learning

## Overview

This project investigates portfolio optimisation under a quantitative finance framework by comparing classical optimisation techniques with modern metaheuristic and machine learning approaches.

Using historical S&P 500 market data, the study evaluates Mean-Variance Optimisation (MVO), Simulated Annealing (SA), Genetic Algorithms (GA), and Bayesian Neural Networks (BNN) across multiple experimental trials.

Performance is assessed using risk-adjusted return metrics, portfolio diversification, drawdown behaviour, and computational efficiency. The objective is to understand the trade-off between theoretical optimality, robustness, and practical investment performance under realistic market conditions.

---

## Research Questions

1. Which optimisation method achieves the highest risk-adjusted return?

2. How robust are different optimisation algorithms across multiple market scenarios?

3. Can metaheuristic methods outperform traditional Markowitz optimisation?

4. What are the trade-offs between return, risk, diversification, and computational cost?

5. How effective are machine learning approaches for portfolio allocation?

---

## Dataset

| Feature | Description |
|----------|-------------|
| Market | S&P 500 |
| Asset Classes | Equities |
| Frequency | Daily Prices |
| Variables | Returns, Covariance Matrix, Portfolio Weights |
| Period | Historical Market Data |

---

## Methodology

### Classical Finance

- Mean-Variance Optimisation (MVO)
- Efficient Frontier Analysis
- Sharpe Ratio Maximisation

### Metaheuristic Optimisation

- Genetic Algorithms (GA)
- Simulated Annealing (SA)

### Machine Learning

- Bayesian Neural Networks (BNN)
- Predictive Return Modelling

### Evaluation Metrics

- Sharpe Ratio
- Cumulative Return
- Volatility
- Maximum Drawdown
- Portfolio Diversification
- Runtime Analysis

---

## Key Findings

### Genetic Algorithms Produce Strong Risk-Adjusted Performance

Genetic Algorithms consistently generated highly competitive portfolios with strong Sharpe Ratios and robust diversification characteristics.

### Simulated Annealing Balances Exploration and Stability

Simulated Annealing achieved competitive solutions while maintaining relatively stable performance across repeated trials.

### Mean-Variance Optimisation Remains Competitive

Traditional MVO provided stable allocations but demonstrated sensitivity to estimation error in expected returns and covariance matrices.

### Bayesian Neural Networks Improve Adaptability

BNN-based approaches adapted better to changing market conditions but required substantially greater computational resources.

### No Single Method Dominates All Metrics

Different optimisation methods excelled under different evaluation criteria, highlighting the importance of aligning optimisation objectives with investment goals.

---

## Technical Skills Demonstrated

### Quantitative Finance

- Portfolio Optimisation
- Asset Allocation
- Risk Management
- Sharpe Ratio Analysis
- Modern Portfolio Theory

### Optimisation

- Genetic Algorithms
- Simulated Annealing
- Metaheuristic Search
- Constrained Optimisation

### Machine Learning

- Bayesian Neural Networks
- Financial Prediction
- Model Evaluation

### Programming

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- TensorFlow / PyTorch
- Matplotlib

---
