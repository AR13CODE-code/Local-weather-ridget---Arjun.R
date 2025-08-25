# Local-weather-ridget---Arjun.R
Mini project: simple weather ridget in kotlin using open weather app
# 🌦 Local Weather Widget  
Mini Project by Arjun – 1st Year B.Tech  

## Introduction  
I wanted to build a small weather widget app which shows live weather of the user’s city.  
Instead of opening Google every time, this app gives a simple view with icons and background colors.  

## Features  
- Shows temperature, humidity, and weather condition  
- Uses weather icons ☀️ 🌧 ☁️  
- Caches last data for offline use  
- Dynamic backgrounds (sunny = yellow, rainy = blue, cloudy = grey)  

## Tech Stack  
- Kotlin (Android)  
- OpenWeatherMap API  
- SharedPreferences (local storage)  

## Code Snippet  
```kotlin
val url = "https://api.openweathermap.org/data/2.5/weather?q=Chennai&appid=YOUR_API_KEY&units=metric"
