# sqlalchemy-challenge


## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Bonus Part](#bonus_part)

## 🧐 About <a name = "about"></a>

Getting ready for a long holiday vacation to Honolulu, Hawaii!
For this project we are donig:
1.	Climate Analysis and Exploration
2.	Climate App
3.	Temperature Analysis 
4.  Daily Rainfall Average



## 🏁 Getting Started <a name = "getting_started"></a>


**Climate Analysis and Exploration:** <br>

using Python and SQLAlchemy to do basic climate analysis and data exploration of your climate database. 



**Precipitation Analysis:** <br>

•	Designing a query to retrieve the last 12 months of precipitation data. 

•	Selecting only the date and prcp values.

•	Loading the query results into a Pandas DataFrame and set the index to the date column.

•	Plotting the results using the DataFrame plot method.

•	Using Pandas to print the summary statistics for the precipitation data.



**Station Analysis:** <br>

•	Designing a query to calculate the total number of stations.

•	Designing a query to find the most active stations.

•	Designing a query to retrieve the last 12 months of temperature observation data (TOBS).



**Climate App:** <br>

designing a Flask API based on the queries that we have just developed. 

•	A dictionary using date as the key and prcp as the value.

•	A list of stations from the dataset.

•	The dates and temperature observations of the most active station for the last year of data.

•	List of the minimum temperature, the average temperature, and the max temperature for all dates greater than and equal to the given date.

•	List of the minimum temperature, the average temperature, and the max temperature for dates between the given start date and given end date.

## :doughnut:Bonus Part -	Temperature Analysis . <a name = "bonus_part"></a>


**Temperature Analysis I:** <br>

•	Hawaii is reputed to enjoy mild weather all year. Is there a meaningful difference between the temperature in, for example, June and December?

•	Identify the average temperature in June at all stations across all available years in the dataset. Do the same for December temperature.

•	Use the t-test to determine whether the difference in the means, if any, is statistically significant. Will you use a paired t-test, or an unpaired t-test? Why?



**Temperature Analysis II:** <br>

•	The starter notebook contains a function called calc_temps that will accept a start date and end date in the format %Y-%m-%d. The function will return the minimum, average, and maximum temperatures for that range of dates.

•	Using the calc_temps function to calculate the min, avg, and max temperatures for your trip using the matching dates from the previous year (i.e., use "2017-01-01" if the trip start date was "2018-01-01").

•	Plotting the min, avg, and max temperature from your previous query as a bar chart.
    o	Using the average temperature as the bar height.
    o	Using the peak-to-peak (TMAX-TMIN) value as the y error bar (YERR).



**Daily Rainfall Average:** <br>

•	Calculating the rainfall per weather station using the previous year's matching dates.

•	Calculating the daily normals. Normals are the averages for the min, avg, and max temperatures.

•	Creating a list of dates for the trip in the format %m-%d. Using the daily_normals function to calculate the normals for each date string and appending the results to a list.

•	Loading the list of daily normals into a Pandas DataFrame and set the index equal to the date.

•	Using Pandas to plot an area plot (stacked=False) for the daily normals.

