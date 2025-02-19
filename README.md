# Survival and Recovery in Lung Cancer with Pembrolizumab  

This project was developed in the **third year of the Data Science degree** at the **Polytechnic University of Valencia**. It focuses on the survival and recovery analysis of **advanced-stage non-small cell lung cancer (NSCLC) patients** treated with **Pembrolizumab**.  

Using statistical and machine learning techniques (**PLS, Random Forest, and XGBoost**), we predict key variables influencing **initial disease evaluation, treatment response, and survival outcomes**. This study contributes to **personalized medicine** and aligns with **Sustainable Development Goals (SDGs)** related to health, innovation, and partnerships.  

## **Repository Structure**
This repository includes datasets, analysis scripts, and documentation related to the project:  

- **`Gantt_diagram.xlsx`** – Project timeline visualization.  
- **`Base_Pembro_1L_february_24__v2.xlsx`** – Initial dataset used in `Treatment.Rmd`.  
- **`df_survival.csv`** – Dataset used for survival analysis (`survival_model.Rmd`).  
- **`df_definitive.xlsx`** – Dataset for PCA analysis (`PCA.Rmd`) and linear regression (`Linear Regression Model using PCA.Rmd`).  
- **`PCA.Rmd`** – Principal Component Analysis (PCA) for exploratory data analysis.  
- **`df_definitive-2.xlsx`** – Dataset used for Random Forest models (`RF_First-Eval.Rmd` and `RF_best_response.Rmd`).  
- **`PLS_M2_FINAL.Rmd`** – Partial Least Squares (PLS) Model.  
- **`RF_First-Eval.Rmd`** – Random Forest model for predicting the first evaluation.  
- **`RF_best_response.Rmd`** – Random Forest model for predicting the best response.  
- **`XGBoost.Rmd`** – Implementation of XGBoost model.  
- **`survival_model.Rmd`** – Patient survival analysis.  
- **`PROYIII-GROUP07.pdf`** – Full project report.  

## **Installation**  
To run the analyses, ensure you have **R** and **RStudio** installed. Then, install the required R packages:  

```r
install.packages(c("ggplot2", "dplyr", "randomForest", "xgboost", "caret", "mice", "knitr", 
                   "readxl", "FactoMineR", "factoextra", "ropls", "tidyr", "pls", "tibble", 
                   "ranger", "survival", "KMsurv", "survMisc", "survminer", "openxlsx", "purrr"))
