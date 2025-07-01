# Problem Set 3 

This folder contains all deliverables for Problem Set 3.

---

## Topics Covered

**Part I**: Model flexibility, regularization, and best subset selection  
- Bias-variance tradeoff in Ridge, Lasso, and non-linear methods  
- Training vs. test MSE behavior with increasing model complexity  
- Best subset selection using `regsubsets()` on simulated data  
- Comparison of estimated vs. true coefficients  
- Coefficient estimation error vs. model size  
- Model performance evaluation using MSE and sum of squared differences

**Part II**: Comparative modeling and classification using real datasets  
- Ridge, Lasso, and Principal Component Regression (PCR) applied to the Boston dataset  
- Lasso selected key predictors while minimizing MSE  
- Curse of dimensionality and KNN limitations as predictors grow  
- Log-odds derivation for logistic and softmax models  
- Classification performance on the *Weekly* dataset using:
  - Logistic Regression  
  - Linear and Quadratic Discriminant Analysis (LDA/QDA)  
  - K-Nearest Neighbors (KNN)  
  - Naive Bayes  
- Model tuning and comparison using accuracy as a metric

---

## Files

- `part1.Rmd` — RMarkdown file for Part I  
- `part1.pdf` — Knitted PDF output of Part I  
- `part2.Rmd` — RMarkdown file for Part II  
- `part2.pdf` — Knitted PDF output of Part II  
- `instructions.pdf` — Original assignment description

---

## Tools Used

- `R` – primary programming language  
- `ggplot2` – for data visualization  
- `dplyr` – for data wrangling  
- `readr` – for data import  
- `leaps` – for best subset selection  
- `glmnet` – for Ridge and Lasso regression  
- `pls` – for Principal Component Regression  
- `caret` – for cross-validation and model comparison  
- `class` – for KNN classification  
- `e1071` – for Naive Bayes classification  
- `MASS` – for LDA and QDA modeling  
- `ISLR2` – for datasets such as *Boston* and *Weekly*  
