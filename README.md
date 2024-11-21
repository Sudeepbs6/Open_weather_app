# Weather App

A modern Android weather application using OpenWeatherMap API for real-time weather data.

## Features
- US city weather search
- Auto-location detection  
- Last searched city auto-load
- Real-time weather display
- Weather icons
- Offline support

## Tech Stack
- Kotlin & Java
- MVVM Architecture
- Retrofit
- JUnit
- Jetpack Compose
- Kotlin Coroutines  
- Hilt
- Jetpack Navigation
- Room Database
- Mockito

## Setup
1. Clone repository
2. Get API key from OpenWeatherMap
3. Add to local.properties:
```bash
WEATHER_API_KEY=your_api_key_here

##Architecture

app/
├─ data/
│  ├─ remote/
│  ├─ local/
│  └─ repository/
├─ domain/
│  ├─ model/
│  └─ usecase/
├─ presentation/
│  ├─ ui/
│  └─ viewmodel/
└─ di/
