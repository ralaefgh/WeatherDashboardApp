# Weather Dashboard App

A sleek, responsive web application that provides real‑time weather information and a 5‑day forecast for cities around the world. Powered by the Open‑Meteo API.

---

## Table of Contents

- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Running Locally](#running-locally)  
- [Usage](#usage)  
- [Configuration](#configuration)   
- [Technologies Used](#technologies-used)
- [Demo](#demo)
- [License](#license)  

---

## Features

- **Current Weather:** Displays temperature (°C & °F), condition, wind speed & direction, and day/night indicator.  
- **Metrics Grid:** Cards for wind speed, wind direction (with compass), max/min temperatures (with descriptions), rain chance & amount (with progress bars and intensity labels).  
- **5‑Day Forecast:** Forecast cards showing day‑of‑week, high & low temps, precipitation probability, and weather icons.  
- **City Search & Selector:** Type to search any city (via Open‑Meteo geocoding API) or choose from popular presets.  
- **Responsive Design:** Adapts beautifully from mobile up to desktop.  
- **Graceful Error Handling:** User‑friendly error messages and retry option.  

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge).  
- Internet connection (for API fetches).  

### Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/enhanced-weather-dashboard.git
   cd enhanced-weather-dashboard
   ```

### Running Locally

1. Simply open `index.html` directly.  
2. Search for a city or select from the dropdown.  
3. View real‑time weather and forecast—auto‑updates on each search.  

---

## Usage

- **Search:** Enter a city name and press Enter or click 🔍.  
- **Popular Cities:** Choose from the dropdown to instantly load weather.  
- **Retry:** If data fails to load, click “Try Again” in the error panel.  

---

## Configuration

No API key is required. This app uses the **Open‑Meteo** free APIs:

- **Geocoding:** `https://geocoding-api.open-meteo.com/v1/search`  
- **Weather:** `https://api.open-meteo.com/v1/forecast`  

If you wish to swap in another API or add keys, modify the `fetchWeatherForCity`, `getCityCoordinates`, and `fetchWeatherData` functions in `index.html`.

---

## Technologies Used

- **HTML5** & **CSS3** (Flexbox, Grid, custom animations)  
- **Vanilla JavaScript** (ES6+, Fetch API, DOM manipulation)  
- **Open‑Meteo APIs** for geocoding & forecasting  
- **No build tools**—zero dependencies, lightning‑fast startup  

---

## Demo

- https://ralaefgh.github.io/WeatherDashboardApp/

---

## License

- **CC BY-NC-SA 4.0**
