# Weather Forecast App

A modern, responsive web app to view real-time weather and 5-day forecasts for any city, with integrated city maps.

## Features
- 🌤️ Current weather details (temperature, humidity, wind, highs/lows)
- 📅 5-day forecast in a clean, compact grid (on `forecast.html`)
- 🗺️ City map using Google Maps Static API
- 🔍 Fast city search with instant feedback
- ⚡ Beautiful, mobile-friendly UI (Tailwind CSS)

## Setup
1. **Clone this repo**
2. **Get API keys:**
   - [OpenWeatherMap API Key](https://openweathermap.org/api)
   - [Google Maps Static API Key](https://console.cloud.google.com/apis/library/static-maps-backend.googleapis.com)
3. **Enable APIs:**
   - Enable "Maps Static API" in Google Cloud Console
   - Enable billing for Google Maps if required
4. **Add your API keys** in `index.html` and `forecast.html` (replace the placeholders)
5. **(Optional) Restrict your Google Maps API key** to your production domain for security

## Usage
- Open `index.html` in your browser
- Search for any city to view weather and map
- Click "View Detailed Forecast" for the 5-day forecast

## Deployment
- Host the files on any static web server (Netlify, Vercel, GitHub Pages, etc.)
- For production, restrict your Google Maps API key by HTTP referrer to your domain

---

**Built with:**
- HTML, JavaScript, Tailwind CSS
- OpenWeatherMap API
- Google Maps Static API
