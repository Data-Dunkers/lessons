# Glossary

## DataFrame

A table of data in pandas made up of rows and columns. It’s the main structure you use to store, view, sort, filter, and analyze datasets in Python.

## df.head()

Shows the first few rows of a DataFrame. The part before the dot (such as `df` or `df_reduced`) is the name of the DataFrame you are working with. By default it displays 5 rows, but you can change this by adding a number inside the parentheses (for example, `df.head(10)` or `df_reduced.head(10)` shows the first 10 rows).

## `import pandas as pd`

**What it does:**
This line loads the **pandas** library, one of the most widely used tools for working with data in Python.

**Why it matters:**
Pandas gives you powerful ways to load, clean, sort, filter, and analyze datasets. Almost every data activity you do in a Jupyter or Colab notebook will use pandas at some point.

**How it works:**

* `import pandas` brings the library into your notebook
* `as pd` creates a shorter nickname, so you can write commands like `pd.read_csv(...)` instead of `pandas.read_csv(...)`

**Typical uses:**

* Loading CSV files
* Viewing tables
* Calculating summary statistics
* Sorting or filtering rows
* Preparing data for charts and visualizations

**Example:**

```python
df = pd.read_csv("your_file.csv")
df.head()
```

## `pd.read_csv()`

Reads a CSV file and loads it into a pandas DataFrame. You use this function to bring external data—such as NBA stats—into your notebook so you can sort, filter, and analyze it.

## plotly.express

A Python library used to create interactive charts such as scatter plots, bar charts, and histograms. It allows you to hover over points, zoom in, and explore data visually with only a few lines of code.

## scatter plot

A chart that shows individual data points on a graph using two numerical variables. Each point represents one row of data—such as a single player—so you can see patterns, clusters, and outliers based on how the points are positioned.
