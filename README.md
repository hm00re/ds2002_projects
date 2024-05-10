# ds2002_projects - Project 2
Helena Moore 

Batch and streaming files for Project 2 are located in the "final_project" folder. Load this into DBFS in databricks.

This project utilizes the sakila_dw database from Project 1. This data can be imported to the azure sql database by dumping the sakila_dw created from running all files in "midterm" folder into a destination database.

Import hm_final_project_ds2002 into databricks and run after the above steps.

## ds2002_projects - Project 1

**Files:**

All files for Project 1 are located in the "midterm" folder. 

SQL files for creating the original source sakila database are located in the "sakila-db" folder.

The JSON file source for this project is located in the "data" folder.


**Instructions:**

Run files in "sakila-db" folder to create source database. 

If there is a pre-existing database named "sakila_dw" in your MySQL workbench, drop this database before proceeding to the next step.

Run hm_project1.ipynb as a jupyter notebook, and run midterm_Create_Populate_Dim_Date.sql when directed to by hm_project1.ipynb. This performs the ETL pipeline for the dimensional datamart sakila_dw, and demonstrates functionality through aggregate SQL queries.

