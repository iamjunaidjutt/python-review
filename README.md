# Python Data Science & Analytics Review

A comprehensive hands-on Python data science review covering NumPy array operations, Pandas data analysis, and Matplotlib/Seaborn statistical visualizations.

---

## Overview

This repository serves as a practical, notebook-driven review of foundational Python libraries for data analysis and scientific computing. It includes structured Jupyter notebooks paired with real-world sample datasets to demonstrate core data manipulation, aggregation, and visualization workflows.

---

## Notebooks & Topics

### 1. `numpy.ipynb` — Numerical Computing
- Multidimensional array creation, shaping, and indexing.
- Vectorized array operations and broadcasting rules.
- Statistical aggregations, boolean masking, and linear algebra fundamentals.

### 2. `pandas.ipynb` — Data Wrangling & Analysis
- Pandas Series and DataFrame structures.
- Data ingestion from CSV (`mercedesbenz.csv`, `wine.csv`, `data.csv`) and Excel spreadsheets (`Excel_Sample.xlsx`).
- Filtering, column transformations, handling missing values, and group-by aggregations.

### 3. `matplotlib.ipynb` — Foundational 2D Plotting
- Figure and axes object hierarchies.
- Line charts, scatter plots, bar charts, and histograms.
- Multi-plot canvas layouts with subplots, color palettes, and axis legends.

### 4. `seaborn.ipynb` — Statistical Data Visualization
- Distribution plots, KDE graphs, and joint plots.
- Categorical box plots, bar plots, and violin plots using real datasets (such as Tips).
- Matrix heatmaps for feature correlation analysis.

---

## Included Datasets

- `mercedesbenz.csv` — Feature matrix for automotive regression testing.
- `wine.csv` — Chemical composition dataset for classification and outlier analysis.
- `cu.item.csv` — Consumer price item index table for tabular operations.
- `Excel_Sample.xlsx` — Multi-sheet workbook for validating spreadsheet imports.
- `data.csv` — Tabular numerical dataset.

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/iamjunaidjutt/python-review.git
cd python-review
```

### 2. Create a virtual environment & install dependencies

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

pip install -r requirements.txt
```

### 3. Launch Jupyter Lab or Notebook

```bash
jupyter notebook
# or
jupyter lab
```

Select any of the `.ipynb` notebooks to run the cells interactively.

---

## Project Structure

```
python-review/
├── numpy.ipynb            # NumPy operations and array math
├── pandas.ipynb           # Pandas DataFrames and data manipulation
├── matplotlib.ipynb       # Matplotlib visualization tutorials
├── seaborn.ipynb          # Seaborn statistical visual workflows
├── requirements.txt       # Python dependencies
├── requirements.py        # Environment reference file
├── *.csv / *.xlsx         # Sample analytical datasets
└── README.md              # Project documentation
```

---

## License

This project is open-source and available under the [MIT License](LICENSE).
