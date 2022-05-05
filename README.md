# Project 1: Summary

This project creates a postgres database for Sparkify music app. For the modeling of the database, the star schema is used.

## Running Python scripts

On Jupyter Notebook click on File -> New -> Terminal

`python create_tables.py`

## Song play example queries

Number of users level most listened to.

`SELECT level, count(level) FROM songplays group by level`

## Running ETL pipeline

Run on Terminal:

`python create_tables.py`

`python etl.py`
