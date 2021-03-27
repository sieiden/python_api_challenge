# python_api_challenge
NW Bootcamp assignment

# Weather PY Observations

The strongest relationship evaluated was city latitude and temperature. The r-value for both the northern and southern hemispheres was over 0.5 (northern hemisphere was over 0.8). This means that latitude is a good indicator of temperature and could be used to predict with some accuracy the maximum temperature of that city.

There does not appear to be a strong relationship between city latitude and cloudiness or humidity for either the northern or southern hemispheres (the r-value was below 0.4 for all relationships). This means that it would be difficult to accurately create a model to predict a city's humidity or cloudiness levels based on the latitude.

For the 500+ random cities my API call pulled, the northern hemisphere has a stronger relationship between a city's longitude and max temperature than the southern hemisphere. The r-value for the northern hemisphere is -0.88 while the southern hemisphere's r-vlaue is only 0.58.

# Vacation Py

This repository also contains a heatmap of the humidity of all 500+ cities within the VacationPy folder. The Vacation Py notebook filters the clean_cities_data2 csv file for cities that have my ideal weather. Then a map with markers indicating a hotel is created using Google's nearest places api.
