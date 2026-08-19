# 04 · End-to-End Projects

Mini-projects applying everything above to the synthetic AP invoice dataset:

- `ap_hold_analysis/` — hold reason summary, aging bucket analysis
- `vendor_payment_trends/` — vendor-level payment behavior and trends

These mirror the analysis already done in `AP-Invoice-Analytics-SQL`, but implemented as a
reusable, scriptable pandas pipeline instead of a one-off SQL query.
