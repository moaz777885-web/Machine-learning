# Task 6 — Imbalanced Data & Robust Evaluation

**Duration:** 1 week (~7–9 hrs)

## Objective

Most real classification problems are imbalanced (fraud, churn, disease
detection). Learn why accuracy lies in these cases, and the standard
techniques for handling imbalance and evaluating honestly.

## Dataset

[Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
— highly imbalanced (~0.17% positive class). If that's too large to work with
comfortably, use
[Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
instead (moderately imbalanced).

## Deliverables

Create `imbalanced_classification.ipynb` in this folder containing:

1. **Demonstrate the problem**: train a plain classifier, report accuracy,
   then show why accuracy is misleading here (e.g. compare to a
   predict-majority-class baseline).
2. **Better metrics**: report precision, recall, F1, and ROC-AUC /
   precision-recall AUC. Explain in a markdown cell which metric matters
   most for this specific problem and why (e.g. recall matters more than
   precision for fraud detection — justify from the business cost of false
   negatives vs. false positives).
3. **Handle the imbalance**: try at least 2 approaches (e.g. class weighting,
   oversampling with SMOTE, undersampling) and compare results.
4. **Confusion matrix** for your best approach, with a written interpretation
   of the actual error types and their real-world cost.

## Grading Criteria

- Clearly demonstrates why accuracy is the wrong metric here
- Resampling (if used) is applied only to the training fold, never to test data
- Metric choice is justified by the business context, not just "higher is better"
- Confusion matrix interpretation ties back to real-world consequences

## Stretch (optional)

Plot precision-recall curves for your different approaches on one chart and
pick an operating threshold, justifying your choice.
