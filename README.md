
# Instructions

## Development Environment
You can either work online, via MyBinder, or locally.

### MyBinder

Go to: https://mybinder.org/v2/gh/JKU-ICG/va_python_dashboard/master?urlpath=lab
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JKU-ICG/va_python_dashboard/master?urlpath=lab)
 and open the *template.ipynb* notebook.

### Local
Checkout this repo and change into the folder:
```
git clone https://github.com/JKU-ICG/va_python_dashboard
cd va_python_dashboard
```

Create a new environemnt and install the packages:
```
conda env create -f environment.yml
conda activate python-tutorial
```

Hint: For more information on Anaconda and enviroments take a look at the README form our [tutorial repository](https://github.com/JKU-ICG/python-visualization-tutorial).

Optional: Install Jupyter Lab extension for ipywidgets:
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Then launch Jupyter Lab :
```
jupyter lab
```

Goto http://localhost:8888/ and open the *template* notebook.

## Tasks

Perform the following tasks. You can use all or a subset of the data for the tasks. Additional data-wrangling may be necessary.
Then download the notebook (as HTML or the notebook itself) and submit it. You may also upload the notebook, the exported html and any other necessary files in a zip archive.

### Dashboard

1. Inspect the data and attributes, e.g. with [head()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html), and [dtypes](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes).
2. Select suitable attributes and visualize them in **three** visualizations
3. Define for **two** of the three visualizations crossfilters that are selections in the visualizations (e.g., with [altair](https://altair-viz.github.io/user_guide/interactions.html)). You can also combine selections for the crossfiltering. 
4. Interpret the results.

