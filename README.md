# SALES-ANALYSIS
An analysis of sales data over the year 2019 
# STEP BY STEP PROCESS
1. Importation of all modules used
2. Making use of the glob Module to merge all .csv files together as a single file for easier analysis
3. Read the new .csv file
4. Start cleaning the data by arranging it by 'Order Date' in ascending order
5. Create a new 'Month' column and ensuring that its the correct datatype
6. Removing all empty rows from the database with the .dropna function
7. Ensuring that all columns are in the appropriate datatype
8. Creating a new column 'Sales' for the total sales per order = quantity * price per unit
9. Determine the total sales per month
10. Using the matplotlib module created a bar chart
