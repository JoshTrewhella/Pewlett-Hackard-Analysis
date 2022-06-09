# Pewlett-Hackard-Analysis

## Overview of the Analysis
Bobby has asked us to clean his data and perform analysis to determine how many people will be retiring in his company and how many of those will be eligible for a retirement package. 

We started by created ERD maps to help visualize our database that we created in SQL Postgres. We then created 6 tables using the CSV files provided to us by Bobby using SQL's query editor. Once these were ready, we imported the data and exported the new tables to CSV files. 

Next we needed to create a retirement table with employees born between 1/1/1952 and 12/31/1955. In order to do this we joined the employees table and the titles table to include all employees in this range. After this we ended up with 3 new CSV files: retirement_titles.csv, unique_titles.csv and retiring_titles.csv. 

Finally, we needed to determine which of these employees were eligible for the mentorship program. Here, we created a table with employees born between 1/1/1965 and 12/31/1965 by joining the employees table and the department employee table. 

## Results
Retiring by Title Table: 


## Summary
