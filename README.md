# Hyperliquid Trader Behavior & Market Sentiment Analysis

## Objective

This study investigates how Bitcoin market sentiment (Fear/Greed index) relates to trader behavior and profitability on Hyperliquid.

We test whether trader performance, risk-taking, and behavioral patterns vary across sentiment regimes.

---

## Datasets

1. Bitcoin Fear/Greed Index
2. Hyperliquid Historical Trader Data

---

## Methodology

1. Cleaned and validated raw trade-level data
2. Aggregated trades to daily trader-level metrics:
   - Daily PnL
   - Win rate
   - Trade frequency
   - Position size
   - Long bias
3. Aligned sentiment data at daily resolution
4. Conducted:
   - Regime mean comparison
   - Statistical testing (Welch’s t-test)
   - Behavioral comparison analysis
   - Trader segmentation
   - KMeans clustering for behavioral archetypes

---

## Key Findings

1. Fear regimes exhibit higher PnL dispersion.
2. Win rate does not significantly differ across regimes.
3. Profitability is driven by volatility exposure, not directional accuracy.
4. High-volatility traders generate disproportionate returns.
5. Convex payoff structure dominates platform profitability.

---

## Strategy Implications

1. Volatility Expansion Strategy:
   Increase risk exposure during Fear regimes to exploit tail events.

2. Regime-Based Allocation:
   Allocate capital dynamically:
   - Core capital to consistent traders
   - Tactical capital to convex traders during Fear regimes

---

## How to Run

1. Install dependencies:
  pip install -r requirements.txt
2. Open notebook:
  PrimeTrade.ipynb
3. Update file paths.
4. Run all cells sequentially.

---

## Tools Used

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn

---

## Author
Krishna Vora
