
AUTHORS: Avery Hall and Anders Shenholm

DATA: basketball stats and player info between 1950-2017
Find data here: https://www.kaggle.com/drgilermo/nba-players-stats

STATUS: Running as planned. Tested on Google Chrome and Safari.


Basic startup info:

Database set-up:

In psql: CREATE DATABASE [database_name];

In unix command line: psql -U [psql_username] [database_name] < data/data.sql

Config set-up:

Create a python file in the main directory named config.py
It should contain:
user = '[psql_username]'
database = '[database_name]'
password: ''

Running the app:

In unix command line: python3 app.py localhost 5000


