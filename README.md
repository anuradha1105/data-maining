# Assignment 1 — Kaggle House Prices (Data Mining)

Author: <Your Name>  
Date: <YYYY-MM-DD>

This folder contains my work for Assignment 1, using Kaggle's House Prices: Advanced Regression Techniques.

## Structure
assignment-1/
├─ README.md
├─ notebooks/
├─ outputs/
├─ figures/
├─ requirements.txt
└─ .gitignore

## Results
| Model           | Metric     | Score     | Notes                                 |
|-----------------|------------|-----------|---------------------------------------|
| Baseline RF     | CV RMSE    | 29080.87  | 5-fold                                |
| Baseline RF     | Public LB  | 0.14696   | outputs/submission.csv                |
| Log-target RF   | CV RMSLE   | 0.14200   | 5-fold                                |
| XGB (baseline)  | CV RMSLE   | 0.12499   | 5-fold                                |
| XGB (baseline)  | Public LB  | 0.12931   | outputs/submission_xgb.csv (best)     |

## Reproduce (Colab)
- Join the competition on Kaggle.
- Download data to data/ with Kaggle CLI (not committed).
- Open the notebook in notebooks/ and run top→bottom; it writes outputs/submission.csv.

## Do not commit
- data/ (Kaggle dataset)
- Secrets (kaggle.json, /root/.kaggle/)
