# animals_billionaires
homework 06-Pandas

# Animal, billionaires Data Analysis

Homework analyzing a dataset of cats and dogs, global billionaires using **pandas**, **matplotlib**

## What I Did
- Explored the dataset (shape, dtypes)
- Used `value_counts()` to find distributions (gender, type/source of wealth, companies, countries)
- Used `.groupby()` and `.sort_values()` to compare wealth and age across groups (e.g. gender, self-made vs. not, by country)
- Calculated averages, sums, and percentages with `.mean()`, `.sum()`, and `normalize=True`
- Filtered data using `.query()` and `.isin()`
- Created visualizations: horizontal bar charts, histograms, scatterplots, and bar graphs
- Read in JSON data with `pd.read_json()`

## Skills Practiced
- Data sorting, filtering and grouping in pandas
- Aggregation and summary statistics
- Basic data visualization
- Reading different file formats (CSV/Excel/JSON)

## Files
- `01-Billionaires.ipynb` / `02-Billionaires.ipynb` — completed notebooks
- `billionaires.json` — most recent billionaires data