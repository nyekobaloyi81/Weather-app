# Weather App
https://nyekobaloyi81.github.io/Weather-app/

<img width="575" height="515" alt="weather" src="https://github.com/user-attachments/assets/8726ee15-9d55-4fc1-84cc-45110f99d024" />


A lightweight weather dashboard built with HTML, CSS, and vanilla JavaScript. Search for a city to see its current conditions, then switch between Celsius and Fahrenheit. City suggestions help distinguish places with the same name.

## Features

- Current temperature, daily minimum and maximum, and wind speed
- City suggestions while typing, with keyboard navigation
- Weather-specific icons and animated backgrounds
- Celsius/Fahrenheit conversion

## Getting Started

1. Create an API key with [OpenWeather](https://openweathermap.org/api).
2. Set the key as `API_KEY` in `script.js`. The key needs access to the Current Weather and Geocoding APIs.
3. From the project folder, start a local web server:

   ```sh
   python -m http.server 8000
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.
