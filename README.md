# Crowdfunding_ETL
 The goal of this project was to Extract the data we were given from the two excel files. Then Transform the data inside of the Jupyter notebook to ensure it is prepped for analyzation. Finally Load the data into its own database inside SQL. 
 
 The first part of this project we worked on getting all of the data from the excel files inside of the Jupyter notebook. 

 first we loaded in the corwdfunding excel file. we started by sperating the "category & sub-category" column into two seperate columns. We then created two seperate data frames. One for all the different categories, and the other for all the different sub-categories. the method we chose to do this by was by using list comprehensions. Then finally we exported both the two data frames into their own CSV files.

 We then created the campaign data frame that also was from inside the crowdfunding excel file. Our goal with this dataframe was to change the data types of the "goal, pledged, and launch date" columns. This was our main objective for transforming this dataframe. finally, we again loaded the campaign dataframe into its own CSV file.

 We finished off the Jupyter notebook by creating the contacts data frame. We had to start by loading in the Contacts excel file into the Jupyter notebook. We chose option one, and used Pandas to create the dataframe. From the "name" column, we broke that column up into two seperate columns. One for the first name and one for the last name. Finally, we exported that dataframe into its own CSV file.

 To begin the SQL part of the project, we started by creating the crowdfunding database, created the tables for all for of the CSV files. The category, sub-category, campaign, and contacts tables were created. We then imported the data into each respective table from each CSV file. To ensure that the data was imported we ran 'SELECT * FROM ("Table Name")' for each table, and all the data was in each table.


