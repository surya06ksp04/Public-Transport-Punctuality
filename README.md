# Public Transport Punctuality Tracker

A Python-based data analysis tool that tracks real-time bus/train arrivals, analyzes delays, and correlates them with weather conditions to identify patterns and suggest improvements.

This project integrates:
- **TransportAPI** for real-time public transport data.
- **OpenWeatherMap API** for live weather conditions.

---

## Features
- Fetches **real-time transport data** (bus/train) from TransportAPI.
- Integrates **live weather data** from OpenWeatherMap.
- Calculates and visualizes **delay patterns**.
- Identifies **top delay causes** (weather or transport type).
- Provides **actionable suggestions** to improve punctuality.
- Keeps API keys safe using a `.env` file.

---

## Technologies Used
- **Python 3.x**
- [pandas](https://pandas.pydata.org/) - Data handling
- [matplotlib](https://matplotlib.org/) - Data visualization
- [requests](https://docs.python-requests.org/en/latest/) - API calls
- [python-dotenv](https://pypi.org/project/python-dotenv/) - Environment variable management

---

## Project Structure
- punctuality_tracker.py # Main Python script
- requirements.txt # Python dependencies
- README.md # Project documentation
- .gitignore # Ignore sensitive files
- .env # API keys (NOT uploaded to GitHub)

Create a file named .env in the project root:

- TRANSPORT_API_APP_ID=your_transportapi_app_id
- TRANSPORT_API_APP_KEY=your_transportapi_app_key
- WEATHER_API_KEY=your_openweather_api_key
