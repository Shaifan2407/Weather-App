![image](https://github.com/Shaifan2407/Weather-App/assets/108326795/9e21fef1-96cb-497b-a1f0-275188a8d784)

# Weather App

This is a simple web application that fetches current weather data for a specified city using the OpenWeatherMap API.

## Features

- Displays current temperature, humidity, and wind speed for the specified city.
- Provides visual representation of weather conditions with corresponding weather icons.
- Gracefully handles error cases when an invalid city name is entered.

## Technologies Used

- **HTML:** Provides the structure and layout of the web application.
- **CSS:** Styles the application for an attractive user interface.
- **JavaScript:** Fetches data from the OpenWeatherMap API and updates the UI dynamically.

## Setup

1. **Clone the repository:**
## Using the Application

### Open the Application:

1. Navigate to the project directory.

2. Open the `index.html` file in your web browser.

### Search for a City:

- Enter the name of the city you want to check the weather for in the search input field.

- Click the search button or press Enter to fetch and display the weather data for the specified city.

# API Key

This application uses the OpenWeatherMap API to fetch weather data. You need to provide your API key in the `app.js` file. If you don't have an API key, you can obtain one by signing up at [OpenWeatherMap](https://openweathermap.org/api).

Replace the placeholder `apiKey` variable in `app.js` with your actual API key:

```javascript
const apiKey = "your-api-key";

