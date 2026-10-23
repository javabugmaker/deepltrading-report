# deepltrading daily report

Static daily signal page for the deep ltrading system (US equities, swing 5-90 days).

- Signal model: ens_60 = daily mean of `rank(mlp_60)` and `rank(lgb_60)`
- Universe: US stocks, market cap >= $10B
- Page: built from `output/signals_<date>.csv` (top 30 + avoid list + model card)

Generated automatically; no account or position data is published here.
