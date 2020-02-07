# Data_wrangling_branch_menus
Data wrangling from three sets of dirty data

The branch, node and edges files in csv format are clean data used for wrangling on distance.

The outlier csv contains only problems on data with outliers. The missing data csv contains only faulty of missing entries.
These two files are used for helping analyze errors in menu pricing and items accuracy in the dirty data file.

In the dirty data file, each column contains some different types of errors except for the order id. 
The script aims to fix all the problems.

My work
1. Dirty Data:
-- Fixing all problems in column date, branch code
-- Modeling for correct menu for different meals in each branch
-- Integration of the three clean data file with the dirty data to find correct distance with networkx

2. Outliers:
-- Find outlier of data 

3. Missing data
-- Fix up all missing data in the dataset with modeling. 
