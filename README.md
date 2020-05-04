# Movies-ETL
ETL - Extract, Transform, Load

## Project Overview
Amazing Priming has tasked us to Extract movie data from json and csv files, Trasform that Data, and Load the clean the datasets.

### Resources
  * Python 3.7.6, Jupyter Notebook, Pandas, Numpy, SQLalchemy
  * Postgres 11.5, PgAdmin 4, SQL
  * wikipedia.movie.json, movies_metadata.csv, ratings.csv
  
### Challenge Summary
  * The code was refactored and the data was analyzed. 
  * The assumptions are within the code. Below here are a few:
    * We assumed that certain rows would have either null values or no values and that those rows or columns would need to be dropped.
    * We assumed that certain data types, such as date-time or time.
