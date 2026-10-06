# Data Analysis with NumPy, Pandas and Seaborn

A hands-on exploratory data analysis project in Python. It covers array computing, data manipulation, data cleaning and visualization across eight real-world datasets.


**Run on Kaggle:** https://www.kaggle.com/code/sabrinalom1/mlb-2-combined-assignment-sabrin-alam

## What this project covers

### NumPy
- Creating 1D to 4D arrays with `array`, `arange`, `reshape`, `ones`, `zeros`, `random` and `linspace`
- Array attributes and memory usage when changing data types
- Statistical operations, indexing, slicing, stacking and splitting

### Pandas
- Series and DataFrame creation, inspection and summary statistics
- Filtering with `loc`, `iloc`, `query` and `isin`
- GroupBy aggregations and multi-level summaries
- Merging and joining relational tables
- Time series work: datetime indexing, resampling and rolling averages

### Data cleaning
- Imputing missing values in a categorical column using the mode
- Detecting outliers with the IQR rule and handling them by trimming and capping

### Data visualization
- **Univariate:** pie, count, KDE with rug, violin, box, boxen, histogram
- **Bivariate:** scatter, line, joint, hexbin, 2D KDE, box, violin, swarm, count
- **Multivariate:** pair plot, PairGrid, heatmap, FacetGrid, hue-based joint and boxen plots

## Datasets

| Dataset | Used for |
|---|---|
| Restaurant tips | Arrays, filtering, distributions, relationships |
| Titanic | DataFrame inspection, survival analysis |
| Iris | Multivariate plots |
| Superstore sales | GroupBy aggregation |
| Delhi daily climate | Time series analysis |
| UCI Adult census | Missing value imputation |
| Diabetes prediction | Outlier handling (age) |
| House prices | Outlier handling (price) |

## Key insights
- Restaurant bills are right-skewed (mean above median), and tips increase with bill size.
- Titanic passenger class is closely tied to both fare and survival rate.
- Iris species are separated best by petal length and width.
- House price data contains invalid zero values and extreme outliers. Trimming reduces the row count, while capping keeps every row.
- Delhi temperature shows a clear repeating yearly seasonal cycle.

## Tech stack
Python, NumPy, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Author
Sabrin Alam
southeast University
