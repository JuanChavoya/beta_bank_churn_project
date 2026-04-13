# Beta Bank: Customer Churn Prediction

## Overview
This project develops a machine learning model to predict customer churn for Beta Bank. The dataset exhibits significant class imbalance (approximately 80% retention vs 20% churn). Three resampling techniques were evaluated: class weighting, manual oversampling, and manual undersampling.

## Results
| Metric | Validation Set | Test Set |
|--------|---------------|----------|
| F1-Score | 0.6107 | 0.6471 |
| AUC-ROC | 0.8666 | 0.8695 |
| Accuracy | 84% | 85% |

The final Random Forest model with manual oversampling exceeded the business requirement of F1 >= 0.59.

## Repository Structure
