# Housing-Regression
# NYC Housing Price Prediction

Linear regression model built from scratch to predict NYC housing prices.

## Files
- `housing_regression.ipynb` - main notebook
- `housing.csv` - dataset (place in same folder as notebook)

## What it does
1. Loads and explores the NYC housing dataset
2. Cleans data - removes duplicates, zero prices, outliers, fills nulls
3. Finds correlation between features and sale price
4. Builds a multiple linear regression model using the Normal Equation (no sklearn)
5. Evaluates using R², RMSE and MAE

## Features used
| Feature | Description |
|---|---|
| bldgarea | Building area |
| lotarea | Lot area |
| unitsres | Number of residential units |
| numfloors | Number of floors |

## Results
| Metric | Train | Test |
|---|---|---|
| R² | 0.036 | 0.040 |
| RMSE | $971,474 | $990,679 |
| MAE | $628,565 | $635,581 |

## Requirements
```
pandas
numpy
matplotlib
```

## How to run
1. Clone the repo
2. Place `housing.csv` in the same folder
3. Open `housing_regression.ipynb` and run all cells
