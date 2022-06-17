# pd.merge() combined with rename(columns=...)

This method is used to merge multiple dataframes. By default, it will compare each dataframe and if there is a matching column, 
the merge will be applied there. 
One thing I learned to make merging simpler if there are columns that mean the same thing but have differing column names, 
is to rename the columns before the merge. 

* Make sure the data in those columns actually are related. 
