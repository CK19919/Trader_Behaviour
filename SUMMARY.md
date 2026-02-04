# Summary: Trader Behavior vs Market Sentiment

## Methodology
Trade-level data from Hyperliquid was combined with daily Fear–Greed Index data to analyze how market sentiment affects trader behavior and performance.
Trade timestamps were converted to daily granularity to align with sentiment data.

Daily trader-level metrics were calculated, including:
- Daily PnL
- Win rate
- Average trade size
- Number of trades per day
- Average leverage (approximated)
- Long/short ratio

Traders were segmented based on leverage usage, trading frequency, and performance consistency.

---

## Key Insights
- Trader performance differs across sentiment regimes, with lower average PnL and win rates during Fear and Extreme Fear periods.
- Traders reduce leverage and trade frequency during Fear periods, indicating risk-averse behavior.
- Greed periods show higher leverage usage, increased trading activity, and stronger long bias.
- High-leverage traders experience larger drawdowns during Fear periods compared to low-leverage traders.
- Increased trading frequency benefits consistent winners more than inconsistent traders.

---

## Strategy Recommendations
1. **Risk Management Rule**  
   During Fear or Extreme Fear periods, high-leverage traders should reduce exposure to limit drawdowns.

2. **Selective Aggression Rule**  
   Increased trading activity during Greed periods should be limited to traders with historically consistent performance.

---

## Limitations
- Market sentiment is global and may not reflect asset-specific events.
- Leverage is approximated using available position data.
- Intraday sentiment effects are not captured.

---

## Conclusion
Market sentiment has a clear influence on trader behavior and outcomes. Incorporating sentiment-aware risk controls and trader segmentation can help improve trading performance.
