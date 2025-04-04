# Weather App 🌦️

A simple React-based weather application that provides **current weather details** and a **7-day forecast** for searched cities using the OpenWeatherMap API.

## Features 🚀
- 🌍 **Search for Cities** using the GeoDB API with autocomplete.
- ☀️ **Current Weather Display** with temperature, humidity, wind speed, and more.
- 📅 **7-Day Weather Forecast** with expandable details.
- 🎨 **Responsive & Clean UI** for an enhanced user experience.

## Tech Stack 🛠️
- **Frontend:** React.js
- **APIs:** OpenWeatherMap API, GeoDB Cities API
- **Styling:** CSS
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Project Structure 📂
weather-app/
│── src/
│ ├── components/
│ │ ├── current-weather/
│ │ │ ├── current-weather.js
│ │ │ ├── current-weather.css
│ │ ├── forecast/
│ │ │ ├── forecast.js
│ │ │ ├── forecast.css
│ │ ├── search/
│ │ │ ├── search.js
│ ├── api.js
│ ├── App.js
│ ├── App.css
│── public/
│ ├── index.html
│── package.json
│── README.md
│── .gitignore
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Install dependencies:
npm install
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
generate api key from 
WEATHER_API_KEY - https://home.openweathermap.org/users/sign_in
GEODB_API_KEY - https://rapidapi.com/hub

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

api.js
export const WEATHER_API_URL = "https://api.openweathermap.org/data/2.5";
export const WEATHER_API_KEY = "YOUR_OPENWEATHERMAP_API_KEY";

export const GEO_API_URL = "https://wft-geo-db.p.rapidapi.com/v1/geo";
export const geoApiOptions = {
  method: "GET",
  headers: {
    "X-RapidAPI-Key": "YOUR_GEODB_API_KEY",
    "X-RapidAPI-Host": "wft-geo-db.p.rapidapi.com",
  },
};
#   W e a t h e r - a p p  
 #   w e a t h e r - a p p  
 