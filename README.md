# Movies-ETL
Module 8 - Written with Python mainly in jupyter notebooks

## Overview of Project

Client needs help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We are tasked with refactoring the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL (Extract Transform Load) process by adding the data to a PostgreSQL database.

### Purpose
1.  Write an ETL function to read three data files
2.  Extract and Transform the Wikipedia Data
3.  Extract and Transform the Kaggle Data
4.  Create the Movie Database


## Resources

* Python 3.7.6, Visual Studio Code 1.50.1, Jupyter Notebook

* Data Sources:
  --ETL Deliverable 1 starter code (Links in Canvas.)
  --ETL Deliverable 2 starter code (Links in Canvas.)
  --ETL Deliverable 3 starter code (Links in Canvas.)

## Summary
* The three data files are passed into the function.  All three data sets where converted to DataFrames, and the DataFrames are correct and displayed.
* TV shows are filtered out, and the wiki_movies DataFrame is created.  A try-except block was used successfully.  All of the tasks for the extraction & transformation of the Wikipedia data are completed.  The cleaned Wikipedia data is converted to a DataFrame, and the DataFrame is displayed properly.
* During the extraction & transformation of the Kaggle metadata, the following are done:  The metadata is cleaned, the Wikipedia and Kaggle DataFrames are merged and the "movies" DataFrame is created and performed.  Three tasks completed during the extraction & transformation of the MovieLens rating data.  The Kaggle and ratings DataFrames are correct and displayed.
* The data in the movies table in the SQL database was replaced.  The ratings table is dropped, and the MovieLens rating CSV file was added to the SQL ratings table.  The elapsed time to add the data to the database is displayed.

## Challenge Overview
It was difficult in the sence this project was less linear.  Also, there was several points of code having a roadblocks if try-except handling exceptions weren't properly implemented.
