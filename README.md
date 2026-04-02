# Coffee Shop Daily Revenue Forecasting

## Overview
Time series forecasting project using a real coffee shop's transaction data (March 2024 – March 2025).
Five models compared: XGBoost, Prophet, ARIMA, Linear Regression, and a Weighted Ensemble.

## Dataset
Transaction-level coffee shop sales data (~3,600 records).
Source: https://github.com/Shehrhass/Time-Series-and-Demand-planning/blob/main/index_1.csv


## How to Run
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Shehryar_Hassan_Final_Assignment_vFn.ipynb` in Jupyter
4. Update the file path in Cell 2 to point to your local dataset
5. Run all cells top to bottom

## Results
| Model | MAE | RMSE | MDA |
|---|---|---|---|
| XGBoost | $135.93 | $179.73 | 62.16% |
| Linear Regression | $138.02 | $171.93 | 58.11% |
| Weighted Ensemble | $140.98 | $173.41 | 56.76% |
| Prophet | $141.88 | $178.00 | 47.30% |
| ARIMA | $220.65 | $276.94 | 0.00% |

## Blog Post
https://medium.com/@shehryarh0/predicting-trends-for-demand-planning-xgboost-as-the-ultimate-barista-c71e2d641b55
(https://medium.com/p/c71e2d641b55)