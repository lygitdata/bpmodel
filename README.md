# Blood Pressure Classification Models

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
- [Getting Started](#getting-started)
- [Resources](#resources)
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
- [Reproducibility](#reproducibility) details provided.

## Reproducibility

Ensure the reproducibility of the study by following the provided steps in the [Reproducibility](#reproducibility) section.

## Getting Started

Clone the repository to your local machine and follow the steps outlined in [Reproducibility](#reproducibility) to recreate the analysis and results.

## Resources

- [GitHub Repository](https://github.com/lygitdata/bpmodel): Access the RMarkdown file and associated files for detailed analysis.
- [Issues](https://github.com/lygitdata/bpmodel/issues): Report any problems, ask questions, or suggest improvements.

## License

This project is licensed under the [MIT License](LICENSE).
