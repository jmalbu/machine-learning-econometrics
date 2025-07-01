
# Problem Set 4 — Resampling and Advanced Regression

This folder contains all deliverables for Problem Set 4.

---

## Topics Covered

**Part I**: Resampling Methods & Logistic Regression  
- Validation set approach vs. LOOCV vs. K-fold CV  
- Logistic regression with the `Default` dataset  
- Estimating test error rates through repeated validation  
- Bootstrap standard error estimation for logistic regression coefficients

**Part II**: Polynomial and Spline Regression  
- Fitting polynomial models to explore non-linear relationships  
- Model selection using cross-validation and residual sum of squares (RSS)  
- Regression splines using `bs()` from the `splines` package

**Part III**: Model Comparison for Salary Prediction  
- Comparing boosting, OLS, ridge, and lasso using the `Hitters` dataset  
- Tuning shrinkage parameters in boosting  
- Evaluating models using test MSE  
- Feature importance analysis in boosted and bagged models

---

## Files

- `instructions.pdf` — Problem set instructions  
- `ps4.Rmd` — RMarkdown file containing all code and analysis  
- `ps4.pdf` — Knitted PDF output of the final report

---

## Tools Used

- `R`, `ggplot2`, `dplyr`, `glmnet`, `boot`, `splines`, `randomForest`, `gbm`
