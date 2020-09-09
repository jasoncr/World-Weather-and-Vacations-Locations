# python-api-challenge
In the first part of this exercise, I wanted to visualize the effects of proximity to the equator to weather trends. To do this I used Jupyter Notebooks to run my Python code. I used matplotlib, pandas, scipy, and numpy. I imported a data set from OpenMapWeather at https://openweathermap.org/api to use for my visualizations. I pulled in a 650 random cities from the world. Afterwards I cleaned the data to make it the most useful and threw out the cities with missing data. This left me with almost 600 cities to create visualizations for. I then created scatter plots for Latitude vs Max Temperature, Latitude vs Humidity, Latitude vs Cloudiness, Latitide vs Wind Speed. For brevity, I only included one of those plots. 
![lat_vs_humid](/output_data/lat_vs_humid.png)

I then explored how isolating cities based on Northern and Southern Hemispheres would affect the data. I re-did the plotting from above as well as added linear regression lines. Again, I only included one of those plots below.
![south_lat_vs_temp](/output_data/south_lat_vs_temp.png)

I came to the conclusions that: In the southern hemisphere, the cloudiness increases as the latitude approaches the equator, in the southern hemisphere, the maximum temperature increases as the latitude approaches the equator, and in the northern hemisphere, the maxiumum temperature decreases as the latitude retreats from the equator. Although these conclusions were quite obvious to the average person, now there is data to back up the common knowledge. 


The second part was to use this data to determine what would be a good place to go and visit. I filtered the data based on max temperature, wind speed, minimum temperature, and cloudiness so I would have the most comfortable vacation. I then use google maps API to find me a hotel close by. I plotted everything on a gmaps object so I would have all the information to make a great decision for my next vacation. 
![Sample2](/Images/083722.png)
