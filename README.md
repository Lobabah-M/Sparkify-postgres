# Description
This project was created for the purpose of analyzing data for the music streaming app ***Sparkify***. In particular, the analysis team is interested in understanding what songs the users are listening to. The data is modeled in a star schema using **Postgres** and is transfered using an ETL pipeline built in **python**.

# To Run the Project
To run the project first create the database and tables the run then ETL pipeline using the following commands.

```
   python create_tables.py
   python etl.py
```


# Repository Files Description
* **data** - a folder containing the datasets. 
    
* **sql_queries** - contains all sql statments needed to create the database, drop tables, create tables, insert data and query the database.

* **create_tables.py** - creates the database, drops the tables if they exist and create the tables.

* **etl.ipynb** - contains ETL processes to extracts a subset of the dataset and inserts it into tables

* **etl.py** - ETL processes for the entire dataset

* **test.ipynb** - tests to confirm that records were inserted successfully in the tables.

* **README.md** - contains a description of the project.

    