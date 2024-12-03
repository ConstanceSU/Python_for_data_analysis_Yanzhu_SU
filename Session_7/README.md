Session 7 - Pandas II

1. Lambda and map

A **Lambda** function is an anonymous tranformation. It is a **pure** function, since the output only depends on the input, with no side effects. 

On the other side, **map**, is another option, originally created for **series** to perform one-to-one transformations. It is supposed to be faster than **apply**. For those familiar with **applymap**, note that this method will be deprecated in future versions.

2. Series

- Mainly used for time series and 1D observations
- **Rolling** performs a sliding window over the over series

2. Advanced data manipulation

- value_counts
- drop_duplicates
- groupby
- pivot_table
- query - explore in a neat manner
- merge & join dataframes based on a specific column

4. Handling missing data and data transformation 
