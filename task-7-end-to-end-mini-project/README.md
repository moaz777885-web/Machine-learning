# Task 7 — End-to-End Mini Project (Self-Sourced Data)

**Duration:** 1 week (~8–10 hrs)

## Objective

This is a dry run for the capstone. Find your own dataset, define your own
problem, and run the full pipeline solo: cleaning → EDA → modeling →
reporting. This is where real-world messiness (and ambiguity about what to do)
shows up.

## Dataset

**You source it yourself.** Requirements:
- At least 1,000 rows and 8+ columns
- Not one already used in a previous task
- From a public source: Kaggle, UCI ML Repository, data.gov, a public API, or
  a well-documented scrape (cite your source in `REPORT.md`)

Pick a dataset that lets you ask an interesting question — regression or
classification, your choice.

## Deliverables

In this folder:

1. `pipeline.ipynb` — full pipeline: load → clean → EDA → feature engineering
   → model → evaluation, following the practices from Tasks 1–6 (proper
   splits, justified cleaning, correct metrics, no leakage).
2. `REPORT.md` (400–600 words) — the problem you defined, why it matters,
   your approach, key results, and **one honest limitation** of your analysis
   or model (every real analysis has one — identify yours).
3. `data/` folder with either the raw data (if small/licensed for
   redistribution) or a `download_instructions.md` explaining how to get it.

## Grading Criteria

- Problem is well-defined and the dataset genuinely supports answering it
- Full pipeline present and correct (this is a cumulative check on Tasks 1–6 skills)
- Report identifies a real limitation, not a throwaway disclaimer
- Reproducible: another student could clone your folder and rerun it

## Stretch (optional)

Add a simple `predict.py` script that loads your trained model and scores a
new row of input from the command line.
