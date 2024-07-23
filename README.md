## Python Bulk Load- CSV data to Big Query table
This notebook was created to upload data from csv file, which was a resulting file from a previous ETL process to a Google Big Query data base table. 


## Quick Description
After creating the table and passing the data to it using parameters stored in Google Drive, the program makes a SQL request to the recently created table and reads the data into a Pandas data frame.  The resulting table crated in Big Query will also later be connected to Looker Studio for the creation of different reports and dashboards


## Modules used
-from google.cloud import bigquery
-from google.oauth2 import service_account
-from google.colab import drive
-pandas
