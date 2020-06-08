## Climate Analysis and Exploration:

Use Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database. 

This will be completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

To do this, use the provided starter notebook and hawaii.sqlite files to complete the climate analysis

and data exploration.

A start and end date must be chosen for the trip, ensuring the vacation range is approximately 3-15 days total.

Use SQLAlchemy create_engine to connect to your sqlite database.

Use SQLAlchemy automap_base() to reflect the tables into classes and save a reference to those classes

called Station and Measurement.

## Precipitation Analysis:

Design a query to retrieve the last 12 months of precipitation data.

Select only the date and prcp values.

Load the query results into a Pandas DataFrame and set the index to the date column.

Sort the DataFrame values by date.

Plot the results using the DataFrame plot method.

## Station Analysis:

Design a query to calculate the total number of stations, the most active stations, 

list the stations and observation counts in descending order.

Analyze the following: "Which station has the highest number of observations?"

Design a query to retrieve the last 12 months of temperature observation data (tobs).

Filter by the station with the highest number of observations.

Plot the results as a histogram

