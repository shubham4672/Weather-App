# Weather App Project

This project is a weather application built using HTML, CSS, and JavaScript, utilizing the OpenWeather API to fetch and display current weather data for any city/country.

## Features

- Search for current weather by city name.
- Display temperature, weather conditions, humidity, and wind speed.
- Responsive design to ensure usability on various devices.
- Friendly user interface with modern design.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/shubham4672/Weather-App
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Weather-App
    ```

3. **Open `index.html` in your browser:**

    ```bash
    open index.html
    ```

## Usage

1. **Get an API Key:**

    Sign up at [OpenWeather](https://openweathermap.org/api) and get your API key.

2. **Set up your API Key:**

    Open the `app.js` file in a text editor and replace `'API_KEY'` with your actual API key:

    ```javascript
    const apiKey = 'API_KEY';
    ```

3. **Run the Application:**

    Open `index.html` in your preferred web browser. You can now search for the weather in any city.

## Project Structure

```plaintext
weather-app/
│
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
├── app.js              # JavaScript file for functionality
├── README.md           # This README file
└── images/             # Folder for images and other assets
