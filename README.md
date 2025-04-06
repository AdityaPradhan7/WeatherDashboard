# Global Weather Dashboard 🌍⛅

🔗 **Live Demo**: _[Coming Soon / Add your Vercel or GitHub Pages link here]_  
📦 **Download Syncloop Package**: [Click here](https://github.com/AdityaPradhan7/WeatherDashboard/blob/main/Syncloop%20package.zip)  
💻 **GitHub Repository**: [Global Weather Dashboard](https://github.com/AdityaPradhan7/WeatherDashboard)

---

## 📄 Description  
Global Weather Dashboard is a browser-based, user-friendly platform that enables users to search for any city via text or voice and receive real-time weather information, air quality levels, local time, forecast, historical data, and interactive map overlays. This app fetches accurate data from multiple external APIs and presents it in an organized and visually appealing interface.

---

## ✨ Key Features

1. **Search Functionality**
   - Text input-based city search
   - Voice input using the browser’s built-in **Web Speech API**
   - Auto-fills city name from a phrase like:  
     _"Tell me the weather in **Tokyo**"_ → Extracts and searches for **Tokyo**

2. **Location & Time Info**
   - Converts city name to latitude and longitude using **OpenWeatherMap Geocoding API**
   - Displays local time using **TimeZoneDB API** (via Syncloop)

3. **Current Weather + Forecast**
   - Real-time weather data via **OpenWeatherMap Current Weather API** (via Syncloop)
   - 6-day weather forecast with temperature, humidity, weather conditions, and icons

4. **Air Quality**
   - Live air quality data using **OpenWeatherMap Air Pollution API** (via Syncloop)

5. **Historical Weather**
   - Past weather data based on date range using **Open-Meteo Historical Weather API**
   - Max and min temperatures displayed daily

6. **Interactive Map**
   - Embedded **Leaflet.js map**
   - **OpenStreetMap** as base map
   - **OpenWeatherMap Temperature Overlay**
   - **AQICN Air Quality Overlay**

---

## 🧰 Tech Stack

### Frontend
- **HTML5**: Structure
- **CSS3**: Styling and layout
- **JavaScript (Vanilla)**: Functionality and API integration
- **Granim.js**: Dynamic background transitions (Day/Night effect)
- **Leaflet.js**: Interactive map rendering

### Voice Input
- **Web Speech API**: Native browser API for voice-to-text recognition

### API Services
- **OpenWeatherMap APIs**:  
  - Geocoding API  
  - Current Weather API *(via Syncloop)*  
  - 6-Day Forecast API *(via Syncloop)*  
  - Air Pollution API *(via Syncloop)*
- **TimeZoneDB API** *(via Syncloop)*
- **Open-Meteo Archive API**
- **AQICN Overlay** (for map air quality layers)

### API Management
- **Syncloop Platform**  
  Unified API endpoint that bundles multiple services, making code cleaner and easier to manage.

📦 [Download Syncloop Package](https://github.com/AdityaPradhan7/WeatherDashboard/blob/main/Syncloop%20package.zip)

---

## 🚧 Approach

### 1. Planning and Design
- Decided core modules: Search, Weather Data, Air Quality, Historical Data, Map
- Focused on simplicity, accessibility, and responsiveness
- Used clean layout and dynamic visual elements like Granim.js and Leaflet

### 2. Frontend Development
- Built in pure HTML, CSS, and JavaScript
- Integrated Granim.js for dynamic background transitions
- Implemented voice recognition via Web Speech API

### 3. API Integration
- Used OpenWeatherMap’s Geocoding API to convert city names into lat/lon
- Fetched time, weather, and air data from Syncloop-managed APIs
- Integrated Open-Meteo and AQICN overlays separately

### 4. Testing and Debugging
- Ensured compatibility on different screen sizes and browsers
- Validated voice input, API responses, and data visualizations
- Debugged UI edge cases and error handling

### 5. Deployment
- Deployed frontend on **Vercel** for fast and global delivery
- Secured API keys by using backend routing *(initially)* and later replaced with Syncloop

---

## ✅ Final Summary

Global Weather Dashboard is a lightweight yet feature-rich web app that enables users to get localized weather data, forecasts, air pollution insights, and historical trends with a smooth and intuitive interface. The project emphasizes clarity, performance, and easy scalability — all built with no framework.

---

## 🚀 Future Enhancements

- Add **responsive mobile design**
- Add **unit switcher** (°C ↔ °F)
- Use **local storage** to save user preferences
- Add **weather-based recommendations** (e.g., "Carry an umbrella today!")

---
