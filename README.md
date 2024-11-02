# Analysis of Model Averaging Methods in Survival Analysis

## Project Overview

This project explores the effectiveness of applying model averaging methods in survival analysis, specifically for predicting survival times of breast cancer patients. We compare single-model approaches with model averaging techniques to evaluate differences in prediction accuracy, highlighting the advantages and potential of model averaging in survival analysis.

As an ensemble learning technique, model averaging combines the predictions of multiple models, leveraging their individual strengths to compensate for the limitations of single models, thereby enhancing the overall prediction accuracy and robustness. With the rapid development of data science and machine learning, model averaging has become increasingly popular across various fields, especially in medical research, where it is an effective tool for improving predictive outcomes.

## Analysis Details

The project focuses on the following three survival analysis models and three model averaging techniques:

1. **Survival Analysis Models**
   - Cox Proportional Hazards Model
   - Weibull Model
   - Log-Normal Accelerated Failure Time (AFT) Model

2. **Model Averaging Methods**
   - Bayesian Model Averaging
   - Bagging
   - Weighted Averaging

### Weight Selection for Weighted Averaging

For the weighted averaging method, this project discusses and tests several common weight selection criteria:
- **Akaike Information Criterion (AIC)**
- **Bayesian Information Criterion (BIC)**
- **Mallows Criterion**
- **Jackknife Criterion**

## Dataset Description

The dataset used in this project is sourced from IEEEDataPort, specifically from the National Cancer Institute's SEER Program (2017 update), which provides population-based cancer statistics. The dataset includes female breast cancer patients diagnosed with invasive ductal and lobular carcinoma from 2006 to 2010. After filtering, the study includes data from 4,024 patients, excluding cases with unknown tumor size, lymph node assessment data, or survival time of less than one month.

## Project Structure

- **data/**: Dataset and related files
- **src/**: Source code for survival analysis models and model averaging methods

