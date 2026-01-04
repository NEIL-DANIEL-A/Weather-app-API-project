# 🌦️ Weather App (No API Key)

## Project Description

This is a simple Weather Application built using HTML, CSS, and JavaScript.
The app fetches real-time weather data using a public REST API that does not require any API key.

Users can enter a city name and view the current temperature and wind speed.

## Features

Search weather by city name

Displays:

-> Temperature (°C)
        
-> Wind speed (km/h)

Uses key-less public APIs

Beginner-friendly and lightweight

No backend required

## Technologies Used

HTML – Structure of the app

CSS – Styling and layout

JavaScript – Logic and API calls

REST API – Fetching weather data

## APIs Used

Open-Meteo Geocoding API
Used to convert city name into latitude and longitude.

Open-Meteo Weather API
Used to fetch current weather data using coordinates.

Both APIs are free and do not require authentication.

## Project Structure
weather-app/
|── index.html
│── style.css
│── script.js
│── README.md

## How It Works

User enters a city name

App fetches latitude & longitude of the city

Weather data is fetched using coordinates

Current weather details are displayed on the screen
