# Excel-Bike-Shop-Dashboard

In this project we went through the data cleaning process and dashboard creation in Excel of a Bike Shop Dataset. The aim of this project was have a better understanding of the customers of this Bike Shop. 

## Step 1: Data Cleansing 
The initial data didn't need a lot of cleasing, however I decided to take it further to make a more understable. The first I did was to remove all duplicates from the dataset I did this by selecting the `remove duplicates` functions. I then realised that the Marital Status and Gender columns were stated as M, S, F; which might not be difficult to understand, but since I wanted the dataset to be as clear as possible I decided to to replace the initial with the full names. I did this, by selecting the columns, and then clicking `CTRL + H`, by doing this a the find & replace column popped up which allowed me to change names in the those columns. Third this I did in the data was to create an Age Bracket column which allowed me to group the ages in the age column into three categories: Adolescent, Middle Age and Old. I did this by creating a nested IF statment: `=IF(L2>54, "Old",IF(L2>=31, "Middle Age",IF(L2<31,"Adolescent", "Invalid")))`. Lastly, I made sure to remove the decimal point in the Income collumn by selecting the decrease decimal function.

## Step 2: Pivot Tables and Charts

