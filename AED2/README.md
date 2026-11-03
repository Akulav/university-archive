# AED Lab 2: Labour Force Participation

Exploratory analysis and binary regression on a labour force participation dataset (`lfp`, `wc`, `hc`, ...).

## What it does

- Converts yes/no columns to booleans and checks for missing values
- Plots histograms with mean and median markers for each feature
- Draws a correlation heatmap
- Fits a probit model with `statsmodels`

## Running

```bash
pip install pandas seaborn matplotlib scikit-learn statsmodels
python datas.py
```

The script expects `Lab_2_data.csv` in the working directory. The dataset is not included in this repository.
