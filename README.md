NAME- SHRIRANG LAKHPURKAR 

PRN-25070123108 

CLASS -ENTC B2

AIM To perform data wrangling and preprocessing on a dataset using Python libraries like Pandas and NumPy, including handling missing values, cleaning inconsistent data, and transforming data into a proper format.

THEORY Data wrangling (also called data cleaning) is the process of transforming raw data into a clean and usable format. In this experiment, various functions of Pandas and NumPy are used to identify, handle, and correct data issues.

-Libraries Used pandas (pd) → Used for data manipulation and analysis. numpy (np) → Used for numerical operations and handling missing values (NaN).

-Functions Used and Explanation

pd.DataFrame() Used to create a DataFrame from structured data (like dictionary).

np.nan Represents missing or undefined values in the dataset.

isna() Detects missing values (NaN). Returns True where value is missing.

notna() Opposite of isna(). Returns True where values are present.

isna().sum() Counts total missing values column-wise.

isna().sum(axis=1) Counts missing values row-wise.

dropna() Removes rows with missing values.

dropna(axis=1) Removes columns with missing values.

fillna() Fills missing values with a specified value.

replace() Replaces specific values in the dataset.

pd.to_numeric() Converts data to numeric type. errors="coerce" converts invalid values into NaN.

mean() Calculates average of column values.

median() Calculates median value of column.

fillna(mean/median) Used to fill missing numerical values: Mean → for Age Median → for Marks

str.upper() Converts text to uppercase. Used to fix inconsistent formatting in categorical data.

pd.to_datetime() Converts data into datetime format.

CONCLUSION In this experiment, we successfully performed data wrangling using Pandas and NumPy. We learned how to: Detect and handle missing values Clean inconsistent data Convert data types
