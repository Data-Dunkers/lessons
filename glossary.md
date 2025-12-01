# Glossary

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
