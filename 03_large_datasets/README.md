# 03 · Large Datasets

Techniques for when pandas needs to handle data that doesn't comfortably fit in memory
or runs slowly at scale:

- `12_dtype_optimization.ipynb` — downcasting numeric types, using `category` dtype, `memory_usage()`
- `13_chunking_large_files.ipynb` — reading huge CSVs in chunks with `chunksize=`
- `14_efficient_groupby.ipynb` — avoiding slow `.apply()`, using `.transform()` / `.agg()` instead
- `15_pandas_vs_alternatives.ipynb` — brief intro to when to reach for Polars or Dask instead
