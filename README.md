2023 LOAN DISBURSEMENT AND SETTLEMENT
Objective
The objective of the project is to explore and analyze the year 2023 data sets related to loan disbursement and settlement.
The key aspects covered in this segment includes:

a)	Importation of Libraries
import pandas as pd  - Imports the Pandas library and assigns it the alias pd. Pandas is a powerful library for data manipulation and analysis.
import numpy as np  - Imports the NumPy library and assigns it the alias np. NumPy is used for numerical operations on arrays and matrices.
import matplotlib.pyplot as plt  - Imports the pyplot module from the Matplotlib library and assigns it the alias plt. Matplotlib is a popular plotting library.
import seaborn as sns  - Imports the Seaborn library and assigns it the alias sns. Seaborn is built on top of Matplotlib and provides a high-level interface for statistical graphics.

b)	Reading Data
Involves reading the data set to be used for analysis
df = pd.read_excel('loans.xls', engine='xlrd')
df.head()-the code reads an Excel file named 'loans.xls' into a Pandas Data Frame called df, and then it displays the first few rows of the Data frame using df.head().
df = pd.read_excel('settlement.xls', engine='xlrd')
df.head()-the code reads an Excel file named 'settlement.xls' into a Pandas Data Frame (df) using the 'xlrd' engine and then displays the first few rows of the Data Frame.

1.	Data Distribution Exploration
