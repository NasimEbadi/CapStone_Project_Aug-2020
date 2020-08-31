# CapStone_Project_Aug-2020
This is my capstone project for the TDI during summer 2020.
In this project I predicted air quality index (AQI) in the U.S. in 2020 under three different scenarios of the Covid-19 pandemic. 
In this project I used datasets from multiple sources including:
1.GDP and Unemployment Rate from BLS by county for 2020 on quarter one and two
2.Covid-19 confirmed cases and number of deaths by county from CDC
3.AQI, tempreture, and wind data by county from the EPS
4. Zipcodes/county FIPs from data.world


Using pyhton Pandas tools I merged and edited these datasets to get a final dataset that is suitable for ML analysis.

To conduct the analysis I defined a model for each county and predicted three values for each scenario per county.

I also made an interactive map for the prediction using CARTO.com:

https://nasimebadi.carto.com/builder/27d6f3a4-04c7-48f6-aa9b-3e44dee6f027/embed

