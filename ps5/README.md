# Problem Set 5

This folder contains all deliverables for Problem Set 5.

---

## Topics Covered

**Part I**: Clustering, Principal Component Analysis (PCA), and K-means  
- Implemented K-means clustering manually on a 2D dataset  
- Iteratively reassigned clusters and recalculated centroids until convergence  
- Visualized cluster assignments and centroid movement  
- Simulated a high-dimensional dataset with known class structure  
- Applied PCA for dimensionality reduction and visualized principal components  
- Evaluated K-means clustering performance using different values of K  
- Demonstrated how scaling and PCA affect clustering results and interpretation  

**Part II**: FX Returns, PCA, and Predictive Modeling of the S&P 500  
- Computed monthly FX returns from exchange rate data  
- Visualized the correlation matrix of currency returns using a corrplot  
- Applied PCA to FX return series to identify common underlying factors  
- Interpreted scree plots and biplots to assess variance explained and variable influence  
- Built linear regression and LASSO models to predict S&P 500 returns using FX PCs  
- Compared LASSO on raw FX returns vs. PCA-transformed FX data  
- Explored Partial Least Squares (PLS) regression to extract predictive latent features  
- Interpreted variable loadings in PLS to identify currencies with strong directional influence on equity markets  

---

## Files

- `instructions.pdf` — Assignment instructions and question prompts  
- `part1_part2.Rmd` — RMarkdown file with code for all exercises  
- `part1_part2.pdf` — Knitted PDF output of the completed assignment  

---

## Tools Used

- `R`  
- `ggplot2` – for data visualization  
- `dplyr` – for data manipulation  
- `corrplot` – for correlation matrix visualization  
- `glmnet` – for LASSO regression  
- `pls` – for Partial Least Squares modeling  
- `stats` – for K-means clustering and PCA  
- `base` and `graphics` – for manual cluster implementation and plotting 
