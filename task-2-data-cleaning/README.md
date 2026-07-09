# Task 2 — Data Cleaning & Wrangling

**Duration:** 1 week (~6–8 hrs)

## Objective

Real data is messy. This task focuses purely on cleaning: missing values,
duplicates, inconsistent formatting, wrong dtypes, and outliers — before any
analysis or modeling happens.

## Dataset

Use a deliberately messy dataset — pick **one**:

- [Melbourne Housing Snapshot (Kaggle)](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot) — missing values, mixed types
- [World Happiness Report (Kaggle)](https://www.kaggle.com/datasets/unsdsn/world-happiness) — inconsistent country naming, some missing years

(Kaggle requires a free account to download — this is intentional practice for
real workflows.)

## Deliverables

Create `cleaning.ipynb` in this folder containing:

1. **Audit**: document every data quality issue you find (missing values by
   column, duplicates, inconsistent categories/spelling, wrong dtypes,
   suspicious outliers) — before fixing anything.
2. **Cleaning decisions**: for each issue, fix it AND write a markdown cell
   explaining *why* you chose that approach (e.g. drop vs. impute, and why
   that imputation strategy).
3. **Before/after comparison**: shape, missing-value counts, and dtypes
   before and after cleaning.
4. Save the cleaned dataset as `data/cleaned.csv` in this folder (small
   enough to commit — if not, add it to `.gitignore` and note that in your
   README instead).

## Grading Criteria

- No silent data loss — every drop/impute is justified, not just applied
- Correct dtype handling (dates as dates, categories as categories, etc.)
- Duplicates and inconsistent categorical values are actually caught, not missed
- Clear before/after evidence the cleaning worked

## Stretch (optional)

Write a short function `clean(df)` that applies your full cleaning pipeline in
one call, so it could be reused on a fresh extract of the same data.
