# Weather App

A simple weather application built with **React**, **TypeScript**, and **Axios**.  
It allows users to search for any city or use their device's location to display the current weather and forecast for specific hours.

---

## Features

- Search for any city and view weather information.
- Detect device location and display local weather automatically.
- Display current temperature, weather condition, and icon.
- Show forecast for specific hours (13:00, 14:00, 15:00, 16:00).
- Mobile-first responsive design with blurred background effect.

---

## Screenshots

![Search Page](./screenshots/search-page.png)  
![Weather Page](./screenshots/weather-page.png)

---

## Installation

1. Clone this repository:
```bash
git clone https://github.com/igorcbtr/weather-app-ts.git
2. Navigate to the project folder:

cd weather-app-ts


3. Install dependencies:

npm install


4. Create a .env file in the root and add your WeatherAPI key:

VITE_WEATHER_API_KEY=your_api_key_here


5. Start the development server:

npm run dev

Usage

1 . On the main page, type the city name in the input box and press Enter, or click Get Device Location to detect your location automatically.

2 . You will be redirected to the weather page showing:

Current temperature and weather condition.

Forecast for the next hours (13:00–16:00).

Technologies Used

React + TypeScript

Axios for API requests

React Router for navigation

WeatherAPI for weather data

CSS for styling

API Reference

WeatherAPI documentation: https://www.weatherapi.com/docs/

Current Weather: /v1/current.json

Forecast: /v1/forecast.json

Folder Structure
src/
├─ assets/          # Images and icons
├─ components/      # React components (SearchContainer, WeatherContainer)
├─ pages/           # Page components
├─ App.tsx          # Main App
├─ index.css        # Global styles

Notes

Make sure your browser allows geolocation access for the device location feature.

This app is designed mobile-first and supports responsive layouts.

License

This project is open source and available under the MIT License.
