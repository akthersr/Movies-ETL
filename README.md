# Movies-ETL

## Overview of the project

Amazing Prime, a movie streaming service want us to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We have to refactor the code from this module to create a function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data and performs the ETL process by adding the data to a PostgreSQL database. In oreder to create the pipeline,we follow this ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database. At the end,they organized a functional hackathon.

## Data Source

Data Source: wikipedia_movies.json, movies_metadata.csv, ratings.csv

Data Tools: PostgreSQL13, pgAdmin

Softwares:Python 3.9.7, Jupyter Notebook 6.4.5

## Analysis

This analysis consists of four steps:

- Create an ETL Function to Read Three Data Files

- Extract and Transform the Wikipedia Data

- Extract and Transform the Kaggle data

- Create the Movie Database

