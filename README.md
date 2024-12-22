# Weather App 🌤️

Welcome to the Weather App! This Python-based GUI application allows you to search for the current weather conditions in any city across the globe. Using the OpenWeatherMap API, you can get live updates on temperature, humidity, wind speed, and more.

## Features 🚀

- **Real-Time Weather Information**: Get the current weather conditions for any city.
- **Temperature and Feels Like**: Displays both temperature and how it feels.
- **Detailed Info**: View wind speed, humidity, description, and pressure.
- **Interactive Search**: Simple and user-friendly search bar for entering city names.
- **Time Zone Awareness**: Displays local time for the searched city.

## Prerequisites ✅

Before you run the application, make sure you have the following installed:

- Python 3.8+
- Required Python libraries:
  - `tkinter`
  - `geopy`
  - `timezonefinder`
  - `pytz`
  - `requests`

You can install the required libraries using pip:

```bash
pip install geopy timezonefinder pytz requests
```

## How to Run 🏃‍♂️

1. Clone this repository or download the source code.

2. Place the following required image files in the same directory as the script:
   - `logo.png` (App logo)
   - `search.png` (Search bar background)
   - `search_icon.png` (Search button icon)
   - `box.png` (Bottom box design)

3. Replace the placeholder `##` in the API URL with your OpenWeatherMap API key. 🔑

   ```python
   api = "https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid=YOUR_API_KEY"
   ```

4. Run the script:

   ```bash
   python weather_app.py
   ```

5. Enter a city name in the search bar and press the search button to view the weather details.

## Application Structure 🏗️

### Main Components:

- **Search Bar**: Enter the city name to search for weather data.
- **Weather Details**: Displays temperature, conditions, wind, humidity, description, and pressure.
- **Time Display**: Shows the local time of the searched city.

### Libraries Used:

- **`tkinter`**: For building the graphical user interface.
- **`geopy`**: To fetch geographic location details.
- **`timezonefinder`**: For determining the time zone.
- **`pytz`**: For time zone management.
- **`requests`**: To fetch weather data from the OpenWeatherMap API.



## Acknowledgments 🙌

- **OpenWeatherMap API** for providing weather data.
- **Geopy & TimezoneFinder** for location and timezone support.

---

Enjoy using the Weather App! ☀️🌧️🌈

