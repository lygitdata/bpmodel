# Blood Pressure Classification / Prediction

<img src="https://bpmodel.ly.gd.edu.kg/img/Free-blood-pressure.png" width="100px" alt="img">

English: https://bpmodel.ly.gd.edu.kg/

中文：https://bpmodel.ly.gd.edu.kg/cn/

Русский: https://bpmodel.ly.gd.edu.kg/ru/

This repository contains resources related to the development and evaluation of predictive models for blood pressure classification. The project explores the use of Multinomial Regression with Lasso Regularization and XGBoost models, along with a systematic feature selection process.

## Table of Contents

- [Introduction](#introduction)
- [Models](#models)
  - [Multinomial Regression Model with Lasso Regularization](#multinomial-regression-model-with-lasso-regularization)
  - [XGBoost Model](#xgboost-model)
  - [XGBoost Model with Selected Predictors](#xgboost-model-with-selected-predictors)
- [Conclusions and Future Directions](#conclusions-and-future-directions)
- [Computational Details](#computational-details)
- [Reproducibility](#reproducibility)
- [License](#license)

## Introduction

This project focuses on predicting blood pressure levels using machine learning models. The goal is to provide insights into the effectiveness of different models and their application in health-related predictions.

## Models

### Multinomial Regression Model with Lasso Regularization

- Trained with various lasso regularization strengths.
- Optimal λ identified through cross-validation.
- 43 selected predictors and their coefficients provided.

### XGBoost Model

- Utilizes Extreme Gradient Boosting with specific hyperparameters.
- Outperforms the Multinomial Regression Model with Lasso Regularization.
- Evaluation metrics include test accuracy and AUC.

### XGBoost Model with Selected Predictors

- Feature selection using Gain scores of predictors.
- Top predictors identified, contributing to improved model performance.
- Test accuracy and AUC assessed for different numbers of selected predictors.

## Conclusions and Future Directions

- Emphasis on the importance of accuracy in health-related predictive models.
- Acknowledgment of limitations and suggestions for improvement, including feature engineering and data enrichment.
- Proposal for integrating predictive models into health apps for personalized blood pressure suggestions.

## Computational Details

- R libraries used: caret, dplyr, ggplot2, glmnet, xgboost, and more.
- Conducted in RStudio IDE version "Mountain Hydrangea" for Windows.

## Reproducibility

The RMarkdown file and its relevant files can be downloaded at the following link: https://bpmodel.ly.gd.edu.kg/manuscript/download.zip

To reproduce the findings and generate the same results presented in this paper, follow these steps:

1. Download the Necessary Files:

- Navigate to the provided link in your browser.

- Unzip the downloaded file to a directory of your choice.

3. Open RMarkdown in RStudio:
   
- Ensure you have R and RStudio installed on your machine.

- Open RStudio and navigate to the directory where you unzipped the files.

- Open the RMarkdown file (manuscript.Rmd) in RStudio.

5. Install Required Packages:

- If not already installed, install the required R packages from the CRAN.

7. Knit the Document:
   
- Knit the RMarkdown file to reproduce the analysis. This will execute the code chunks, perform the
analysis, and generate the final document.

## License

This project is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
