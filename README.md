# 2022 Airbnb Listing Analysis
You can view the full report here: https://public.tableau.com/app/profile/bryce.mandap/viz/AirbnbRevenueAnalysis2022/Dashboard1

## Background
The primary objective of this project was to enhance my proficiency in creating visually appealing UI designs, while also incorporating prescriptive analytics techniques. Airbnb is widely recognized as the industry leader in the lodging domain, and given the immense popularity of San Diego as a sought-after tourist destination in Southern California, investing in property within the region can prove to be a lucrative opportunity.

## Project Objective
The principal aim of this project is to facilitate prospective investors in comprehending the dynamics of the lodging industry, with a particular emphasis on Airbnb, and to evaluate its potential as a profitable investment option. Additionally, it can serve as a valuable guide for individuals who are contemplating investing in a property within San Diego, by assisting them in identifying the key factors and variables to consider for making informed investment decisions.


# Project Breakdown
This project includes 4 significant sections to help investors gain insight into Airbnb Listings

## KPI Card Overview
- This allows the audience to easily identify the most significant metrics and key performance indicators at a single glance. 
    - KPI's include: Number of Listings, Avg. Listing Price, Avg. Revenue, Avg. Review Score, Reviews per Month
    - These KPI Cards are also dynamic to the applied filters
    
## Geographical Clustering Map
- Allows the user to identify groups/clusters that are most populated by other Airbnb Hosts
- Provides insight into which neighboorhoods are most profitiable based on the shape of the circles
- Hovering over each circle can provide additional granularity specifically Property Details and Host details

## Frequency Bar Chart
- Identifies which neighboorhoods have had the most sold listings 
- This can also show which neighboorhoods are most sold depending on the different quartiles of revenue

![image](https://user-images.githubusercontent.com/129364286/230003488-845dac7a-8ae9-4462-9f93-12a63e2a3204.png)

## Dynamic Corelation Scatter Plot
- Enables the user to swap different Independent variables to compare the correlation amongst a variety of features
    - e.g) Can visualize the correlation between the Review Rating and Expected Revenue
    - e.g) Can also visualize the correlation between the number of accomodations to expected revenue 

![image](https://user-images.githubusercontent.com/129364286/230002811-ad58dbaf-31b6-4ff2-bd02-e9f665971780.png)


## Insights Found and Suggestions 
- The property owners within the 75th Percentile (or top 25%) based on revenue, have an average listing price of 438$ with an average of 3.17 review per month
    - In this scenario, reviews can be viewed as guaranteed bookings, therefore, these property book their properties 3 times a month
- Parkwest neighborhood has the highest avg revenue ($354,785), with Rosevile being second ($270,624)
- The top 5 neighboords with the most sold listings within the top 25% of earners are: Mission Bay, Ocean Beach, Pacific Beach, North Hills, and  La Jolla
- Number of Beds, Price, and Number of Accomodations have a positive correlation with Expected Revenue
    - Review/Rating however has the lowest correlation
