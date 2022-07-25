# ETL: Extract, Transform and Load - Movie Data Analysis

## Project Overview
This project uses the ETL method to analyze 1990 - 2018 movie data taken Wikipedia and Kaggle (sourced from MovieLens). <br>
<br>
The project methods include:
- Creating an ETL pipeline from raw data to a SQL database.
- Extracting data from disparate sources using Python.
- Cleaning and transforming data using Pandas.
- Using regular expressions to parse data and to transform text into numbers.
- Loading data with PostgreSQL.

## Resources
<b>Data Sources:</b><br>
- Wikipedia web scrape: wikipedia-movies.json<br>
- Kaggle data from Kaggle.com: movies_metadata.csv and ratings.csv

<b>Software:</b><br>
- Jupyter Notebook 6.4.8<br>
- Python 3.9.12<br>
- Pandas 1.4.2<br>
- Numpy 1.21.5<br>
- sqlalchemy 1.4.39<br>
- psycopg2 2.9.3

## Summary
The project was developed using four Jupyter Notebook files to extract the initial data, analyze and clean the data, combine the data, and link to a local PostgreSQL database to export two final tables (movie and ratings).

<b>1. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ETL_function_test.ipynb" target="_blank">ETL_function_test.ipynb:</b></a> The purpose of this file is to test the initial import of the source files.<br>
<b>2. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ETL_clean_wiki_movies.ipynb" target="_blank">ETL_clean_wiki_movies.ipynb:</b></a> The purpose of this file is to test cleaning of the Wikipedia data. <br>
<b>3. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ETL_clean_kaggle_data.ipynb" target="_blank">ETL_clean_kaggle_data.ipynb:</b></a> The purpose of this file is to clean the data found on Kaggle.com (sourced from MovieLens).<br>
<b>4. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ETL_create_database.ipynb" target="_blank">ETL_create_database.ipynb:</b></a> The purpose of this file is to combine all previous functions (importing and cleaning the data), merging the data, and connecting to PostgreSQL to output two final tables.

Screen captures of the final tables:<br>
<b>1. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/movies_query.png" target="_blank">movies_query.png</b></a><br>
<b>2. <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ratings_query.png" target="_blank">ratings_query.png</b></a>

