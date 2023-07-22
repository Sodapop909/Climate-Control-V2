# Climate-Control-V2

# Weather Application

This is a simple weather web application that allows users to search for the current weather in a particular city. It displays the temperature, weather description, humidity, wind speed, and icon representing the weather conditions for the searched city.

## Features

- Search for weather data by city name
- Displays temperature in Celsius and Fahrenheit
- Shows weather description, humidity, and wind speed
- Dynamic weather icon that changes based on weather conditions 
- Background image of the city fetched from Unsplash API
- Clean and responsive UI

## Technologies Used

- HTML
- CSS
- JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data
- [Unsplash API](https://unsplash.com/developers) to fetch city images

## Usage

- User can search for a city name in the input field and click the Search button 
- Weather data for the searched city is fetched from OpenWeatherMap API
- An image of the city is fetched from Unsplash API and set as the background
- Page dynamically updates to display weather details for the searched city

The app also displays weather data for a default city (Washington DC) on initial load.

## Room for Improvement

Some ways this app could be improved:

- Add autocomplete suggestions for the search box
- Store previously searched cities and show history
- Add a visual graph for weather data over multiple days
- Allow user to switch between Celsius and Fahrenheit

## License

This project is open source and available under the [MIT License](LICENSE).
