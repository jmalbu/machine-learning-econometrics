# Problem Set 4

This folder contains all deliverables for Problem Set 4.

---

## Topics Covered

**Part I**: Validation set, LOOCV, and bootstrapping  
- Described the process and advantages of **K-fold cross-validation** vs. LOOCV  
- Fitted logistic regression models to predict credit default using `income`, `balance`, and `student` status  
- Evaluated **test error** across multiple random splits to assess model stability  
- Compared models with and without the `student` predictor  
- Used the **bootstrap** to estimate standard errors of logistic regression coefficients  
- Compared bootstrapped SEs with analytical SEs from `glm` output  

**Part II**: Polynomial and spline regression  
- Fitted polynomial regression of `nox` on `dis` using degrees 1 through 10  
- Plotted fits and computed **RSS** for each degree  
- Performed **10-fold CV** to select optimal polynomial degree  
- Fit regression splines with varying degrees of freedom (df = 3 to 10)  
- Assessed **in-sample RSS** and **cross-validated test error** to select optimal df  
- Visualized and interpreted spline smooths, noting diminishing returns in flexibility  

**Part III**: Comparing regression models on baseball salary data  
- Cleaned and log-transformed the *Hitters* dataset  
- Trained models on first 200 observations, tested on remainder  
- Compared **boosting**, **bagging**, **OLS**, **ridge**, and **lasso**  
- Found that **bagging** yielded the lowest test MSE (~0.230), outperforming boosting (~0.285) and penalized regressions  
- Identified **cumulative career statistics** (e.g., CAtBat, CWalks) as key salary predictors using boosting feature importance  
- Illustrated test MSE vs. shrinkage rate in boosting and confirmed overfitting at low shrinkage values  

---

## Files

- `instructions.pdf` — Problem set instructions  
- `ps4.Rmd` — RMarkdown file containing all code and analysis  
- `ps4.pdf` — Knitted PDF output of the final report

---

## Tools Used

- `R`  
- `ggplot2` – for data visualization  
- `dplyr` – for data wrangling  
- `readr` – for importing CSV files  
- `boot` – for bootstrapping and cross-validation  
- `splines` – for regression splines  
- `gbm` – for boosting  
- `glmnet` – for ridge and lasso regression  
- `randomForest` – for bagging  
- `knitr` – for report generation  
- `broom`, `tidyverse` – for clean modeling workflows  

