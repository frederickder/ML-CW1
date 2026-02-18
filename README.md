# ML-CW1

Machine Learning Coursework 1 — Regression prediction challenge.

## Structure

- `data/` — Training and test datasets
- `notebooks/` — EDA, model selection, and final model training
- `outputs/` — Directory for final generated CSV file and model comparison figures

## Setup

```bash
pip install -r requirements.txt
```

## Reproducible Run Order

1. Run `notebooks/01_eda.ipynb`
2. Run `notebooks/02_model_selection.ipynb`
3. Run `notebooks/03_final_model.ipynb`

Notes:
- Notebooks  resolve the project root automatically when run from either repo root or `notebooks/`.
- `xgboost` and `lightgbm` are required (validated at notebook start).
