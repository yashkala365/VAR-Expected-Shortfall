# Value at Risk (VaR) & Expected Shortfall Risk Analytics Dashboard

An institutional-style quantitative finance project that measures portfolio downside risk using multiple Value at Risk (VaR) methodologies and Expected Shortfall (Conditional VaR).

The dashboard downloads live market data, constructs a diversified equity portfolio, calculates Historical VaR, Parametric VaR, Monte Carlo VaR, and Expected Shortfall, and visualizes portfolio risk through interactive charts.

---

## Project Overview

Risk management is one of the most important functions in investment banking, hedge funds, asset management, and quantitative finance.

This project builds a complete portfolio risk analytics dashboard capable of estimating potential portfolio losses under different statistical assumptions.

The notebook demonstrates several industry-standard risk measurement techniques and compares their results using real financial market data.

---

## Features

- Live market data from Yahoo Finance
- Multi-Asset Portfolio Construction
- Historical Value at Risk (VaR)
- Parametric (Variance-Covariance) VaR
- Monte Carlo VaR Simulation
- Expected Shortfall (Conditional VaR)
- Portfolio Growth Analysis
- Return Distribution Visualization
- Rolling VaR Risk Monitoring
- Interactive Plotly Visualizations

---

## Financial Concepts Covered

- Value at Risk (VaR)
- Conditional Value at Risk (CVaR)
- Expected Shortfall
- Historical Simulation
- Monte Carlo Simulation
- Parametric VaR
- Portfolio Returns
- Risk Management
- Portfolio Analytics
- Confidence Intervals
- Tail Risk
- Loss Distribution

---

## Risk Models Implemented

### Historical VaR

Calculates portfolio risk directly from historical return observations without assuming any probability distribution.

---

### Parametric VaR

Assumes portfolio returns follow a normal distribution and estimates downside risk using portfolio mean, volatility, and the normal distribution.

---

### Monte Carlo VaR

Generates thousands of simulated portfolio returns using random sampling to estimate future downside risk.

---

### Expected Shortfall (CVaR)

Measures the average portfolio loss beyond the VaR threshold.

Unlike VaR, Expected Shortfall captures the severity of extreme losses and is widely used under the Basel III market risk framework.

---

## Workflow

```
Download Historical Market Data
            │
            ▼
Calculate Daily Portfolio Returns
            │
            ▼
Historical VaR
            │
            ├───────────────┐
            ▼               ▼
Parametric VaR      Monte Carlo VaR
            │               │
            └──────┬────────┘
                   ▼
          Expected Shortfall
                   │
                   ▼
Portfolio Growth Analysis
                   │
                   ▼
Return Distribution
                   │
                   ▼
Rolling VaR Dashboard
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Plotly
- yFinance
- Google Colab

---

## Portfolio

The notebook builds an equally weighted portfolio using:

- Apple (AAPL)
- Microsoft (MSFT)
- NVIDIA (NVDA)
- Amazon (AMZN)
- Alphabet (GOOGL)

---

## Visualizations

### Portfolio Growth

Tracks cumulative portfolio performance over time.

---

### Return Distribution

Histogram of historical portfolio returns with the Historical VaR threshold highlighted.

---

### Rolling Value at Risk

Computes a rolling 252-day Historical VaR to monitor how portfolio risk changes over time.

---

## Example Output

| Metric | Description |
|---------|-------------|
| Historical VaR | Calculated |
| Parametric VaR | Calculated |
| Monte Carlo VaR | Calculated |
| Expected Shortfall | Calculated |
| Confidence Level | 95% |
| Portfolio Assets | 5 |

---

## Installation

Clone the repository

```bash
git clone https://github.com/yashkala365/VAR-Expected-Shortfall.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open directly in Google Colab.

---

## Skills Demonstrated

- Quantitative Finance
- Financial Risk Management
- Portfolio Analytics
- Value at Risk (VaR)
- Expected Shortfall (CVaR)
- Monte Carlo Simulation
- Statistical Modeling
- Portfolio Performance Analysis
- Data Visualization
- Python Programming
- Financial Engineering

---

## Applications

This project demonstrates practical skills used by:

- Quantitative Risk Analysts
- Market Risk Analysts
- Portfolio Managers
- Asset Management Firms
- Investment Banks
- Hedge Funds
- Proprietary Trading Firms
- Financial Engineering Teams

---

## Key Takeaways

- Implemented three independent VaR methodologies for portfolio risk estimation.
- Calculated Expected Shortfall (CVaR) to quantify tail risk beyond the VaR threshold.
- Built a diversified multi-asset portfolio using live financial market data.
- Created rolling risk analytics and interactive visualizations for continuous portfolio monitoring.
- Demonstrated practical applications of quantitative risk management techniques used across institutional finance.

---

## Author

**Yash Kala**
