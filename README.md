# Pandas
Pandas provides a large variety of methods aimed at manipulating and cleaning your data
Missing data can be identified using the .isnull() method. Missing data can be counted per column by chaining in the .sum() method, which returns a Series of counts per column.
Missing data can be removed using the .dropna() method, which can be customized using different parameters
Duplicate data can be found using the .isduplicate() method
The .drop_duplicates() method can be used to drop duplicate records, providing significant customization on which records to consider as duplicate and which records to keep.
Pandas can access Python string methods using the .str attribute. This can be helpful in applying vectorized cleaning methods on messy text data.
