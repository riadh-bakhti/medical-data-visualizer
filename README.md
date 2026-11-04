# Medical Data Visualizer

Exploratory visualisation of the medical examination dataset with pandas, seaborn and matplotlib.

The data is cleaned first: a BMI based `overweight` column is added, `cholesterol` and `gluc` are reduced to binary values, and impossible blood pressure or outlier height/weight records are removed.

Two figures are produced:

- `catplot.png` - counts of the categorical variables, split by cardiovascular disease
- `heatmap.png` - correlation matrix of the cleaned data

## Run

```
pip install -r requirements.txt
python main.py
```

## Tests

```
python -m unittest test_module
```
