# Traffic Safety Analysis

## The Situation
You've just joined the analytics taskforce of the New York City Police Department as they look to analyze traffic accident data for the city's Public Safety initiative.

## The Assignment
Your team has access to data on all the traffic accidents in New York City from January 1st, 2021 up to April 9th, 2023.
Your task is to analyze the data with the purpose of finding interesting patterns and trends to help the NYPD prevent future accidents.

## The Objectives
1. Identify seasonal patterns
2. Visualize weekly trends
3. Analyze contributing factors

## The Data Set

#### NYC Traffic Accidents
Motor vehicle collisions reported by the New York City Police Department from January 2021 to April 2023. Each record represents an individual collision, including the date, time, and location of the accident (borough, zip code, street name, latitude/longitude), vehicles and victims involved, and contributing factors.

#### Recommended Analysis
1. Compare the % of total accidents by month. Do you notice any seasonal patterns?
2. Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?
3. On which particular street were the most accidents reported? What does that represent as a % of all reported accidents?
4. What was the most common contributing factor for the accidents reported? What about for fatal accidents specifically?

#### Objective 1: Identify seasonal patterns
Your first objective is to calculate the number of collisions by month and year, and visualize them using line charts.

* Calculate the count of 'Collision ID' by year and month, and visualize it using a line chart.
* Filter out the incomplete month of April 2023.
* Modify the line chart so that each year is shown as a separate line.
* Apply formatting to finalize the chart and summarize insights from the analysis.

#### Objective 2: Visualize weekly trends
Your second objective is to calculate the number of collisions by time of day and day of week, and visualize the data using a heatmap.

* Extract the Weekday and Hour from the 'Date' and 'Time' columns.
* Calculate the count of 'Collision ID' by Weekday and Hour.
* Create a heatmap to visualize collision hotspots by time of day and day of week.
* Modify the heatmap to a "white-white-red" 3-color scale to keep focus on the most dangerous periods in the week and summarize the insights from your analysis.

#### Objective 3: Analyze contributing factors
Your final objective is to find the top 10 contributing factors by number of collisions, and calculate the percentage of the collisions involving injuries or fatalities.

* Calculate the count of 'Collision ID' by 'Contributing Factor'.
* Filter the top 10 contributing factors by collisions, and sort them in descending order.
* Calculate '% of Dangerous Collisions' for each contributing factor by taking the number of collisions with an injury or fatality and dividing them by the total.
* Add data bars to the '% of Dangerous Collisions' values to visualize the results, and summarize the insights from your analysis

#### [Project Link]()