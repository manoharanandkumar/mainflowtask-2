# Superstore Sales Data Analysis

A Jupyter Notebook exercise exploring a retail sales dataset with pandas, NumPy, Matplotlib, and Seaborn. The notebook inspects data quality, computes descriptive sales statistics, and builds visual summaries such as histograms, box plots, a correlation heatmap, and sales breakdowns by region and category.

## Notebook

Open [`TASK-2.ipynb`](TASK-2.ipynb) in Jupyter Notebook or JupyterLab and run the cells in order.

## Data setup

The notebook currently reads a local Windows file path (`C:/Users/Manoh/Downloads/archive (1)/sales_data.csv.csv`). Download or provide the dataset separately, then update the `pd.read_csv(...)` paths in the notebook to your local file location before running it. Do not commit data unless its license permits redistribution.

The dataset shown in the notebook includes fields such as order date, region, category, product, and sales. Some later cells check for `Profit` and `Discount`, but those columns are not present in the displayed dataset, so those particular analyses are skipped.

## Tech stack

Python · Jupyter Notebook · pandas · NumPy · Matplotlib · Seaborn

## Scope

This is an exploratory notebook rather than a deployed forecasting or business-intelligence application. Treat the charts and statistics as descriptive summaries of the provided dataset.
