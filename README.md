Working on Real Project with **Python**
(A part of Big Data Analysis)

The Weather Dataset
Here, The Weather Dataset is a time-series data set with per-hour information about the weather conditionsat a particular location. It records temperature,dew point temperature,
relative humidity , wind speed, visibility ,  pressure , and conditions.
This data is available as a CSV File. We are going to analyze this data set using the Pandas DataFrame.

How to Analyze DataFrames ?

.head()
it shows the first N rows in the data (by default, N=5)

.shape
it shows the total no.of rows and columns of the dataframe

.index
This attribute provides the index of dataframe

.coulumns
It shows the name of each column

.dtypes
It shows the data-type of each column

.unique()
In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.

.nunique()
It shows the total no. of unique values in each column. It can be applied on a single column as well as on whole dataframe.

.count
It shows the total no. of non-null values in each column. It can be applied on a single column as well as on whole dataframe.

.value_counts
In a column, it shows all the unique values with their count. It can be applied on single column only.

.info()
Provides basic information about the dataframe.

