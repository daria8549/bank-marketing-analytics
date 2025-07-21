# Bank Marketing Campaign Analysis and Modeling

This project analyzes a dataset from a Portuguese bank’s telemarketing campaign to predict customer responses. It involves building and comparing various classification and regression models using R.

## Dataset

- **Source**: `bank.csv`
- **Content**: Data from direct marketing campaigns (phone calls) targeting bank customers
- **Attributes**: 16 customer attributes including age, job, marital status, education, previous contact outcomes, and campaign-related variables

## Objectives

- Perform data preprocessing and exploration
- Train multiple classification models to predict whether a client subscribes to a term deposit
- Evaluate model performance and interpret results

## Methods Used

- **Data Preprocessing**: Feature selection, factor encoding, train-test split
- **Classification Models**:
  - Decision Tree (`rpart`, `rpart.plot`)
  - Naive Bayes (`e1071`)
  - Logistic Regression (`glm`)
  - Random Forest (`ranger`)
  - Conditional Inference Tree (`party`, `partykit`)
- **Model Evaluation**:
  - Accuracy, Confusion Matrix
  - ROC Curve and AUC
  - Variable Importance

## Files

- `Project report_group2_1339 Data Analytics.Rmd` – Complete R Markdown report with all code, plots, and analysis
- `bank.csv` – Dataset used in the analysis

## Tools

- R
- RMarkdown
- Libraries: `dplyr`, `ggplot2`, `caret`, `rpart`, `ranger`, `e1071`, `party`, `MASS`, `tidymodels`
