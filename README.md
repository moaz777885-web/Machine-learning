# Data Science Mentorship Program

An 8-week, project-based data science curriculum. Each task builds on the last —
by Week 8 you'll have a portfolio of 8 GitHub-reviewed projects, including a
self-sourced capstone.

## How this works

1. **Fork** this repository to your own GitHub account.
2. Each week, do your work inside that week's task folder (e.g. `task-1-python-pandas-eda/`)
   in your fork — do not modify other tasks' folders.
3. Open a **Pull Request** from your fork back to this repo when a task is done.
   Use the PR template — it will ask you to fill in a short write-up.
4. You'll get review comments on the PR. Address them and push updates to the
   same branch (don't open a new PR for revisions).
5. A task is "complete" once its PR is approved and merged.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the detailed fork/PR workflow if you're
new to Git.

## Setup

```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Task Schedule

| # | Task | Focus | Duration |
|---|------|-------|----------|
| 1 | [Python, Pandas & EDA Foundations](task-1-python-pandas-eda/) | Data types, pandas basics, first exploratory analysis | Week 1 (5–8 hrs) |
| 2 | [Data Cleaning & Wrangling](task-2-data-cleaning/) | Missing values, duplicates, messy real-world data | Week 2 (6–8 hrs) |
| 3 | [EDA & Data Storytelling](task-3-eda-storytelling/) | Deeper analysis, visualization, written insights | Week 3 (6–8 hrs) |
| 4 | [Feature Engineering & Baseline Model](task-4-feature-engineering-baseline-model/) | Train/test split, first ML model, baseline metrics | Week 4 (7–9 hrs) |
| 5 | [Model Selection & Tuning](task-5-model-tuning/) | Cross-validation, hyperparameter tuning, model comparison | Week 5 (7–9 hrs) |
| 6 | [Imbalanced Data & Robust Evaluation](task-6-imbalanced-evaluation/) | Class imbalance, proper metrics, avoiding leakage | Week 6 (7–9 hrs) |
| 7 | [End-to-End Mini Project](task-7-end-to-end-mini-project/) | Self-sourced dataset, full pipeline, technical report | Week 7 (8–10 hrs) |
| 8 | [Capstone Project](task-8-capstone/) | Self-sourced dataset, polished portfolio deliverable | Week 8 (8–10 hrs) |

## Grading Criteria (applies to every task)

Each task README has task-specific criteria, but all PRs are reviewed against:

- **Correctness** — code runs, results are reproducible, conclusions are supported by the data
- **Code quality** — readable, no dead cells, no hardcoded absolute paths
- **Communication** — markdown cells / README explain *why*, not just *what*
- **Rigor** — no data leakage, appropriate train/test handling, sound reasoning about metrics

## Tools

Python 3.10+, pandas, numpy, matplotlib/seaborn, scikit-learn, Jupyter.
See [requirements.txt](requirements.txt).
