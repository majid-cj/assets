### StakeWeatherApp
A mobile weather application built with React Native, allowing users to search for weather forecasts in various locations. The app provides current weather conditions, temperature, humidity, wind speed, and a multi-day forecast for the selected city.

### Table of Contents
- Features (#features)
- Screenshots (#screenshots)
- Tech Stack (#tech-stack)
- Installation (#installation)
- Usage (#usage)
- Project Structure (#project-structure)
- Dependencies (#dependencies)

### Features
- Search for weather forecasts by city name.
- Display current weather conditions, including temperature, humidity, and wind speed.
- Show a multi-day forecast (e.g., today, tomorrow, and the next few days).
- Provide detailed weather information, such as "feels like" temperature and time-based forecasts (morning, day).
- Support for recently searched cities for quick access.
- Dark mode theme for better user experience.


### Screenshots

![screen-recording](https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-recording.mp4)

#### Search Screen

<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-shot-1.png" alt="Alt Text" width="120" height="260">
<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-shot-2.png" alt="Alt Text" width="120" height="260">
<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-shot-3.png" alt="Alt Text" width="120" height="260">

#### Search Screen

<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-shot-4.png" alt="Alt Text" width="120" height="260">

#### Weather Forecast

<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/screen-shot-5.png" alt="Alt Text" width="120" height="260">

### Project Structure
The project follows a modular structure for better organization:

<img src="https://raw.githubusercontent.com/majid-cj/assets/refs/heads/master/screenshots/file-structure.png" alt="Alt Text" width="900" height="500">


### Dependencies
The app relies on the following key dependencies (as seen in the package.json snippet):
- "@react-native-firebase/analytics": "^21.12.2"
- "@react-native-firebase/app": "^21.12.2"
- "@react-navigation/native": "^7.0.18"
- "@react-navigation/native-stack": "^7.3.2"
- "axios": "^1.8.4"
- "expo": "~52.0.40"
- "expo-build-properties": "~0.13.2"
- "expo-dev-client": "~5.0.14"
- "i18next": "^24.2.3"
- "intl-pluralrules": "^2.0.1"
- "lottie-react-native": "^7.1.0"
- "react": "18.3.1"
- "react-i18next": "^15.4.1"
- "react-native": "0.76.7"
- "react-native-config": "^1.5.5"
- "react-native-dev-info": "^14.0.4"
- "react-native-fast-image": "^8.6.3"
- "react-native-get-random-values": "^1.11.0"
- "react-native-google-places-autocomplete": "^2.5.7"
- "react-native-mmkv": "^3.2.0"
- "react-native-safe-area-context": "^4.12.0"
- "react-native-screens": "^4.4.0"
- "react-native-svg": "15.8.0"
- "zustand": "^5.0.3"

### Usage
- Open the app on your device or emulator.
- On the home screen, use the search bar to look for a city (e.g., "Dubai").
- Select a city from the search results to view its weather forecast.
- Check the current weather, including temperature, humidity, wind speed, and a brief description
- Scroll to see the forecast for the next few days and detailed time-based weather (morning, day).
- Access recently searched cities from the "Recently Searched Cities" section for quick lookups.

