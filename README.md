# Pandas_Demo

In this project, I demonstrate how to use Python programming language to analyse a csv dataset. The dataset is from the Stock Overflow Annual Developer Survey of 2019 https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2019.zip.

The scope is to demonstrate how to use common operations involved in manipulating and wrangling datasets in Pandas:

1. Load Data - in csv format.
2. Basics of a DataFrame & Series - Selecting Rows and Columns.
3. Indexes - Set, Reset, and using Indexes.
4. Filtering - using conditionals to Filter Rows and Columns.
5. Updating Rows & Columns - how to modify data within DataFrames.
6. Add/Remove Rows & Columns from DataFrames.
7. Sorting Data.
8. Grouping and Aggregating - analysing and exploring data.
9. Cleaning Data - casting Datatypes and Handling Missing values.
10. Working with Dates and Time Series Data
11. Reading/Writing Data to different sources - Excel, JSON, SQL, etc

# Common Pandas Operations

It is worthy noting that Pandas has vast capabilities in manipulating and wrangling dataset. Just like in the scope of this project, the following are the common operations:

1. Loading Data - Pandas provides functions like read_csv(), read_excel(), and read_sql() to load data from various file formats or databases into DataFrame objects.
2. Viewing Data: Use functions like head(), tail(), and sample() to view the first few rows, last few rows, or a random sample of rows in a DataFrame.
3. Filtering Data: Use boolean indexing or functions like query() to filter rows based on specific conditions.
4. Selecting Columns: Use indexing ([]), .loc[], or .iloc[] to select specific columns or subsets of columns from a DataFrame.
5. Sorting Data: Use the sort_values() method to sort rows based on one or more columns.
6. Grouping and Aggregating Data: Use the groupby() function to group data based on one or more columns, and then apply aggregation functions like sum(), mean(), count(), etc., to compute summary statistics for each group.
7. Merging and Joining Data: Use functions like merge() or join() to combine data from multiple DataFrames based on common columns or indices.
8. Reshaping Data: Use functions like pivot_table(), melt(), stack(), and unstack() to reshape data between wide and long formats.
9. Handling Missing Data: Use functions like isna(), dropna(), fillna(), or interpolate() to handle missing or null values in a DataFrame.
10. Applying Functions: Use the apply() method to apply custom functions to rows or columns of a DataFrame.
11. Combining Datasets: Use functions like concat() or append() to concatenate or append multiple DataFrames vertically or horizontally.
12. Pivoting Data: Use the pivot() function to reshape data based on column values.
13. Working with Time Series Data: Pandas provides functions for resampling, shifting, rolling, and computing various statistics on time series data.

## Disclaimer

This project is inspired by Corey Schafer's Tutorials on Pandas https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS.