# Pandas for Data Analysts — Beginner to Intermediate

A structured, hands-on pandas learning path built by an AP/P2P analyst transitioning into
data analytics — with a focus on the kind of messy, real-world invoice and vendor data
analysts actually work with, and on techniques that hold up on **large datasets**, not just
toy examples.

This repo complements two related portfolio projects:
- [`AP-Invoice-Analytics-SQL`](https://github.com/M-0024/AP-Invoice-Analytics-SQL) — the same
  invoice-hold analysis problem solved in SQL Server (SSMS)
- `AP-Invoice-Hold-PowerBI` — the same data visualized as an interactive Power BI dashboard

Together: **SQL for querying → pandas for scripting/automation → Power BI for reporting.**

## Structure

| Folder | Covers |
|---|---|
| `01_beginner/` | Reading data, exploring, selecting/filtering, cleaning, sorting & grouping |
| `02_intermediate/` | Merging/joining, pivot tables, datetime handling, vectorization, reshaping, string ops |
| `03_large_datasets/` | Dtype optimization, chunked reading, efficient groupby, when to reach for Polars/Dask |
| `04_projects/` | End-to-end mini-projects using the synthetic AP invoice dataset |
| `data/` | Synthetic AP invoice dataset used throughout (no real/confidential data) |

## Dataset

`data/synthetic_ap_invoices.csv` is a **synthetic** dataset (generated with numpy/pandas,
seeded for reproducibility) modeled on real AP invoice-hold data structure: invoice number,
vendor code, region, invoice date, amount, PO number, hold reason, payment status. It
intentionally includes realistic messiness — missing amounts, duplicate invoice numbers,
inconsistent hold reasons — so cleaning exercises reflect real work.

No confidential or employer data is included anywhere in this repo.

## Getting started

```bash
git clone https://github.com/M-0024/Pandas-for-Data-Analysts.git
cd Pandas-for-Data-Analysts
pip install -r requirements.txt
jupyter notebook
```

Then open `01_beginner/01_reading_data.ipynb` and work through the notebooks in order.
Each notebook ends with a short exercise — do those before moving to the next one.

## Progress

- [x] 01 · Beginner
- [ ] 02 · Intermediate
- [ ] 03 · Large datasets
- [ ] 04 · End-to-end projects

## Author

Masuma Khatun (M-0024) — Assistant Manager, AP/P2P Operations (Genpact, Baker Hughes account,
Germany region). Background in finance transformation, P2P operations, and project governance,
building pandas/SQL/Power BI fluency for a move into data analytics and finance transformation
advisory.
