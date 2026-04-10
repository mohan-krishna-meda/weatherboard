# WeatherBoard – Animated Weather Dashboard

> Search any city and get an instant animated weather dashboard with a 5-day forecast and temperature trend chart.

## 🚀 Live Demo
[**Try it here →**](https://mohan-krishna-meda.github.io/weatherboard)

## ✨ Features
- Search weather for any city worldwide
- Current conditions: temperature, humidity, wind speed, visibility, feels-like
- Animated 5-day forecast cards with hover effects
- Temperature trend bar chart
- Color-coded temperatures (blue = cool, orange/red = hot)
- Beautiful dark-mode UI

## 🛠 Tech Stack
- HTML5, CSS3, Vanilla JavaScript
- OpenWeatherMap API (free tier) — easy to connect
- No framework, no build step

## 🔑 Connect Real Weather Data
1. Get a free API key at [openweathermap.org](https://openweathermap.org/api)
2. In `index.html`, replace the `loadWeather()` function's demo block with:
```javascript
const API_KEY = 'YOUR_API_KEY_HERE';
const res = await fetch(
  `https://api.openweathermap.org/data/2.5/forecast?q=${city}&appid=${API_KEY}&units=metric`
);
const data = await res.json();
```

## 📦 Run Locally
```bash
git clone https://github.com/YOUR_USERNAME/weatherboard.git
cd weatherboard
open index.html
```

## 🌐 Deploy to GitHub Pages
1. Push to GitHub
2. **Settings → Pages → Source → main branch**
3. Live at: `https://YOUR_USERNAME.github.io/weatherboard`

---
Made by Mohan Krishna Meda
