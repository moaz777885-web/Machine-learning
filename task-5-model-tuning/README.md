# Task 5 — Model Selection & Tuning

**Duration:** 1 week (~7–9 hrs)

## Objective

Go beyond a single model: compare several algorithms fairly using
cross-validation, then tune hyperparameters properly (no test-set peeking).

## Dataset

Continue with your Task 4 dataset and split.

## Deliverables

Create `model_tuning.ipynb` in this folder containing:

1. **Cross-validation baseline**: evaluate your Task 4 model with k-fold CV
   (not just a single train/test split) and report the mean and std of your
   metric across folds.
2. **Model comparison**: train at least **3 different algorithms** (e.g.
   linear/logistic regression, random forest, gradient boosting / KNN / SVM)
   under the same CV scheme. Present results in a comparison table.
3. **Hyperparameter tuning**: pick your best-performing model and tune it
   with `GridSearchCV` or `RandomizedSearchCV`. Report best params and the
   before/after metric improvement.
4. **Final holdout evaluation**: evaluate your tuned model on the untouched
   test set exactly once, and report that as your final number.

## Grading Criteria

- Cross-validation is set up correctly (no leakage between folds, e.g.
  scaling fit inside the CV loop or via Pipeline)
- Model comparison is apples-to-apples (same CV folds/seed across models)
- Test set is touched only once, at the end
- Tuning shows a real, explained improvement (or an honest note if it didn't help)

## Stretch (optional)

Plot a validation curve or learning curve for your final model and interpret
whether it's over- or under-fitting.
