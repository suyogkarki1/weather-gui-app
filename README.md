 🌦 Weather Forecast GUI Application

 📌 Project Overview

This project is a Python-based desktop weather application that allows users to search for any city and view real-time weather information.
The application fetches weather data using the OpenWeatherMap API and displays it through an interactive Tkinter graphical user interface.

The app shows details such as temperature, humidity, pressure, visibility, sunrise, sunset time, and weather conditions with icons.


 ⚙️ Features

* Search weather by city name
* Displays temperature in Celsius
* Shows humidity, pressure, and visibility
* Sunrise and sunset time display
* Dynamic weather icons (clear, rain, clouds, etc.)
* Responsive GUI using threading
* Error handling for invalid city or internet issues


 🛠 Technologies Used

* Python
* Tkinter (GUI)
* OpenWeatherMap API
* Requests
* Pillow (PIL)
* Threading
* ConfigParser
* TimezoneFinder
* PyTZ
* Geocoder


 📂 Project Structure

Weather-App
│
├── main.py
├── config.ini
├── requirements.txt
├── Images/
├── Icons/
└── README.md

🔑 API Setup

1. Create a free account on OpenWeatherMap
2. Generate your API key
3. Create a file named **config.ini**

Example:

[Openweather]
api = YOUR_API_KEY

 ▶️ How to Run the Project

1. Clone the repository
        git clone https://github.com/yourusername/weather-app.git

2. Install dependencies
        pip install -r requirements.txt

3. Run the application

        python main.py


 👨‍💻 Author

Suyog Karki
BSc IT (Data Science)

 📄 License

This project is for educational purposes.
