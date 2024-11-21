                                                                        Weather App


A modern Android weather application that allows users to check weather conditions for US cities. The app uses the OpenWeatherMap API to fetch real-time weather data and supports both manual city search and location-based weather information.
Features

Search weather by US city name
Auto-location detection (with user permission)
Last searched city auto-load
Real-time weather conditions display
Weather icon visualization
Offline support with data caching

Tech Stack
Core Technologies

Kotlin & Java
MVVM Architecture
Retrofit for network calls
JUnit for unit testing

Additional Features

Jetpack Compose for UI
Kotlin Coroutines for async operations
Hilt for dependency injection
Jetpack Navigation
Room Database for local storage
Mockito for testing

Setup

Clone the repository
Get an API key from OpenWeatherMap
Add your API key in local.properties:
CopyWEATHER_API_KEY=your_api_key_here

Build and run the project

Architecture
The app follows MVVM architecture with clean code principles:
Copyapp/
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
Testing

Unit tests using JUnit and Mockito
UI tests using Espresso
Run tests using:
Copy./gradlew test


Permissions

Internet access
Location access (optional)

API Reference
The app uses OpenWeatherMap API endpoints:

Weather by city name: /data/2.5/weather?q={city}
Weather by coordinates: /data/2.5/weather?lat={lat}&lon={lon}

Contributing

Fork the repository
Create a feature branch
Commit changes
Push to the branch
Open a pull request
