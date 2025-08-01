# Shafaf Air PK 🌬️

A comprehensive air quality monitoring Flutter application for Pakistan, providing real-time air quality data, weather information, and environmental news.

## Features

### 🌟 Core Features
- **Real-time Air Quality Index (AQI)** monitoring
- **Location-based air quality** data for Pakistani cities
- **Weather information** with current conditions
- **Environmental news** and updates
- **Interactive charts** and data visualization
- **Dark/Light theme** support
- **Offline data** caching

### 📱 User Interface
- **Modern Material Design** with custom air-themed colors
- **Responsive layout** for all screen sizes
- **Smooth animations** and transitions
- **Intuitive navigation** with bottom navigation
- **Beautiful charts** using fl_chart
- **Loading animations** with shimmer effects

### 🗺️ Location Services
- **GPS location** detection
- **Manual city selection** from Pakistan cities list
- **Geocoding** for address lookup
- **Permission handling** for location access

### 📊 Data Visualization
- **AQI charts** with historical data
- **Weather charts** and forecasts
- **Interactive graphs** for air quality trends
- **Real-time updates** with HTTP polling

## Screenshots

*[Add screenshots of your app here]*

## Tech Stack

- **Framework**: Flutter 3.7+
- **Language**: Dart
- **State Management**: ValueNotifier
- **UI Components**: Material Design, Google Fonts
- **Charts**: fl_chart
- **HTTP Client**: http package
- **Location Services**: geolocator, geocoding
- **Local Storage**: shared_preferences
- **Environment Variables**: flutter_dotenv
- **Date/Time**: intl package
- **Loading Effects**: shimmer
- **RSS Feeds**: dart_rss
- **Permissions**: permission_handler
- **Connectivity**: connectivity_plus
- **URL Handling**: url_launcher

## Getting Started

### Prerequisites
- Flutter SDK (3.7.0 or higher)
- Dart SDK
- Android Studio / VS Code
- Git

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HassanRaza0302/shafaf-air.git
   cd shafaf-air
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory
   - Add your API keys:
     ```
     AIR_QUALITY_API_KEY=your_api_key_here
     WEATHER_API_KEY=your_weather_api_key_here
     ```

4. **Run the app**:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/                   # Data models
│   ├── air_quality_data.dart
│   └── pakistan_cities.dart
├── services/                 # API and business logic
│   ├── air_quality_service.dart
│   ├── location_service.dart
│   └── news_service.dart
├── config/                   # Configuration files
│   └── api_config.dart
├── screens/                  # UI screens
├── widgets/                  # Reusable widgets
└── utils/                    # Utility functions
```

## API Integration

The app integrates with multiple APIs:
- **Air Quality API** for real-time AQI data
- **Weather API** for meteorological data
- **Geocoding API** for location services
- **RSS Feeds** for environmental news

## Features in Detail

### Air Quality Monitoring
- Real-time AQI values for Pakistani cities
- Historical data visualization
- Air quality alerts and notifications
- Color-coded AQI levels

### Weather Information
- Current weather conditions
- Temperature, humidity, wind speed
- Weather forecasts
- Location-based weather data

### News and Updates
- Environmental news feed
- Air quality alerts
- Government notifications
- Health advisories

### User Experience
- Intuitive navigation
- Smooth animations
- Offline functionality
- Data caching
- Theme switching

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Development

### Building for Production
```bash
# Android
flutter build apk --release

# iOS
flutter build ios --release

# Web
flutter build web --release
```

### Testing
```bash
flutter test
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Flutter team for the amazing framework
- Air quality data providers
- Weather API services
- Open source community

## Contact

- **Developer**: Hassan Raza
- **GitHub**: [@HassanRaza0302](https://github.com/HassanRaza0302)
- **Project**: [Shafaf Air PK](https://github.com/HassanRaza0302/shafaf-air)

---

**Breathe clean air, stay informed!** 🌱
