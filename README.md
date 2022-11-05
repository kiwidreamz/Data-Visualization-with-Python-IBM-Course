# Data Visualization with Python (IBM Course)

I created this repository to keep a copy of the three python projects we created in the labs of this 5-week course as well as my answer to the final assignment.

[Link](https://www.coursera.org/learn/python-for-data-visualization) to the course on Coursera.

---------------------------------------- 

## Dash Basics Exercice

#### Goal
Create a dashboard that displays the percentage of flights running under specific distance group. Distance group is the distance intervals, every 250 miles, for flight segment. If the flight covers to 500 miles, it will be under distance group 2 (250 miles + 250 miles).

#### Expected Output
Below is the expected result from the lab. Our dashboard application consists of three components:

#### Title of the application
Description of the application
Chart conveying the proportion of distance group by month

#### To do:
Import required libraries and read the dataset
Create an application layout
Add title to the dashboard using HTML H1 component
Add a paragraph about the chart using HTML P component
Add the pie chart above using core graph component
Run the app

-----------------------------------------

## Dash Interactivity Exercice

#### Goal
Extract average monthly arrival delay time and see how it changes over the year as the user inputs a different year. Year range is from 2010 to 2020.

#### Expected Output
Title of the application
Component to enter input year
Chart conveying the average monthly arrival delay


#### To do:
Import required libraries and read the dataset
Create an application layout
Add title to the dashboard application using HTML H1 component
Add an input text box using core input component
Add the line chart using core graph component
Run the app

----------------------------------------

## Flight Delay Exercice

#### Dashboard Components
Monthly average carrier delay by reporting airline for the given year.
Monthly average weather delay by reporting airline for the given year.
Monthly average national air system delay by reporting airline for the given year.
Monthly average security delay by reporting airline for the given year.
Monthly average late aircraft delay by reporting airline for the given year.
NOTE: Year range should be between 2010 and 2020

#### Expected Output
Title of the application
Component to enter input year
5 Charts conveying the different types of flight delay. Chart section is divided into three segments.
Carrier and Weather delay in the first segment
National air system and Security delay in the second segment
Late aircraft delay in the third segment


#### To do:
Design layout for the application.
Create a callback function. Add callback decorator, define inputs and outputs.
Review the helper function that performs computation on the provided inputs.
Create 5 line graphs.
Run the application.

-------------------------------------------

## Final Assignment

As a data analyst, you have been given a task to monitor and report US domestic airline flights performance. Goal is to analyze the performance of the reporting airline to improve flight reliability thereby improving customer reliability.

#### Key report items

Yearly airline performance report 
Yearly average flight delay statistics
NOTE: Year range is between 2005 and 2020.

#### Components of the report items
Yearly airline performance report

#### For the chosen year provide

Number of flights under different cancellation categories using bar chart.
Average flight time by reporting airline using line chart.
Percentage of diverted airport landings per reporting airline using pie chart.
Number of flights flying from each state using choropleth map.
Number of flights flying to each state from each reporting airline using treemap chart.
Yearly average flight delay statistics

#### For the chosen year provide

Monthly average carrier delay by reporting airline for the given year.
Monthly average weather delay by reporting airline for the given year.
Monthly average national air system delay by reporting airline for the given year.
Monthly average security delay by reporting airline for the given year.
Monthly average late aircraft delay by reporting airline for the given year.
NOTE: You have worked created the same dashboard components in Flight Delay Time Statistics Dashboard section. We will be reusing the same.

#### Expected Layout

Requirements to create the expected result
Two dropdown menus: For choosing report type and year
Each dropdown will be designed as follows:
An outer division with two inner divisions (as shown in the expected layout)
One of the inner divisions will have information about the dropdown and the other one is dropdown.
Layout for adding graphs.
Callback function to compute data, create graph and return to the layout.

###### Here is a quick look at the dashboard for my final assignment

![Dashboard](https://i.imgur.com/cwR4XOn.jpg)
