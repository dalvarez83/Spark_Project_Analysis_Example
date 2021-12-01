# Spark Project Analysis Example
Example of machine learning at scale (distributed data). Developing a distributed PySpark pipeline for implementing logistic regression and random forest algorithms to predict click-through rates.

## Steps to follow files in this repository

`Load_Parquet_files.ipynb`: takes raw data and converts to parquet and dataframe formats

`EDA_Pandas.ipynb`: converts raw data to pandas dataframe and performs fulsome EDA in Pandas

`EDA_Spark.ipynb`: converts parquet files to Spark dataframe and performs light EDA in Spark

`FeatureEngineering-Spark.ipynb`: takes Spark dataframe and performs light EDA checks and data processing

`Data_Processing.ipynb`: takes Spark dataframe and performs data processing required for creating processed dataframe for algorithm implementation

`Logistic_regression_implementation.ipynb`: takes processed dataframe and performs logistic regression algorithm implementation (with and without hash transformation)

`Random_forest_implementation.ipynb`: takes processed dataframe and performs random forest algorithm implementation
