# Task 1 — Python, Pandas & EDA Foundations

**Duration:** 1 week (~5–8 hrs)

## Objective

Get comfortable with the day-to-day pandas workflow: loading data, inspecting
it, slicing/filtering, grouping, and producing your first plots. This task
assumes you already know Python basics and simple pandas — the goal is fluency
and good habits, not new concepts.

## Dataset

Use the **Titanic dataset** (provided, clean-ish):
[https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

Load it directly from the URL in your notebook — don't commit the raw CSV.

## Deliverables

Create `analysis.ipynb` in this folder containing:

1. **Load & inspect**: shape, dtypes, `.info()`, `.describe()`, first/last rows.
2. **Filtering & grouping**: at least 3 non-trivial questions answered with
   pandas (e.g. "What was the survival rate by passenger class and sex?").
3. **Three plots** (matplotlib or seaborn) with axis labels and titles —
   e.g. survival rate by class, age distribution, fare vs. survival.
4. **Summary** (markdown cell, 5–8 sentences): what stood out, and one
   question you'd want to investigate further next.

## Grading Criteria

- Correct, working pandas operations (no copy-pasted boilerplate you don't understand)
- Plots are legible and labeled
- Summary shows actual interpretation, not just restating numbers
- Notebook runs top-to-bottom without errors

## Stretch (optional)

Repeat one of your groupby questions using both `.groupby()` and a pivot
table, and note in a markdown cell which felt more natural and why.
