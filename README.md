# Store Sales Time Series Forecasting

## Overview
End-to-end time series forecasting pipeline for retail store sales
using the Kaggle Store Sales dataset.

## Dataset
- 3M+ rows | 54 stores | 33 product families | 5 years
- Source: Kaggle Store Sales - Time Series Forecasting

## Models Tested
| Model | MAE | vs Naïve |
|-------|-----|----------|
| Naïve Baseline | 159,000 | — |
| ARIMA | 140,000 | -12% |
| Prophet | 92,825 | -42% ✅ |

## Key Findings
- Oil prices show -0.70 correlation with sales
- STL decomposition outperforms classical decomposition
- Prophet best balance of accuracy and interpretability

## Tech Stack
Python · Prophet · ARIMA · LSTM · Pandas · Matplotlib · Sklearn

## Author
Favian Zamorano | MSc MBA
