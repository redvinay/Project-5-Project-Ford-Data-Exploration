# Project-5-Project-Ford-Data-Exploration

## About The Dataset:
The Ford Go Bike data file "201811-fordgobike-tripdata.csv.zip" is taken from url "https://s3.amazonaws.com/fordgobike-data/index.html". 
Each trip is anonymized and includes and following information is available in url "https://www.fordgobike.com/system-data":

•Trip Duration (seconds)
•Start Time and Date
•End Time and Date
•Start Station ID
•Start Station Name
•Start Station Latitude
•Start Station Longitude
•End Station ID
•End Station Name
•End Station Latitude
•End Station Longitude
•Bike ID
•User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
•Member Year of Birth
•Member Gender
•Bike Share for all Trip



## Summary of Findings:

1. Most of the users are spening around 100 to 600 minutes 
2. There is no strong relation between age and duration 
3. Females are spending more time and most of them are customers. Moreover, females are almost spending same time with and without sharing their bikes 
4. Subscribers are not spending much time as compared to the customers
5. Female customers are lesser in their age among all. Males and Others, whose age is above 35 are not likely to share their bikes

## Key Insights for presentation:

In this investigation, I wanted to look at the characteristics of different user types, age and their behaviour that could be used to predict their duration.
The main focus was on the three parametrs: Age, User Type, and Bike Sharing Behaviour.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the histogram of duratiom in minutes. Post that, I have used the heat map to find the 
relationship between age and duration. Finally, I use the point plots for the relation between 
Duration by Gender and User Type and then the Duration by Gender and Bike share. 
