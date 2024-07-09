*** Pandas:-***
#  Pandas is an open-source library mainly used for --> working with relational or labeled data 
#  fast 
#  high-performance,
#  productive capabilities. 

#  Pandas provides functionalities for 
#  analyzing, cleaning, exploring, and manipulating data efficiently.

# Key Features of Pandas
1.Data Cleaning:-  Delete irrelevant rows, wrong values, and empty/null values.
2.Fast and Efficient:-  Data manipulation and analysis, easy to load data.
3.Time Series Analysis:-  Built-in functionality for time series analysis.
4.Flexibility:-  Easy handling of missing data, inserting and deleting columns and records from DataFrames.


# Uses of Pandas
1 Data cleaning
2.Merging and joining datasets
3.Handling missing data
4.Grouping data (GroupBy functionality)
5.Split-apply-combine operations
6.Data visualization


# Installation python Copy code
!pip install pandas
Importing Libraries
import pandas as pd
import numpy as np


***Data Structures in Pandas***
1.Series: 1D labeled array capable of holding any data type (integers, strings, floating-point numbers, etc.).
2.DataFrame: 2D labeled data structure with columns of potentially different types.
3.Panel: 3D labeled array (Deprecated).

# Creating Series
1.From a NumPy array
2.With custom labels
3.From a dictionary
4.From a list


# Creating DataFrames
1.From a dictionary
2.From a list of lists
3.From a dictionary of NumPy arrays

# Importing and Exporting DataFrames
Export to CSV:-pd.to_csv()
Read from CSV:-pd.read_csv()

Export to JSON:- df.to_json()
Read from JSON:- pd.read_json()

# Check Size and Index
>---size
>---index

# Get Data Types
>---dtypes
>
# Describe Data:
>---describe()

# Check for Null Values
>isnull().sum()
>isna().sum()

# Transpose DataFrame:-row into columne and column into rows 
> print(df.T)
