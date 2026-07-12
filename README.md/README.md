# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between cryptocurrency trader performance and the Bitcoin Fear & Greed Index.

The goal is to determine how different market sentiment conditions influence trading behavior, profitability, trade size, and overall trading performance.

---

## Dataset

### 1. Bitcoin Fear & Greed Index

Columns:

- Date
- Fear & Greed Value
- Classification

### 2. Historical Trader Data

Columns include:

- Coin
- Execution Price
- Size USD
- Closed PnL
- Side
- Timestamp
- Direction
- Fee

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## Project Workflow

1. Import Libraries
2. Load Datasets
3. Explore Data
4. Handle Missing Values
5. Remove Duplicates
6. Convert Date Columns
7. Merge Datasets
8. Exploratory Data Analysis
9. Visualizations
10. Key Insights

---

## Key Insights

- Market sentiment significantly influences trader behavior.
- Greed periods generally contain more trading activity.
- Profitability varies across different market sentiment categories.
- Trade size changes with changing market sentiment.
- Some cryptocurrencies consistently generate higher profits than others.

---

## Visualizations

- Market Sentiment Distribution
- Average PnL by Sentiment
- Win Rate
- Trade Size
- Top Coins
- Correlation Heatmap
- Daily PnL Trend
- Trades per Day
- long/short Ratio
- trader cluster

---

## How to Run

```bash
pip install -r requirements.txt
```

Open:

```
analysis.ipynb
```

Run all cells from top to bottom.

---
# Bonus – Trader Clustering

K-Means clustering was applied using three trader characteristics:

- Total Closed PnL
- Average Trade Size
- Number of Trades

Three behavioral clusters were identified:

• Cluster 0 – Frequent traders with moderate profitability.

• Cluster 1 – High-profit traders with larger average trade sizes.

• Cluster 2 – Low-activity traders with comparatively lower profitability.

These clusters can help design personalized trading strategies and improve risk management.

## Author

Tanvi Mahadik