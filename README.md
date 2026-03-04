# Weather_Report_AutoUpdate
 interactive weather-forecast dashboard to monitor multi-city conditions and short-term forecasts.
# 🌤️ Modern Weather Dashboard

> A comprehensive, dark-mode weather analytics platform providing real-time climate data, air quality insights, and predictive meteorological charts.

![Dashboard Preview](https://i.imgur.com/YOUR_IMAGE_LINK_HERE.png) 

## 🚀 About The Project

This application offers a centralized hub for all weather-related data. Designed with a sleek, dark aesthetic, it visualizes complex data sets—such as Air Quality Index (AQI) and hourly temperature trends—into easy-to-read cards and interactive graphs.

It supports multi-city tracking, allowing users to instantly switch between Noida, Mumbai, and Pune without reloading the page.

## ✨ Key Features

- **Real-Time Current Weather:** Display of current temperature, condition (e.g., Mist), and last updated timestamp.
- **7-Day Forecast:** Predicted daily temperatures and weather icons for the upcoming week.
- **Temperature Trend Graph:** An interactive line chart visualizing daily highs and lows.
- **Air Quality Index (AQI) Visualizer:** 
  - Circular gauge indicating health status (e.g., "Unhealthy").
  - Detailed breakdown of specific pollutants: CO, PM10, NO2, PM2.5, O3, and SO2.
- **Precipitation Analysis:** Bar charts predicting the chance of rain for every day.
- **Sunlight Tracking:** Accurate sunrise and sunset times for the selected location.
- **Granular Metrics:** Deep-dive data including:
  - Visibility (km/miles)
  - Humidity (%)
  - Wind Speed
  - UV Index
  - Atmospheric Pressure
- **City Switcher:** Quick navigation pills to toggle between saved favorite cities.

## 📥 Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
Navigate to the project directory:
Bash

cd weather-dashboard
Install dependencies:
Bash

npm install
# or
yarn install
Set up your environment variables:
Copy .env.example to .env and add your API keys.
Bash

VITE_WEATHER_API_KEY=your_api_key_here
Start the development server:
Bash

npm start
🔑 API Integration
This dashboard consumes weather data endpoints to render the following views:

One Call API / Current Weather: For the top-left card (Temp: 34.3°C, Condition: Mist).
Forecast API: For the top strip (Daily temps) and the central line graph.
Air Quality API: To fetch the raw numbers for the center-bottom circular gauge.
Geocoding: To handle the city switching functionality.
Design Philosophy
Dark Mode First: Reduced eye strain for users checking weather late at night or early morning.
Card-Based Layout: Modular information architecture allows for easy scanning of data.
Color Coded Alerts: Uses red/orange hues for alerts (like "Unhealthy" AQI) and cool blues for neutral data.
📄 License
Distributed under the MIT License. See LICENSE.txt for more information.

👤 Author
Abhay Bhagat 
[[LinkedIn Profile Link]
https://www.linkedin.com/in/abhay-bhagat-03588a25b/
