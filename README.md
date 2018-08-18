# Project---Ebay-auto-sales-analysis
Project - Ebay auto sales analysis
## Data clean processing
* briefly look through the data to learn dataset shape, missing values number, and data types
** DataFrame.info()
* remove columns where all rows contain the same value
** DataFrame.drop()
* clean columns name (prefer snakecase)
** DataFrame.columns or DataFrame.rename()
* convert text number to numeric 
** explore this column with Series.unique() to find pattern and special cases
** remove non-digital characters with str.replace
** change data type with Series.astype()
** change column name if required
* extract values from strings
* correct bad values
* deal with missing data
* export cleaned data
