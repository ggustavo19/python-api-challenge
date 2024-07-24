# python-api-challenge
Assignment: What is the weather like as we approach the equator?
If someone asks more quesions.How would you explain and prove it using data?

## Instructions
- Part 1: WeatherPy
  - Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
    - To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:
      - Latitude vs. Temperature
      - Latitude vs. Humidity
      - Latitude vs. Cloudiness
      - Latitude vs. Wind Speed
  - Requirement 2: Compute Linear Regression for Each Relationship
    - To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.
    - Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values as you can see in the following image
      - ![image](https://github.com/user-attachments/assets/41bc514c-cd05-4272-9f67-5da19bd80611)
    - You should create the following plots:
      - Northern Hemisphere: Temperature vs. Latitude
      - Southern Hemisphere: Temperature vs. Latitude
      - Northern Hemisphere: Humidity vs. Latitude
      - Southern Hemisphere: Humidity vs. Latitude
      - Northern Hemisphere: Cloudiness vs. Latitude
      - Southern Hemisphere: Cloudiness vs. Latitude
      - Northern Hemisphere: Wind Speed vs. Latitude
      - Southern Hemisphere: Wind Speed vs. Latitude
    - After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.
- Part 2: VacationPy
  - In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
  - Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
  - Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
    - ![image](https://github.com/user-attachments/assets/0fc3aa02-9051-4846-b8c0-c56018560f8a)
  - Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
    - A max temperature lower than 27 degrees but higher than 21
    - Wind speed less than 4.5 m/s
    - Zero cloudiness
  - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
  - For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
  - Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
    - ![image](https://github.com/user-attachments/assets/69634fa3-aa50-422a-aa9c-0c372769cf80)
 
  
    
