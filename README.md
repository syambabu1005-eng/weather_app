# weather_app
🌦️ Weather App (Python)

A simple Weather Application built using Python that fetches real-time weather data and a 3-day forecast for any city using an online API.

---

📌 Features

- Get current weather details for any city
- Displays:
  - Temperature (°C)
  - Feels like temperature
  - Humidity (%)
  - Wind speed (km/h)
  - Weather condition
- 3-day weather forecast
- Handles network and input errors

---

🧠 How It Works

- Uses the wttr.in API to fetch weather data
- Sends HTTP request using the "requests" library
- Parses JSON response
- Displays formatted weather details in console

---

▶️ How to Run

1. Install required library:

pip install requests

2. Save the file as "weather_app.py"

3. Run the program:

python weather_app.py

---
💻 Example Output

==============================
🌦️ WEATHER REPORT
==============================
📍 City: Hyderabad
🌡️ Temperature: 30 °C
🤒 Feels Like: 34 °C
💧 Humidity: 60 %
🌪️ Wind Speed: 15 km/h
☁️ Condition: Partly cloudy
==============================

📅 3 Day Forecast

Date: 2026-04-14 | Avg Temp: 31°C | Condition: Sunny
Date: 2026-04-15 | Avg Temp: 32°C | Condition: Cloudy
Date: 2026-04-16 | Avg Temp: 30°C | Condition: Rain

---

🛠️ Technologies Used

- Python
- requests library
- REST API (wttr.in)

---

🚀 Learning Outcome

- Working with APIs in Python
- Handling JSON data
- Error handling using try-except
- Building real-world applications

---
 ## 🧑‍💼 Created By
Devarapalli Syam
---

📢 Note

- Requires internet connection
- API used is free and does not require an API key

---

🔗 Future Improvements

- Add GUI using Tkinter
- Add hourly forecast
- Add weather icons
- Support multiple cities
