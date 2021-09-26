# World_Weather_Analysis

###################################
#Purpose
###################################
The purpose of this project is to collect and analyze weather data for the traveling website Plan My Trip.  The data provided will be used to recommend ideal hotels based on the clients desires.  Interactive features were devloped to convey available hotels based on the users input.  Additionally, users are able to map a route for their trips with the ability to plan stops along the way.  
###################################
#How We Did It!
###################################
Results were obtained using the NumPy module to generate random latitudes and longitudes.  The citipy module was used tp list the nearest city to the random latitudes and longititudes we generated.  Using the OpenWeatherMap API we requested current weather data for each unique city on the list, and added the desired data to a DataFrame.  A min max statement was used to allow the client to enter their preferred minimum temperature requirement and maximum temperature requirement for travel.  Locations within the specified temperature range are populated for the user to see.  Locations were added to a DataFrame and four locations were randomly selected and markers were added to each location. 
Using Google API's Directions and Maps, four random locations were selected to highlight the applications Vacation Itinerary function and a route was planned giveing the user the option to travel by various methods.

