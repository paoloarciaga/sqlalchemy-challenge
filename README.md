# sqlalchemy-challenge

This repo consists of the following deliverables: 
- Analysis where I explored the climate data 
- Flask API I designed, based off the queries I developed

## Precipitation Analysis
In this part of my analysis, you will see how I completed the following: 
- A query that finds the most recent date in the dataset (8/23/2017) 
- A query that collects only the date and precipitation for the last year of data without passing the date as a variable 
- Saved the query results to a Pandas DataFrame to create date and precipitation columns 
- Sorted the DataFrame by date 
- Plotted the results by using the DataFrame plot method with date as the x and precipitation as the y variables 
- Used Pandas to print the summary statistics for the precipitation data 

## Station Analysis
In this part of my analysis, you will see how I completed the following: 
- Designed a query that correctly finds the number of stations in the dataset (9) 
- Designed a query that correctly lists the stations and observation counts in descending order and finds the most active station (USC00519281) 
- Designed a query that correctly finds the min, max, and average temperatures for the most active station (USC00519281) 
- Designed a query to get the previous 12 months of temperature observation (TOBS) data that filters by the station that has the greatest number of observations 
- Saved the query results to a Pandas DataFrame
- Plotted a histogram with bins=12 for the last year of data using tobs as the column to count.

## Flask API
In my python file, you will see how I designed my flask application that does the following: 
-  Generates the engine to the correct sqlite file 
-  Uses automap_base() and reflect the database schema 
-  Saves references to the tables in the sqlite file (measurement and station) 
-  Creates and binds the session between the python app and database 
-  Displays the 5 available routes (precipitation, stations, tobs, start, and start/end) on the landing page

I worked with my tutor who edited parts of my python file, as my initial code only had 3 out of the 5 API routes working. Upon doing so, I was able to successfully fix my code and got all 5 API routes to work. 
