# Airbnb-baseline-visualization

# About the project

The main goal of this project is to analyze the Airbnb listing in the Los Angeles area, provide visualization and some baseline strategy based on the EDA

# Methodology

* The data we used is collected by [Inside Airbnb](http://insideairbnb.com/get-the-data.html), an open source database that allows people to explore how Airbnb is really being used in cities around the world. Within lots of cities in the database, we focus solely on the Los Angeles area dataset. The data is scraped from the Airbnb website once every month, and normally is on the first Monday of each month. The available data for listings in NYC is ranging from 01 January, 2015 till now. For each of the monthly data, the dataset contains five files as the following 
  * **listings.csv.gz:** Detailed Listings data for the Los Angeles area
  * **Calendar.csv.gz:** Detailed Calendar Data for listings captured on the scarped day
  * **Reviews.csv.gz:** Detailed Review Data for listings
  * **Listings.csv:** summary information and metrics for listings
  * **Reviews.csv:** summary review data and Listing ID

* Use folim to perform cluster analysis and visualization. The interactive map can be a baseline tool for host to understand the average price in its area
* Use plotly to reveal the trend and the density of new listings on Airbnb in each of the areas. 

# Takeaways

![map4](https://github.com/ruilong96/Airbnb-baseline-visualization/blob/master/map4.gif)![map1](https://github.com/ruilong96/Airbnb-baseline-visualization/blob/master/map1.PNG)

![map3](https://github.com/ruilong96/Airbnb-baseline-visualization/blob/master/map3.PNG)![map3](https://github.com/ruilong96/Airbnb-baseline-visualization/blob/master/map2.PNG)

* Popular areas such as Santa Monica Beach, Beverly Hill are more expensive then the other areas.
* Los Angeles downtown is densely populated by the listings in the recent years, but the price are not as expensive as the other area.
* Roland heights area has more listings in the recent years with a relatively low price compared to the other area
* The listings to the north where is closed to Angeles National Forest is relatively expensive but is less supplied. We would recommend that the host in these areas add more listings.
