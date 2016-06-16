# Untappd Beer Drinking History

#### Downloading, analyzing, and visualizing your Untappd beer drinking check-in history.

  1. Download your check-in data with [download_untappd_checkins.ipynb](download_untappd_checkins.ipynb)
  2. Download the details of those check-ins (beer, brewery, and venue details) with [download_untappd_details.ipynb](download_untappd_details.ipynb)
  3. Geocode all the breweries whose beer you've checked-in with [geocode_untappd_breweries.ipynb](geocode_untappd_breweries.ipynb)
  4. Get the check-in venue's timezone (so you know when you drank it, local time) with [get_untappd_venue_timezone.ipynb](get_untappd_venue_timezone.ipynb)
  5. Finally analyze, visualize, and map these data with [untappd_analysis.ipynb](untappd_analysis.ipynb)

Untappd's API is nearly useless due to its limited functionality and conservative rate limits, so this project
uses the Selenium browser automation Python package to automate the Google Chrome browser to collect your
Untappd check-in history. You will also need a Google Maps timezone API key to get the venues' timezones.