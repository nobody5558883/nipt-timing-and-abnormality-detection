# Optimal NIPT Timing and Chromosomal Abnormality Detection

## Project Overview

This project develops a statistical and machine learning framework for optimizing the timing of non-invasive prenatal testing (NIPT) and detecting potential chromosomal abnormalities.

The study combines longitudinal modeling, regression, ensemble learning, risk optimization, and uncertainty quantification. It demonstrates how data science methods can support research questions in biostatistics, epidemiology, and public health.

## Research Questions

1. How are fetal Y-chromosome concentration, gestational age, and maternal BMI associated?
2. How can pregnant women be grouped by BMI to determine an appropriate NIPT testing window?
3. How can testing schedules be optimized while accounting for maternal characteristics and measurement uncertainty?
4. How can chromosomal abnormalities in female fetuses be identified from sequencing and clinical variables?

## Methods

The main methods used in this project include:

- Beta generalized additive mixed models (Beta-GAMM)
- Nonparametric regression
- XGBoost regression
- Random forest regression
- Risk-minimization modeling
- Sensitivity analysis
- EasyEnsemble classification
- Conformal prediction
- Three-way decision analysis

## Repository Contents

- [`analysis/problem-1-beta-gamm.Rmd`](analysis/problem-1-beta-gamm.Rmd) — Relationship between Y-chromosome concentration, gestational age, and maternal BMI
- [`analysis/problem-2-optimal-timing.ipynb`](analysis/problem-2-optimal-timing.ipynb) — BMI grouping and optimal NIPT timing
- [`analysis/problem-3-risk-minimization.ipynb`](analysis/problem-3-risk-minimization.ipynb) — Risk-based optimization under measurement uncertainty
- [`analysis/problem-4-abnormality-detection.ipynb`](analysis/problem-4-abnormality-detection.ipynb) — Chromosomal abnormality detection for female fetuses
- [`analysis/model-comparison-reml.ipynb`](analysis/model-comparison-reml.ipynb) — Comparison of candidate statistical models
- [`analysis/model-fit-r-squared.ipynb`](analysis/model-fit-r-squared.ipynb) — Calculation of model goodness-of-fit
- [`paper/nipt-modeling-paper.pdf`](paper/nipt-modeling-paper.pdf) — Complete research paper

## Technologies

- Python
- R
- pandas and NumPy
- scikit-learn
- XGBoost
- imbalanced-learn
- Matplotlib
- mgcv and gratia
- ggplot2

## Data Availability

The original dataset contains sensitive prenatal screening and pregnancy-related records. Therefore, the participant-level data are not publicly redistributed in this repository.

The code is provided to demonstrate the analytical workflow. Researchers wishing to reproduce the analysis should use an appropriately authorized dataset with equivalent variables.

## Limitations

The abnormality-detection task involves a highly imbalanced outcome, with relatively few positive cases. Therefore, the model results should be interpreted cautiously and require external validation before any practical application.

## Disclaimer

This project was developed for academic and mathematical modeling purposes. It is not intended to provide medical advice or replace professional clinical diagnosis.

