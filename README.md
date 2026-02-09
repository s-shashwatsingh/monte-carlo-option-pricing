# Monte Carlo Option Pricing — Reliance Industries

This project prices a European Call Option on Reliance Industries using two approaches:

• Monte Carlo Simulation  
• Black–Scholes Analytical Model  

The goal is to compare simulated pricing with theoretical valuation.

---

## Financial Model

Stock price assumed to follow Geometric Brownian Motion:

S(t+1) = S(t) * exp((r − 0.5σ²)dt + σ√dt Z)

Option payoff:

C = e^(-rT) E[max(ST − K, 0)]

---

## Methodology

1. Download historical stock data using Yahoo Finance
2. Estimate annual volatility from daily returns
3. Simulate price paths
4. Compute discounted expected payoff
5. Compare with Black-Scholes formula

---

## Tech Stack
Python • NumPy • Pandas • Matplotlib • SciPy • yfinance

---

## How to Run

pip install -r requirements.txt  
jupyter notebook
