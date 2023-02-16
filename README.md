# Bike-Shop-Dashboard

In this project I went through the data cleaning process and dashboard creation in Excel of a Bike Shop Dataset. The aim of this project was to have a better understanding of the customers of this Bike Shop. 

## Step 1: Data Cleansing 
The first thing I did was to remove all duplicates from the dataset I did this by selecting the `remove duplicates` functions. I then realised that the Marital Status and Gender columns were stated as initials which can be clear for most people, but since I wanted the dataset to be as clear as possible I decided to to replace the initials with the full names. I did this, by selecting the columns, and then clicking `CTRL + H`, by doing this a the "find & replace" window popped up which allowed me to change names in the those columns. Third thing I did in the data was to create an Age Bracket column which allowed me to group the ages in the age column into three categories: Adolescent, Middle Age and Old. I did this by creating a nested IF statment: `=IF(L2>54, "Old",IF(L2>=31, "Middle Age",IF(L2<31,"Adolescent", "Invalid")))`. Lastly, I made sure to remove the decimal point in the Income collumn by selecting the `decrease decimal` function.

## Step 2: Pivot Tables and Charts

To be able to create the visualisation I created three Pivot Tables. 

The first one comparing the average income versus the Gender and for that I created a bar chart:
<img width="677" alt="image" src="https://user-images.githubusercontent.com/85926823/219498416-74fca74c-fbc5-4da0-acb8-5493600c7200.png">

The second one compared the commute distance versus whether those people purchased bikes or not and for that I created a line chart:
<img width="716" alt="image" src="https://user-images.githubusercontent.com/85926823/219498898-e75b7c64-439e-4737-a9cf-fe02453c820f.png">

The third one compared customers age brackets and whether they purchased a bike or not and for that I created a line chart:
<img width="704" alt="image" src="https://user-images.githubusercontent.com/85926823/219499200-182fe03f-6a47-40de-bd6b-43c37a75c4b9.png">

## Step 3: Dashboard 
The final dashboard consisted of three visualisation. I decided to add a slicer which allows the user to filter through the data in order to get the comparison that they are looking for: 

<img width="448" alt="image" src="https://user-images.githubusercontent.com/85926823/219499649-647640c3-63e6-4681-a2d9-55486a881fb7.png">


