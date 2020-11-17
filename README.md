# Tableau-Homework

![tableau](Images/tableau.png) ![tableau](Images/tableau.png) ![tableau](Images/tableau.png)

## Background
Congratulations on your new job! As the new lead analyst for the New York Citi Bike Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.
Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.
However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Submission
I used 5 months of data 201911 through 202003 to capture the most recent data not affected by the COVID-19 pandemic. I used a union to merge the [data](Data/JC-201911-citibike-tripdata_Union.csv).

I then created two dashboards:

[Bike Path Dashboard](Tableau/Bike_Path_Dashboard.twbx) -> This dashboard compares the number of records per zip code per capita income using the 2018 census data layer. You should be able to click on each bike station (which increases in size per # of records) to view all ending stations drawn out along with the average trip time in hours.

[Bike Gender Dashboard](Tableau/Bike_Gender_Dashboard.twbx) -> This dashboard breaks down the number of records per user type (customer or subscriber) and genders. This is also reflected in the map which provides Male/Female Ratio per the 2018 census data layer. The start stations can be clicked on to filter the tables on the dashboard.