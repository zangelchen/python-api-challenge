# python-api-challenge


Weather Analysis: 

Objective: Use Python script to visualize the weather of over 500 cities of varying distances from the equator using OpenWeatherMap API and citipy Python Library to create a representative model of weather across cities. 

Process: 
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. 
You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

Results: 
There is no correlation between city latitude and cloudiness. Which could mean that it is evenly dispersed and there is a bigger correlation between city longitude and cloudiness. 
![image](https://user-images.githubusercontent.com/117549284/213905266-5642b8d4-321e-46f9-9d27-c8f880bbe931.png)
![image](https://user-images.githubusercontent.com/117549284/213905275-e87a650f-fc15-42ab-8159-84e5f99b1077.png)

There is a slight positive correlation that increase in latitude means increase in humidity.
![image](https://user-images.githubusercontent.com/117549284/213905282-5b7dd5e6-2a5f-4d38-b901-a0f6d8954c22.png)
![image](https://user-images.githubusercontent.com/117549284/213905311-43e181dd-4105-4867-9d1b-51f6fd0b5bf6.png)

There is a strong negative correlation that increase in latitude means decrease in temperature. 
![image](https://user-images.githubusercontent.com/117549284/213905288-6981f89c-71ca-4682-b2d0-eab7ac16d651.png)
![image](https://user-images.githubusercontent.com/117549284/213905289-0280c59e-93b5-4fad-acfd-24fca050e984.png)

There is a weak correlation between latitude and wind speed. However, this unique dispersion could indicate a stronger correlation between longitude and wind speed. 
![image](https://user-images.githubusercontent.com/117549284/213905294-fa6359fa-be5b-4182-b10d-91654d231ee5.png)
![image](https://user-images.githubusercontent.com/117549284/213905297-10ce9cb3-58e3-40c6-806d-c36c21c71f10.png)

Vacation Analysis: 
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

Create a map that displays a point for every city in the city_data_df DataFrame within the parameters of an ideal weather condition.

Create a second map to find the first hotel located within 10,000 meters of your coordinates.Add the hotel name and the country as additional information in the hover message for each city on the map. 

![image](https://user-images.githubusercontent.com/117549284/213905421-dd1ae685-5659-4e76-99ef-f0354cf03524.png)

















