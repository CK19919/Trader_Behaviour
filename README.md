# Trader Behavior vs Market Sentiment (Hyperliquid)

## Objective
This project analyzes how market sentiment (Fear / Greed) relates to trader behavior and performance on Hyperliquid.
The goal is to identify patterns that can help inform smarter and more risk-aware trading strategies.

---

## Repository Structure
data/ → input datasets used for analysis

outputs/ → generated charts and summary tables

analysis.ipynb → main analysis notebook

SUMMARY.md → short write-up (methodology, insights, strategies)

README.md → project overview and setup instructions


---

## Datasets
- **historical_data.csv**  
  Trade-level data including account, trade size, direction, PnL, leverage-related fields, and timestamps.

- **fear_greed_index.csv**  
  Daily market sentiment data with numerical index value and sentiment classification.

Datasets are included to ensure full reproducibility.

---

## Setup & How to Run

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Required Libraries
- pandas  
- numpy  
- matplotlib  
- jupyter  

Install dependencies (if needed):
```bash
pip install pandas numpy matplotlib jupyter
