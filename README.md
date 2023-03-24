# ETL_mini_project

My partner for this mini project was Daniel Lee. My code is slightly different from Daniels'. Daniel used the Regex method for the contacts section, while I used Pandas. I also created a seperate `Data` folder for the final CSV files.

The ETL_Mini_Project_AFermanich.ipynb file is a Jupyter Notebook file that reads in the xlsx files in the `Resources` folder. This splits the data to be analyzed into four seperate sections: category, subcategory, campaign, and contacts. Various transformation methods were used to extract the data for each section. The resulting dataframes for each section were exported into the `Data` folder in my repository. 

The crowdfunding_db_schema.sql file is a SQL query used to create the Postgres_db tables. The ERD diagram is also included as a PNG file to display the relationships between all four tables. Both the SQL query and the ERD diagram notate primary and foreign keys. 

The crowdfunding_db_queries.sql file shows the select * queries that ran for each of the four imported CSV files.


