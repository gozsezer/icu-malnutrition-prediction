# Independently reconstructed baseline (not original code)

Requires a legally accessible de-identified analytic dataset. Do not include target-derived predictors.

This is a newly authored, leakage-aware **logistic regression reference implementation** for a user-supplied, approved CSV. It is not a reproduction of the manuscript's full model comparison, tuning, calibration or SHAP workflow, and it has not been run against the study data.

Expected target: `nrs2002_risk`.

Run: `python analysis/baseline.py --data /secure/path/approved.csv`

Install: `pip install -r analysis/requirements.txt`

Before use: audit the dataset schema, target definition, temporal leakage, feature eligibility and permissions. Report metrics only after independent validation. Do not commit the data.
