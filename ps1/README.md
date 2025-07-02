# Problem Set 1

This folder contains all deliverables for Problem Set 1.

---

## Topics Covered

**Part I**: Conceptual foundations of statistical learning  
- Flexible vs. inflexible methods  
- Bias-variance tradeoff  
- Classification vs. regression vs. clustering  
- Parametric vs. non-parametric approaches  
- Real-world applications of statistical learning  
- Interpretation of sample size (`n`) and number of predictors (`p`)  
- Trade-offs between interpretability and predictive performance  

**Part II**: Applied data exploration and statistical summaries in R  
- Imported, cleaned, and summarized the *College*, *Auto*, and *Boston* datasets  
- Explored variables through numerical summaries, scatterplots, histograms, and boxplots  
- Created new factors (e.g., `Elite` colleges) and visualized differences in tuition  
- Investigated variable ranges, means, and standard deviations (including subsetting)  
- Assessed pairwise correlations and plotted pair matrices to explore potential relationships  
- Interpreted skewed distributions and identified outliers (e.g., crime and tax rates) 
- Explored room counts and their relationship to home values and neighborhood traits  
- Identified key predictors of fuel efficiency and home prices through EDA  

**Part III**: Modeling retail ice cream pricing using the *Ben & Jerry’s* dataset  
- Visualized top-selling flavors and explored price distributions across U.S. regions  
- Observed that brownies is the most popular flavor and prices vary significantly by region  
- Built and refined logistic regression models to predict purchase probability (`y`)  
- Iteratively removed non-significant predictors (e.g., race, dishwasher, hispanic_origin) to simplify the model  
- Compared models using BIC and calculated model selection probabilities  
- Identified key predictors including flavor type, household income, household size, use of coupons, region, and home characteristics (e.g., microwave, internet, cable TV)

---

## Files

- `instructions.pdf` — Assignment instructions
- `part1.pdf` — Written solutions for conceptual questions (Part I)
- `part2.Rmd` — RMarkdown file for Part II (code)
- `part2.pdf` — Knitted PDF output of Part II
- `part3.Rmd` — RMarkdown file for Part III (code)
- `part3.pdf` — Knitted PDF output of Part III

---

## Tools Used

- `R`  
- `ggplot2` – for plotting and visualizations  
- `dplyr` – for data manipulation  
- `readr` – for reading CSV files  
- `broom` – for tidying model outputs  
- `tidyverse` – for consistent and readable data analysis workflows 
