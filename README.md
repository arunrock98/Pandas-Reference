# working notes
Working with Data Pre processing and data cleaning
## Handling Missing Values
1. How to Handle the Missing Values
Real-world data often has missing values.

Data can have missing values for a number of reasons such as observations that were not recorded and data corruption.

Handling missing data is important as many machine learning algorithms do not support data with missing values.

In this tutorial, you will discover how to handle missing data for machine learning with Python.

Specifically, after completing this tutorial you will know:

1.How to marking invalid or corrupt values as missing in your dataset.
2.How to remove rows with missing data from your dataset.
3.How to impute missing values with mean values in your dataset.

## Visualize the Missing Values
we will look at how we can identify and mark values as missing.

We can use plots and summary statistics to help identify missing or corrupt data.

We can load the dataset as a Pandas DataFrame and print summary statistics on each attribute.

#### Impute Missing Values

There are many options we could consider when replacing a missing value, for example:


1.A constant value that has meaning within the domain, such as 0, distinct from all other values.
2.A value from another randomly selected record.
3.A mean, median or mode value for the column.
4.A value estimated by another predictive model.


Any imputing performed on the training dataset will have to be performed on new data in the future when predictions are needed from the finalized model. This needs to be taken into consideration when choosing how to impute the missing values.
examples - please look into titanic dataset