Weather App
A simple weather application built using HTML, CSS, and JavaScript. The app allows users to search for the current weather of a city, displaying temperature, humidity, wind speed, and an appropriate weather icon based on the weather condition.

Features
Search for city weather: Enter the name of a city to get the current weather details.
Weather information displayed:
Temperature (°C)
Humidity (%)
Wind Speed (km/h)
Dynamic weather icons based on the weather condition (Rain, Clouds, Clear, etc.)
Error handling: Displays an error message if an invalid city name is entered.
Tech Stack
HTML: Structure of the app.
CSS: Styling for the app’s user interface.
JavaScript: Functionality for fetching weather data from OpenWeatherMap API and handling user input.
API Integration
This app uses the OpenWeatherMap API to retrieve weather data. You can sign up on their website to get your own API key if you'd like to use this project with a different key.

API Key
Replace the apiKey variable in the script.js section with your own OpenWeatherMap API key:

javascript
Copy code
const apiKey = "YOUR_API_KEY_HERE";
How to Use
Clone or download the repository.
Open index.html in your browser.
Enter a city name in the search box and click the search button.
View the weather information for that city.
Folder Structure
index.html: The main HTML file containing the structure and JavaScript.
style.css: The stylesheet for the app’s styling.
images/: Folder containing weather icons (e.g., clear, rain, cloud, etc.).
README.md: This documentation.


