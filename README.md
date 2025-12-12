# Project Title

## Description

This project demonstrates various functionalities of the Pandas library, including:

*   **Series creation and manipulation:** How to create Pandas Series from lists, dictionaries, and scalar values, and perform basic arithmetic operations.
*   **DataFrame creation and manipulation:** How to create Pandas DataFrames from lists of lists, dictionaries, and Series, and access specific elements.
*   **Arithmetic operations on DataFrames:** Performing addition, subtraction, multiplication, and comparison operations between DataFrame columns.
*   **Data insertion and deletion:** Methods for adding new columns (`insert()`, direct assignment) and removing columns (`pop()`) from DataFrames.
*   **CSV file operations:** Reading data from a CSV file (`read_csv()`) and writing a DataFrame to a CSV file (`to_csv()`).
*   **Handling missing data:** Using `dropna()` to remove rows/columns with missing values and `fillna()` to replace them with specified values or using forward/backward fill methods.
*   **Data replacement:** Using `replace()` to substitute specific values within a DataFrame.

## Installation

To run this code, you will need to have Python and the Pandas library installed. You can install Pandas using pip:

```bash
pip install pandas
```

If you also want to use NumPy (as demonstrated in some cells), install it as well:

```bash
pip install numpy
```

## Usage

The code is organized into several sections, each focusing on a specific Pandas feature. You can run the code cells sequentially in a Jupyter Notebook or Google Colab environment to see the demonstrations.

### Key Sections:

*   **Series:** Cells demonstrating the creation and basic operations of Pandas Series.
*   **DataFrame:** Cells showing how to create and access data in Pandas DataFrames.
*   **Arithmetic operations in Pandas:** Examples of performing calculations on DataFrame columns.
*   **Insert:** Demonstrations of adding new columns to a DataFrame.
*   **Delete:** Examples of removing columns from a DataFrame.
*   **CSV file operations:** Code for reading from and writing to CSV files.
*   **Dropna & Fillna:** Examples of handling missing values.
*   **Replace:** Demonstrations of replacing specific values.

### Example (Reading a CSV file):

```python
import pandas as pd

csv_1 = pd.read_csv("text1.csv")
display(csv_1.head())
```

Make sure `text1.csv` is present in the same directory as your notebook or provide the correct path.
