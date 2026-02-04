# shakshiyadav27-trader-behavior-sentiment-analysis
# Trader Performance vs Market Sentiment (Fear & Greed)

## Overview
This project analyzes how Bitcoin market sentiment (Fear vs Greed)
impacts trader behavior and performance on the Hyperliquid platform.

The analysis was conducted as part of the **Data Science Intern – Round 0**
assignment for Primetrade.ai.

---

## Datasets
1. **Bitcoin Market Sentiment**
   - Daily Fear/Greed classification

2. **Hyperliquid Trader Data**
   - Trade-level data including PnL, trade size, side, and timestamps

Both datasets are loaded directly from the official Google Drive links
provided in the assignment to ensure reproducibility.

---

## Methodology
- Cleaned and validated both datasets
- Converted timestamps and aligned data at a daily level
- Created key trader metrics:
  - Daily PnL
  - Trades per day
  - Average trade size
  - Risk proxy (start position)
  - Long/short bias
- Merged sentiment data with trader metrics
- Compared performance and behavior across Fear vs Greed days
- Segmented traders by leverage, frequency, and consistency

---

## Key Insights
- Traders exhibit higher risk-taking behavior during Fear periods,
  resulting in higher volatility and lower average returns.
- Greed periods are associated with more stable and profitable trading.
- High-risk traders are significantly more vulnerable during Fear days.
- Consistent traders outperform others when sentiment is favorable.

---

## Strategy Recommendations
- Reduce leverage and trade frequency during Fear periods,
  especially for low-consistency traders.
- Scale positions selectively during Greed periods
  for consistently profitable traders.

---

## How to Run
1. Clone the repository: https://github.com/shakshiyadav27/shakshiyadav27-trader-behavior-sentiment-analysis
2. Install dependencies:
3. Open and run the notebook:

---

## Author
Shakshi

