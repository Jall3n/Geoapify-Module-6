# Geoapify Challenge

## Purpose

- Create a Weather Database and use random sampling by utilizing the "np.random.uniform" function to generate a new set of latitudes and longitudes. We then input OpenWeatherMap's API key to retrieve latitude and longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and weather description. After creating a DataFrame we create an output file and export it into a csv. 
- Using the info created from the Weather Database we import the Geoapify API to create our Vacation Search folder and file. We create a new DataFrame that has the weather information as well as hotels based on our search parameters (min and max temp). We then clean the data and create a map with the city names, max temp, and weather description.

![Vacation_Search](https://github.com/Jall3n/Geoapify-Module-6/assets/119149740/d34afaaa-671f-4c73-a43c-855d0942f5a6)

- Finally we create a Vacation Itinerary folder and file. Import the Geoapify API and set the dependencies. We import the csv from the Vacation Search file and create a map that shows all the cities in our new DataFrame. We then choose four cities to travel to that meet our parameters and map out a travel path. 

![VacItinerary_3](https://github.com/Jall3n/Geoapify-Module-6/assets/119149740/a2d30e1c-91bb-4dfa-a81c-eee5e77dc122)

## Cities
- Taltal, Chile
- Monte Patria, Chile
- Puerto Varas, Chile
- Chonchi, Chile

Search parameters: Min Temp was 55 and Max Temp was 82



1. https://numpy.org/doc/stable/reference/random/generated/numpy.random.uniform.html
