# python-utils
This repo includes files with various reusable Python functions for data science tasks.

*Note*: These functions are built for Python 3.6+. Most notably, this includes ths use of f-strings. If you are working in an environment that uses Python 3.5 and below, please refer to the `python3.5` branch of this repository: <https://github.com/gregtam/python-utils/tree/python3.5>.

### Python Files
- `ml_utils.py`: Various useful functions to manipulate pandas DataFrames for use in machine learning, such as balancing classes or creating a limited number of dummy variables.

- `pandas_excel_utils.py`: Functions for saving pandas DataFrames as Excel sheets in better formats (e.g., colouring to visually separate groups or saving very large DataFrames).

- `plotting_utils.py`: Plotting utilities, mostly centring around machine learning model results.

- `sql_utils.py`: Reusable utility functions for interacting with an Impala cluster (e.g., saving a sub-select as a table or counting the number of non-null entries of all columns).
