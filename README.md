# Movies-ETL

## Overview of the Project

The focus of this project was to build a program that would take in large sources of data, clean them, merge them, and then export them to a postgresSQL database, that can be later used for analysis by developerss. This was achieved by performing the ETL (Extract-Transform-Load) on three data files, Wikipedia data, Kaggle metadata, and the MovieLens rating data.

- movie data from Wikipedia, in a JSON file (6.2 MB);
- movie metadata downloaded from Kaggle, as a CSV file (34 MB);
- movie ratings data from MovieLens, as a CSV file (709.6 MB).

A code was written in juypter notebook that performed the following task:
- importing data from large CSV files into pandas dataframes;
- removing columns or rows with unnecessary or corrupted data;
- renaming columns for easier use;
- extracting and cleaning useful data from existing columns using regular expressions;
- merging datasets to maximize utility;
- exporting data to a postgresql database.

## Result

1) In file 'ETL_function_test.ipynb' we create an ETL function to read the three data files.
2) In file 'ETL_clean_wiki_movies.ipynb' we extract and transform the Wikipedia data 
3) In file 'ETL_create_database.ipynb' we extract and transform the Kaggle data
4) In file 'ETL_create_database.ipynb' we create the movie database
