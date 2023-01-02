# MTA_EDA_Analysis
In this project, based on the NYC MTA turnstile and census datasets entries and exits distributions.
# Introduction
The aim: Defining the best locations for the ticket seller 	teams to get most participation to WomenTechWomenYes gala. The gala will be hald on June,26 2023. Observing the predict turnstile value, the data examine between the dates of Jan,1  2022 to Nov,03 2022. 
The Problem: Right finding datasets and determining the right locations to analyze the right results
Solution: Determining the most optimal stations and locations considering the peak hours by correcting the mismatches in the dataset, data processing for cleaning the data set that varies cumulatively and obtaining the real data, visualization of the data and notification of the correct locations.
# Datasets
MTA(Metropolitan Transportation Authority)
Webpage: http://web.mta.info/developers/data/nyct/turnstile/
![mta](https://user-images.githubusercontent.com/111016714/210203237-0ebfd9d1-1d84-4421-b5c1-85ec4b7ff45f.PNG)

NYC Census
![nyc_popdens_labels_layout2](https://user-images.githubusercontent.com/111016714/210203429-09daed76-574a-407c-8656-002b1b05c70c.png)
Webpage: https://www.nyc.gov/site/planning/data-maps/open-data.page

# Methodology
- Data manipulations and operations were performed using pandas, numpy libraries
![pic1](https://user-images.githubusercontent.com/111016714/210205565-fdfd611a-056b-4f6e-9bb3-a8b6cd0b1ed1.PNG)
- Converting cumulative values to raw values
- Cleanig the NaN values, adding the needed columns(as Weekdays,Raw values, Traffic) converting the Datatime Timestamp to integer.
- Adding the functions necessary for reading and analyzing the data
- Using data visualization methods

# Conclusion
- As a result:
- Top 10 Busiest Stations observed
- Which days were found to be predominantly busier
![busiest_days_stations](https://user-images.githubusercontent.com/111016714/210207228-57bf756f-3f73-4887-ab76-770e85502eec.png)


- Based on the census data, population density was also observed through graphs
![heatmap_census](https://user-images.githubusercontent.com/111016714/210207235-6e8dedce-26a8-4e63-b957-216b56d4a1b5.png)




