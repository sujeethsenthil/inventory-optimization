# Inventory Optimization via Monte Carlo

Quantifying uncertainty to optimize reorder policy (Q*, Qo) under stochastic demand and lead time.

## Structure
- `src/` simulation + optimization
- `notebooks/` EDA and experiments
- `app/` Streamlit dashboard
- `data/` (raw ignored)
- `reports/` notes and results

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/00_data_overview.ipynb