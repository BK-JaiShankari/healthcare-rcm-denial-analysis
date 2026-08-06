# Healthcare Claims Denial & Revenue Cycle Analysis

## Overview

## Live Dashboard
https://public.tableau.com/app/profile/jai.shankari8326/viz/HospitalRevenuecycleManagementRCM/DenialRevenueAnalysis 

## Dashboard Preview
<img width="1026" height="823" alt="image" src="https://github.com/user-attachments/assets/1be2a626-8d8d-45e6-8bc8-d27e194d050e" />


## Key Insights
- Unknown payer type denies at 20.6% — highest of any segment
- Neurology/Pulmonology deny ~2.5pts above Internal Medicine
- Net collection rate: 84.1% across finalized claims

## Data Source
https://www.kaggle.com/datasets/nudratabbas/healthcare-fraud-detection-dataset — synthetic healthcare claims data

## Note on Denial_Reason
This field doesn't exist in the source data and was simulated for illustrative purposes to demonstrate root-cause analysis technique. It should not be read as reflecting real denial-reason distribution.

## Tools
Python (pandas, numpy) — data cleaning and feature engineering
Tableau — LOD expressions, dual-axis charts, dashboard actions

## Files
- `Healthcare_Claim&Denial.ipynb` — full data cleaning and feature engineering pipeline
