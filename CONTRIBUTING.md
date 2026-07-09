# Contributing / Submission Workflow

## One-time setup

1. Click **Fork** (top right of the GitHub repo page) to create your own copy.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/Data-Science-Task.git
   cd Data-Science-Task
   ```
3. Add the original repo as `upstream` so you can pull new tasks as they're released:
   ```bash
   git remote add upstream https://github.com/<mentor-username>/Data-Science-Task.git
   ```

## Each week

1. Sync with upstream before starting a new task:
   ```bash
   git checkout main
   git pull upstream main
   git push origin main
   ```
2. Create a branch for the task:
   ```bash
   git checkout -b task-1-<your-name>
   ```
3. Do your work **inside that task's folder only** (e.g. `task-1-python-pandas-eda/`).
   Do not edit other students' folders or other tasks.
4. Commit as you go with clear messages:
   ```bash
   git add task-1-python-pandas-eda/
   git commit -m "Complete task 1: EDA on retail dataset"
   ```
5. Push your branch and open a PR against the **original repo's `main` branch**:
   ```bash
   git push origin task-1-<your-name>
   ```
   Then open a Pull Request on GitHub. Fill out the PR template.

## Getting feedback

- Review comments will appear on the PR. Push additional commits to the same
  branch to address them — don't open a new PR.
- A task is done once the PR is approved and merged by your mentor.

## Naming convention

Branch names: `task-<number>-<your-name>` (e.g. `task-3-emeka`).
Keep your notebook/script names inside your task folder as instructed in that
task's README.
