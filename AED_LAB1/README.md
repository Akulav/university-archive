# AED Lab 1: Housing Data Analysis

Exploratory data analysis and linear regression on a housing dataset (Boston Housing style, target column `MEDV`).

## What it does

- Prints summary statistics: median, min, max, range and skew for every column
- Fills missing values with the column median
- Visualises distributions and correlations
- Trains a linear regression model with `scikit-learn` and reports MSE and R²

## Running

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
python lab1.py
```

The script expects `HousingData.csv` in the working directory. The dataset is not included in this repository.
