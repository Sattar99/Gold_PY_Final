# Gold_PY_Final — Superstore Statistical Analysis

A statistical analysis of the Superstore retail dataset, applying hypothesis testing to real sales data.

## What it does

- Loads and cleans the Superstore dataset (drops redundant/non-informative columns, restructures for analysis)
- Runs statistical tests to evaluate assumptions and relationships in the data, including:
  - **Shapiro-Wilk** test for normality
  - **Levene's test** for equality of variances
  - **One-way ANOVA** and **Kruskal-Wallis** for group comparisons
  - **Chi-squared test** for categorical associations
- Visualises findings with `matplotlib` and `seaborn`

## Tech stack

- **Language:** Python (Jupyter Notebook)
- **Data:** `pandas`, `numpy`
- **Statistics:** `scipy.stats`
- **Visualisation:** `matplotlib`, `seaborn`

## Project structure

```
Gold_PY_Final/
└── Gold_PY_Final/
    ├── Gold_FinalProject.ipynb    # Main analysis notebook
    ├── Assignment_Market.pdf      # Assignment brief
    ├── superstore.csv             # Raw dataset
    └── CleanedSuperStore.csv      # Cleaned dataset
```

## Getting started

```bash
pip install pandas numpy matplotlib seaborn scipy
jupyter notebook "Gold_PY_Final/Gold_FinalProject.ipynb"
```

## License

See [LICENSE](./LICENSE).
