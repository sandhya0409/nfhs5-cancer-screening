# Results (aggregate only)

These files contain only summary results (percentages, model scores, intervals, plots).
No individual-level NFHS-5 data is included.

| File | Made by | What it shows |
| --- | --- | --- |
| `screening_rates_by_group.csv` | `01_screening_rates.ipynb` | Weighted % of women aged 30–49 ever screened (cervical, breast, oral), by residence, wealth and education |
| `transfer_results_sb79.csv` | `02_urban_to_rural_transfer.ipynb`, Cell 3 | ROC-AUC, PR-AUC, Brier score, observed and predicted screening % for each model and setting |
| `transfer_bootstrap_95ci_sb79.csv` | `02_urban_to_rural_transfer.ipynb`, Cell 4 | Estimates with 95% cluster-bootstrap intervals for rural test women |
| `calibration_urban_to_rural_sb79.png` | `02_urban_to_rural_transfer.ipynb`, Cell 5 | Predicted vs observed screening by tenth of predicted risk, rural test women |
