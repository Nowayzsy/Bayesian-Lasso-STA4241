# A brief introduction to Bayesian LASSO

This repository contains the STA4241 final project for a Bayesian Lasso study comparing frequentist Lasso with Bayesian Lasso on simulated data.

## Contents
- `rmd/Shenyu_Zhou_BayesianLasso.Rmd` — R Markdown with all analyses and figures.
- `docs/Shenyu_Zhou_BayesianLasso_Report.pdf` — Final report (PDF).
- `docs/Shenyu_Zhou_BayesianLasso_Slides.pdf` — Short slide deck (PDF).

## Methods
- Frequentist baseline: L1-penalized regression (LASSO).
- Bayesian Lasso: Laplace (double-exponential) prior on coefficients; MCMC sampling (Gibbs sampler).
- Evaluation: Evaluation: predictive error (RMSE/MAE/MSE as applicable), coefficient shrinkage/recovery, and comparison of frequentist vs Bayesian estimates.

