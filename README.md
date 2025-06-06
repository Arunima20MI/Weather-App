# 🌤️ Weather Forecast App (Tkinter + OpenWeatherMap API)

A simple and user-friendly desktop application that displays real-time weather information for any Indian city — or auto-detects your location using IP geolocation. Built using Python, Tkinter, OpenWeatherMap API, and geocoder.

......

## 📌 Features

- 🌍 **Auto-detect location** based on IP (or enter city manually)
- 🌡️ Current temperature in °C
- 🌤️ Weather description
- 💧 Humidity level
- 🌬️ Wind speed
- 📝 Logs weather queries to 'weather_log.txt'

......

## 🚀 How It Works

1. Enter a city name or leave it blank to detect your city automatically.
2. Click "Get Weather".
3. The app fetches real-time data from OpenWeatherMap and displays it.
4. Every request is logged with a timestamp in 'weather_log.txt'.

......

## 🛠️ Technologies Used

- Python 3
- Tkinter (GUI)
- 'requests' (API calls)
- 'geocoder' (IP-based location)
- OpenWeatherMap API

......

## 🔧 Setup Instructions

1. Clone the repository:
   git clone https://github.com/Arunima20MI/weather-forecast-app.git
   cd weather-forecast-app
3. Install required packages:
    pip install requests geocoder
4. Replace the API key with your own:
  --> Sign up at OpenWeatherMap to get an API key.
  --> Update the API_KEY variable in the code.
5. Run the app:
  python weather_app.py

