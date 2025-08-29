![Project Header](https://github.com/mayank1ahuja/diwali_sales_da/blob/c16070f63aa5c5cb88713f591d39311cff3c952c/Project%20Header.png)
<h1 align="center">DIWALI SALES ANALYTICS</h1 align="center">

<h3 align="center">A personal practice project focused on learning-by-doing with retail data.</h3 align="center">

---

## Project Intent 

This repository is a personal practice project created to learn, experiment with, and document retail analytics techniques focused on the Diwali festival. The emphasis is on clarity, explanation, and demonstrating the learning process — not on delivering production-grade engineering.


## Project Overview

This repository demonstrates how raw retail transaction data can be cleaned, explored, and analysed to surface festival-driven business signals. The analysis is delivered as a Jupyter Notebook, providing a clear and structured walkthrough of the process.

**Learning goals:**

- Practice data ingestion, cleaning, and validation in pandas.
- Build concise exploratory analyses and visualizations focused on festival behaviour.
- Practice matplotlib and seaborn for visualization.
- Produce an honest, well-documented artifact a learning log.

---

## Project Steps 

1. **Environment** — Work is carried out in a Jupyter Notebook. The analysis uses common data libraries so the notebook is reproducible locally.

2. **Imports** — Standard imports are used for the tasks implemented in the notebook (pandas, numpy, matplotlib and seaborn).

3. **Load & Inspect** — The notebook loads the CSV and runs quick verification commands (`df.shape`, `df.head()`, `df.info()` / `df.dtypes`) to validate ingestion.

4. **Cleaning** — The notebook performs basic cleaning patterns such as handling missing values.

5. **Exploratory Analysis** — The notebook contains groupby-based analyses and visual checks.


## Work Done

This section lists the concrete code patterns and checks that are implemented in `diwali.ipynb`:

- Imported `pandas`, `numpy`, `matplotlib` and `seaborn` (basic environment setup).
- CSV ingestion with `pd.read_csv()` is used to load the data.
- Basic inspection commands (`df.head()`, `df.info()`) are present.
- Missing-value handling (`df.isnull()`, `df.dropna()`) is implemented.
- Basic visualizations using `seaborn` and `matplotlib`.


## Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Packages: `pandas`, `numpy`, `matplotlib`, `seaborn`

Quick install:

```bash
pip install pandas numpy matplotlib seaborn
```


