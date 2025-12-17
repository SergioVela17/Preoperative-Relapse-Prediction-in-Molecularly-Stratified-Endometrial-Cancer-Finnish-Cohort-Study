# Preoperative-Relapse-Prediction-in-Molecularly-Stratified-Endometrial-Cancer-Finnish-Cohort-Study

This repository contains code for interpretable ML models predicting Endometrial Cancer (EC) relapse timing (No, ≤6 months, >6 months) using preoperative multimodal data from a Finnish cohort of 784 patients [Ref: 11]. The main analyses of the manuscript can be reproduced using the code present in "FinnishProjectAnalyses.Rmd", whereas the code required to perform temporal validation and analysis of SHAP values stability among folds can be found in "TemporalValidation.Rmd" and "SHAPstabilityComparison.Rmd" respectively. No data is uploaded; users must provide their own dataset.

Reproducibility
Using R 4.5.0 and renv

Clone: git clone https://github.com/SergioVela17/Preoperative-Relapse-Prediction-in-Molecularly-Stratified-Endometrial-Cancer-Finnish-Cohort-Study.git

Restore: renv::restore()

Run: source("FinnishProjectAnalyses.Rmd")

Repository
Link: https://github.com/SergioVela17/Preoperative-Relapse-Prediction-in-Molecularly-Stratified-Endometrial-Cancer-Finnish-Cohort-Study/blob/main/README.md
Structure: /scripts/FinnishProjectAnalyses.Rmd, renv.lock, README.md
