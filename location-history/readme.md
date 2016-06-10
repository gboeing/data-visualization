# Visualizing location history

This project combines my location history data from Google, Foursquare, and a simple
spreadsheet of pre-2012 travels. It geocodes and reverse-geocodes the data, and produces
static and interactive maps of everywhere I've been.

To download and visualize just Foursquare/Swarm check-in history, check out [foursquare-location-history.ipynb](foursquare-location-history.ipynb). 
To download and visualize just Google location history, check out [google-location-history-simple.ipynb](google-location-history-simple.ipynb).

Otherwise, for the full process:
  1. I downloaded and processed my Foursquare/Swarm check-in history with [foursquare-location-history.ipynb](foursquare-location-history.ipynb)
  2. I downloaded and processed my Google location history:
    1. Downloaded my Google location history from [https://accounts.google.com/ServiceLogin?service=backup](https://accounts.google.com/ServiceLogin?service=backup)
    2. Reduced the size of the Google location history spatial data set with [google-location-history-cluster.ipynb](google-location-history-cluster.ipynb)
    3. Reverse-geocoded the lat/long Google location history data to neighborhood, city, state, country with [google-location-history-reverse-geocode.ipynb](google-location-history-reverse-geocode.ipynb)
  3. I created a simple spreadsheet of pre-2012 travels and geocoded it with [previous-travels-history-geocode.ipynb](previous-travels-history-geocode.ipynb)
  4. Combine the Foursquare check-in history, the Google location history, and the previous travels data and visualize with [visualize-location-history.ipynb](visualize-location-history.ipynb)
  5. View the interactive leaflet map with [leaflet](leaflet)

For a simple demonstration of parsing, visualizing, and mapping your full Google location history with Python, see [google-location-history-simple.ipynb](google-location-history-simple.ipynb)
