# Data Modeling with Postgres for Udacity Data Engineering Nanodegree

## Project overview
This is data modeling with **Postgres** project for Udacity Data Engineering Nanodegree. In this project I create a database schema in **Postgres** database and **ETL** pipeline that would load JSON files into the database using **Python** and **SQL** in order to facilitate the analysis of this data. This JSON files represent a user activity logs collected by a music streaming app of an imaginary startup Sparkify.

## Python scripts

* create_tables.py: Drop previous schema and creates empty tables
* sql_queries.py: Defines all queries used in the ETL pipeline
* etl.py: Loads data from the JSON files into the tables

## Database schema

* `artists`: Artists in the music database
* `songs`: Songs in the music database
* `users`: Users of the app
* `songplays`: Records of song plays in log files 
* `time`: Timestamps of records

## Prerequisites
The code is **Python** in the form of scripts and in a **Jupyter Notebook** and it uses:

* [PostgreSQL](https://https://numpy.org/)
* [Psycopg](https://pypi.org/project/psycopg2/)
* [Pandas](https://pandas.pydata.org/)

## Run the Code

`jupyter notebook etl.ipynb`

`python create_tables.py`

`python etl.py`
