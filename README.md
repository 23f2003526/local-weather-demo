# City Weather — Open‑Meteo

A lightweight single-page app that shows current weather and a 3‑day forecast for any city using the Open‑Meteo APIs. Fully client-side and ideal for GitHub Pages.

## Features
- Current conditions: temperature, humidity, wind, and condition text.
- 3‑day forecast with min/max temperatures and small weather icons.
- Toggle between Celsius and Fahrenheit at any time.
- Clean, responsive UI; no backend required.

## Usage
1. Open index.html locally or via GitHub Pages.
2. Enter a city name and click Get Weather.
3. View the current weather and the 3‑day forecast.
4. Switch units using the °C/°F toggle; values update instantly.

## Tech
- Open‑Meteo Geocoding API for city → coordinates.
- Open‑Meteo Forecast API for current and daily data.
- Pure client-side HTML/CSS/JS (Bootstrap via CDN).

## Deployment (GitHub Pages)
- Commit index.html and README.md to your repository’s default branch.
- Enable GitHub Pages in repository settings, using the branch’s root.
- Visit the published URL to use the app.

## Privacy
All requests go directly from your browser to Open‑Meteo; no data is stored on a server. The app may store your last searched city in localStorage for convenience.

## License
This project is released under the MIT License. See the License section text here for terms.