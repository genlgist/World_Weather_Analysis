# World_Weather_Analysis

Regina Negrycz 
genglist@yahoo.com 
Module 6 Challenge 
Submitted 5 Jun 2021 
Due 6 Jun 2021 
WeatherPy_travel_map.png
WeatherPy_travel_map_markers.png
WeatherPy_Database.csv
README.md

# Deliverable 1 - Retrieve Weather Data
I needed to generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap along with the current weather description for each city. I then needed to create a new DataFrame containing the updated weather data.

I was able to pull 727 cities with their lat/lng, max temp, humidity, cloudiness, wind speed and current description.  The DataFrame was created correctly and I was able to save the data into WeatherPy_Database.csv.

# Deliverable 2 - Create a Customer Travel Destinations Map

I needed to use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. I then had to show those destinations on a marker layer map with pop-up markers.

The search for cities having temperatures from 75-90 degrees resulted in 278 rows.  There was 1 empty row which was removed.  A search was then done for hotels within 5,000 meters, 13 of which were dropped due to no hotel names.  The results are stored in WeatherPy_vacation.csv.  A map was then created to display the city name, country code, weather and max temp.



# Deliverable 3 - Create a Travel Itinerary Map

I used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. I then created a marker layer map with a pop-up marker for each city on the itinerary.

I read the WeatherPy_vacation.csv into a DataFrame.  I picked 4 citites for an itinerary route and got their lat/lng, created a direction layer map.  I chose 4 cities in Brazil, 1 of which was to the west of the Amazon Rainforest.  There was no travel route available from that city to the 3 other cities on the east coast.  I then created a map for those 4 cities.