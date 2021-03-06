#### -- Project Status: [Active, On-Hold, Completed]

Completed
## Project Intro/Objective
Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

The goal of this project was to collect data from Citi Bike website and glean insights into the selected data. 
### Methods Used
* Python Data Cleaning, Merging and Loading Data
* Data Visualization

### Technologies

* Python, Pandas, Jupyter 
* CSV files
* Tableau Desktop/Public

### Project Description

* Loaded June, July, August 2020 data into Python
Step 1-Imported data and merged
Step 2-Split start time and stop time columns to remove hours 
Step 3-Dropped unknown from gender columns 
Step 4-Ran several codes to determine the following: 
    a.Male 1-3575258 Female 2-1910540 Unknown- 831797 (Dropped from data)
    b.Subscriber is 4425504 Customer 1060294
Step 4-Exported csv

* Created in Tableau
1-Top 10 Start Station Name-The Top 10 Stations are calculated by total minutes. These starting points are located mostly in higher traffic popular areas for both citizens and tourists. All are located in Mnahattan up to Central Park. 
2-Bottom 10 Start Station Name-These are located in the upper Manhattan and Bronx areas of the city. 
3-Top 10 End Station Name-The Top 10 End stations mirror the Top 10 Start stations in the city. This is indication of heavy use in these areas. 
4-Bottom 10 End Station Name-The Bottom 10 End stations are located mostly the Jersey City area with two located in the Bronx. This is an interesting pattern and it may be an anomaly. 
5-Subscriber vs Customer Age Group-In the Customer group the dominate age category are those born in the 1990's with the 1980's in second place. However for the Subscriber age group, those born in the 1980's are the dominate group followed by the 1990's. However the gap is smaller in this case than in Customer group between groups. Of note, from a Subscriber the 1970's, 1960's and even the 1950's are much higher usage than for Customer group. 
6-Age/Gender and Trip Duration-Female's born in the 2000's, 1990's and 1980's had higher average trip duration than males born in 2000's. 
7-Gender Avg Trip-June-July-August-Females had the over higher trip duration than males in each month. Of note, even the lowest trip duration for females was higher than the males highest month of June. 
8-Gender vs UserType-Male Subscribers were the highest number and slighly higher in the Customer category. In both Male and Female the Subscriber category was highest
9-Subscriber vs Customer Trip-Analyzing week by week Subscriber trip durations were highest consistently. Of note, Subscriber and Customer trends had similiar peak times and both drop significantly by end of the August time frame. 



### Preview

![Gender User](https://github.com/jeffstpeterson/NYC-Citibike-Tableau-Analysis/blob/master/Images/Gender%20v%20User.png)

![SubscribervCustomers](https://github.com/jeffstpeterson/NYC-Citibike-Tableau-Analysis/blob/master/Images/Subscriber%20vs%20Customer.png)
## Contact
Jeff Peterson
jeffstpeterson@icloud.com
