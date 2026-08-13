# Global Ads Performance Analysis



## Business Questions
1. Which platform delivers the lowest CPA?
2. Which campaign type delivers the highest ROAS?
3. How does CPA change month over month in 2024?


## Dataset
Global Ads Performance (Google, Meta, TikTok) — Kaggle, CC0. 1,800 campaign-level rows covering 2024 across three platforms, five countries, and six industries. The data is synthetically generated and does not reflect real campaigns.


## Tools
Excel (pivot tables, metric validation), Tableau (dashboard).


## Data Cleaning
- 1,800 rows, 14 columns
- 0 missing values
- No true duplicates (12 rows share descriptive fields but differ
  in metrics — kept as distinct campaigns)
- Date column parsed correctly as dates
- Derived columns (CTR, CPC, CPA, ROAS) verified against raw
  columns; differences under 0.005, consistent with rounding


## Findings
TikTok Ads delivers the lowest CPA (21.67) and the highest ROAS
(7.62), while Google Ads — which absorbs 57% of total spend —
performs worst on both metrics.

Search leads on ROAS (5.31), but the spread across campaign types
is narrow (4.58–5.31). Platform choice drives returns far more
than campaign type does.

Monthly CPA fluctuates within a narrow band (31.03–36.40) with no
upward or downward trend across 2024. July is the most expensive
month, driven by the year's lowest conversion volume rather than
higher spend. There is no seasonality strong enough to justify
shifting budget by month.

## Limitations
- The dataset is synthetic, so findings describe the data, not real market behaviour.
- Conversions are not split into new vs returning customers, so CPA cannot separate acquisition cost from repeat purchases.
- Revenue is not profit; without margin data, a high ROAS does not guarantee profitability.
