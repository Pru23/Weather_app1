                            Weather App

Overview
This is a simple weather application built using Python and PyQt5. The app allows users to input a city name and retrieve the current weather, including temperature, weather description, and an emoji representing the weather condition. The weather data is fetched from the OpenWeatherMap API.
Features
•	City Input: Users can enter the name of a city.
•	Temperature Display: Shows the current temperature in Fahrenheit.
•	Weather Description: Describes the weather condition (e.g., cloudy, rainy).
•	Weather Emoji: Displays an emoji representing the current weather.
•	Error Handling: Displays detailed error messages if issues occur (e.g., invalid API key, city not found, server error).
Technologies Used
•	Python 3.x
•	PyQt5: For the graphical user interface.
•	OpenWeatherMap API: To fetch real-time weather data.
•	Requests Library: For making HTTP requests.
How to Run
1.	Clone the repository:
Copy code
git clone https://github.com/yourusername/weather-app.git
cd weather-app
2.	Install dependencies: Ensure you have Python and PyQt5 installed. You can install PyQt5 using pip:
Copy code
pip install PyQt5 requests
3.	Get your OpenWeatherMap API Key:
o	Go to OpenWeatherMap and sign up.
o	Generate an API key.
4.	Replace API Key: In the code, replace the placeholder API key with your actual API key:

Copy code
api_key = "your_actual_api_key_here"
5.	Run the Application:
Copy code
python weather_app.py
Error Handling
The application handles the following errors:
•	Invalid API Key: Displays an unauthorized error.
•	City Not Found: Displays a city not found error.
•	Connection Issues: Displays connection or timeout errors.
•	Server Issues: Displays relevant server errors (e.g., 500, 502, 503).
Future Enhancements
•	Add more detailed weather information (humidity, wind speed, etc.).
•	Allow users to switch between Celsius and Fahrenheit.
•	Add support for saving favorite cities.

Contact
For any questions or contributions, please reach out at [pdera09@outlook.com].
