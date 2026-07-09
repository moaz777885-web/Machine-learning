# Task 4 — Feature Engineering & Baseline Model

**Duration:** 1 week (~7–9 hrs)

## Objective

Build your first real ML pipeline: proper train/test split, feature
engineering, a baseline model, and honest evaluation. The goal is a correct,
simple pipeline — not the fanciest model.

## Dataset

[House Prices - Advanced Regression (Kaggle)](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
(regression) — or if you'd rather do classification, use the
[Titanic dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
from Task 1 to predict `Survived`.

## Deliverables

Create `model_baseline.ipynb` in this folder containing:

1. **Train/test split** — done *before* any feature engineering that learns
   from the data (e.g. fit scalers/encoders on train only).
2. **Feature engineering**: at least 3 engineered features (e.g. binning,
   ratios, extracting from dates/text, one-hot/target encoding of
   categoricals). Justify each in a markdown cell.
3. **Baseline model**: a dumb baseline first (mean/median predictor for
   regression, most-frequent-class for classification), then a simple real
   model (linear/logistic regression or a shallow decision tree).
4. **Evaluation**: appropriate metric(s) for the task (RMSE/MAE for
   regression; accuracy + precision/recall/F1 for classification), comparing
   baseline vs. your model.

## Grading Criteria

- No data leakage — nothing derived from the full dataset before splitting
- Feature engineering choices are justified, not arbitrary
- Correct metric(s) chosen and interpreted correctly
- Model clearly beats the dumb baseline, or you explain why it doesn't

## Stretch (optional)

Add a `sklearn.Pipeline` that bundles preprocessing + model into one object.
