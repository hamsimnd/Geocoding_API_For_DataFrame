# Geocoding_API_For_DataFrame

# Overview
In this program, the data of the customs office addresses given in xlsx format (addresses are in this link. https://ec.europa.eu/taxation\_customs/dds2/rd/rd\_consultation\_reference.jsp?Lang=en) using the Geocoding API link in the Google Console It has been prepared for the purpose of parsing it and making it in a for loop into the dataframe read over excel. It is planned to mark and visualize the relevant areas on the map in future studies.
## Installation
Just use ``pip``:

- pip install pandas
- pip install requests
## Configuration
- Set your Google API key here. 
- Even if using the free 2500 queries a day, its worth getting an API key since the rate limit is 50 / second.
- With API\_KEY = None, you will run into a 2 second delay every 10 requests or so.
- With a "Google Maps Geocoding API" key from <https://console.developers.google.com/apis/>,the daily limit will be 2500, but at a much faster rate.
