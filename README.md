# Insurance Missing Values Analysis (Synthetic Data)

## Overview
This project demonstrates a **missing value (data quality) analysis workflow** on an insurance-style dataset using **synthetic (non-confidential) data**.  
It covers missingness profiling, visual diagnostics, and practical insights for cleaning decisions.

## What’s Inside
- Missing value summary table (**count + % per column**)
- Missing data heatmap to spot patterns
- Quick checks on rows with missing critical fields (e.g., premium / dates)
- Notes on how to decide: drop vs impute vs “missing as category”

## Repository Structure
- `insurance_missing_values_analysis.ipynb` — missing value audit notebook
- `data/insurance_sample.csv` — synthetic sample dataset (safe to share)
- `requirements.txt` — dependencies

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook "insurance_missing_values_analysis.ipynb"

