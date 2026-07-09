# Task 3 — EDA & Data Storytelling

**Duration:** 1 week (~6–8 hrs)

## Objective

Move from "clean data" to "insight." Practice asking good questions of a
dataset, using statistics (not just plots) to back up claims, and writing up
findings for a non-technical reader.

## Dataset

Use your **cleaned dataset from Task 2**, or if you want a fresh one:
[Superstore Sales dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Deliverables

Create `eda_report.ipynb` **and** `REPORT.md` in this folder.

**Notebook** (`eda_report.ipynb`):
1. Formulate **3 specific business/analysis questions** about the data (not
   generic — e.g. "Which product category has the highest return rate, and
   does it vary by region?").
2. Answer each with appropriate analysis: grouping, correlation, a simple
   statistical test (t-test, chi-square, or correlation significance —
   whichever fits), and a supporting plot.
3. Flag any correlation you found and explicitly discuss whether it implies
   causation (it usually doesn't) — one paragraph.

**Report** (`REPORT.md`):
- 300–500 words, written for a non-technical stakeholder.
- State your 3 questions, your findings, and one actionable recommendation
  per finding.
- Include your best 1–2 charts (exported as images, referenced in the markdown).

## Grading Criteria

- Questions are specific and answerable with the data — not vague
- At least one statistical test is used correctly (right test for the data type)
- Correlation vs. causation is explicitly addressed
- The written report is genuinely readable by someone without a stats background

## Stretch (optional)

Add a 4th question that requires combining/joining two different groupings or
a derived feature (e.g. profit margin = profit / sales).
