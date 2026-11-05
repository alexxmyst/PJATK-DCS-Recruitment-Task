## Project Overview
The project aims to identify product offers that contain a controlled marketplace catalogue error. We built a model that checks whether the text and structured attributes describe a consistent offer.

The core challenge was to distinguish between real anomalies and valid edge cases (e.g., a genuinely low price might be a promotion, and a heavy shipment might be a valid product variant). 

## Objective
**Predict the probability of `target=1` (the listing contains a simulated data error) versus `target=0` (no simulated error introduced). 

The main measure is ROC-AUC, which evaluates whether corrupted offers tends to receive higher scores than offers without controlled corruption. 
---

## Project Deliverables
* EDA notebook notebooks/01_eda_report.ipynb
* Training and submission notebook notebooks/02_training_pipeline.ipynb
* Model and validation artifacts outputs/catalogue_submission/
* Kaggle submission CSV outputs/kaggle_submission/submission.csv
