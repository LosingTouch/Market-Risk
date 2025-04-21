# Market Risk Analysis – ESILV 2024–2025

[![CI: Python application](https://github.com/LosingTouch/Market-Risk/actions/workflows/python-app.yml/badge.svg)](https://github.com/your-username/market-risk-esilv/actions/workflows/python-app.yml)

**Advanced Statistical Methods for Market Risk**  
This project applies advanced techniques to estimate financial market risks, covering both market and liquidity risk using historical data, simulations, and multiresolution analysis.

---

## 📌 Overview

We investigate various measures of market risk, including:

- **Value at Risk (VaR)**: Empirical, non-parametric (logistic kernel), and Monte Carlo methods  
- **Expected Shortfall (ES)**  
- **Extreme Value Theory (EVT)**: GEV estimation via Pickands & Hill, Extremal Index via runs declustering  
- **Almgren–Chriss Model**: Optimal liquidation strategy and market impact cost  
- **Multiresolution Analysis**: Correlation across time scales, Epps effect, Hurst exponent

---

## 🎯 Objectives & Workflow

### 1. Data Preparation & Exploration
- Visualize price and return series
- Clean missing values and detect anomalies
- Prepare time series for modeling

### 2. Risk Metrics Computation
- Empirical & non-parametric VaR (logistic kernel)
- Expected Shortfall estimation
- Monte Carlo VaR on call options using Black–Scholes

### 3. Extreme Value Analysis
- Estimate GEV parameters using Pickands and Hill estimators
- Compute Extremal Index to assess clustering of extremes

### 4. Liquidity Risk Modeling
- Implement Almgren–Chriss framework for trade execution costs
- Optimize trade schedules under price impact assumptions

### 5. Multiresolution FX Correlation
- Analyze the Epps effect on FX pairs
- Compute wavelet-based correlations
- Estimate the Hurst exponent for memory effects

---

## 📁 Project Structure

```
market-risk-esilv/
├── notebooks/               # Jupyter notebooks: Questions A–E
├── docs/                    # Final reports (PDFs)
├── data/                    # Excel files: prices, FX, liquidity
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

---

## 📄 Files Included

- `docs/Projet Market risk.pdf` – Project questions and tasks.  
- `docs/Market Risk Final Report.pdf` – Final Report explaining the answers, the code is also included in the appendix. 
- `data/Natixis_ihab.xlsx`, `Dataset TD4.xlsx`, `Dataset-TD5-csv.csv` – market & FX data  
- `notebooks/QuestionA-E.ipynb` – Full Python implementation for each question.

---

## 🧪 Technologies Used

- Python 3.10  
- NumPy, pandas, matplotlib, scipy  
- Extreme value theory (GEV, declustering)  
- Monte Carlo simulation  
- Almgren–Chriss optimization  
- Haar wavelet transforms

---

## ▶️ Running the Code

```bash
# clone the repo
git clone https://github.com/your-username/market-risk-esilv.git
cd market-risk-esilv

# (optional) set up virtual environment
python3 -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate.bat on Windows

# install dependencies
pip install -r requirements.txt

# launch a notebook
jupyter lab notebooks/QuestionA.ipynb
```

---

## 📜 License

This project is licensed under the MIT License — see the LICENSE file for details.

