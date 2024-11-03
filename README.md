# Country Information, Map Viewer, and Weather 

This project is a simple web application that allows users to select a country from a dropdown list organized by continent and get key information about the country, including current weather conditions. Users can view details such as the country’s capital city, population, flag, and an interactive map displaying the selected country's location. Additionally, real-time weather information, such as air temperature and conditions, is provided for each selected country.

## Features
- **Country Selector**: Dropdown list of countries organized by continent for easy navigation.
- **Country Information**: Displays the selected country's capital, population, and flag.
- **Interactive Map**: Uses [Leaflet.js](https://leafletjs.com/) to show the selected country’s location on a map with a marker.
- **Current Weather Conditions**: Fetches real-time weather data, including temperature and weather conditions, using the [WeatherAPI](https://www.weatherapi.com/).

## Demo
A live demo of the project can be accessed here: [Demo Link (if hosted)]

## Tech Stack
- **HTML, CSS, JavaScript**: Core web technologies for building the interface.
- **Leaflet.js**: JavaScript library for creating interactive maps.
- **RestCountries API**: Fetches country information (capital, population, flag).
- **WeatherAPI**: Provides current weather information based on country coordinates.

## How to Use
1. Select a country from the dropdown menu.
2. Click the “Give Info” button.
3. The following details are displayed:
   - **Country Info**: Shows the capital, population, and flag.
   - **Weather Info**: Displays current air temperature and weather conditions with an icon.
   - **Map**: Shows the country’s location on an interactive map.
4. The map will zoom in to the selected country, and a marker will be placed at its location.
