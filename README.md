# insurance-status-expenditures-meps2004

This project explores the relationship between insurance status and total medical care expenditures using the 2004 Medical Expenditure Panel Survey (MEPS). The analysis was completed as part of a technical assessment and demonstrates data cleaning, regression modeling, visualization, and presentation of results in a policy-relevant format.

## Objectives
- Clean and prepare MEPS person-level data
- Create demographic summary tables and visualizations
- Model the association between insurance status and total medical expenditures
- Report adjusted means using `emmeans` for interpretability
- Present results in polished, reader-friendly tables and figures

## Contents
- `meps_analysis.Rmd`: Full RMarkdown with code, models, and written analysis
- `meps_analysis.html`: Output report showing code and results
- `/figures`: (Optional) Exported plots used in the report
- `/tables`: (Optional) Saved versions of tables for manuscript-style reporting

## Methods
A multivariable ordinary least squares (OLS) regression was used with log-transformed total medical expenditures as the outcome. The model adjusted for age, gender, race/ethnicity, education, geographic region, and family size. Estimated marginal means were calculated and back-transformed for interpretation.

## Packages Used
- `tidyverse`
- `gt`
- `emmeans`
- `gtsummary`
- `broom`

## Notes
This project uses publicly available data from the MEPS 2004 Full Year Consolidated Data File

---
