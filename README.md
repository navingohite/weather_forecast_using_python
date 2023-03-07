# weather_forecast_using_python

##Real-Time Weather Forecasting
This project is a weather forecasting application that provides users with real-time weather updates for any location around the world. It utilizes the Django web framework and integrates with the OpenWeatherMap API to retrieve live weather data.

###Features
Live weather updates for any location around the world
Decision tree algorithm for predicting weather conditions based on historical weather data
User-friendly interface for easy access to weather information
Error handling and notification for any errors
Responsive design for mobile devices

###Requirements
Python 3.6 or higher
Django 3.2.7 or higher
requests 2.26.0 or higher

###Installation

1#
cd real-time-weather-forecasting
Create and activate a virtual environment:

2#
python3 -m venv env
source env/bin/activate
Install the required dependencies:

3#
pip install -r requirements.txt
Set up the environment variables. Create a .env file in the root directory and add the following variables:

4#
SECRET_KEY=your_secret_key_here
DEBUG=True
Note: Replace your_secret_key_here with a secret key of your choice.

5#
Run database migrations:

python manage.py migrate
Collect static files:

6#
python manage.py collectstatic
Run the application:

7#
python manage.py runserver
Open your web browser and go to http://localhost:8000/ to access the Real Time Weather Forecasting application.

###Usage
Open your web browser and go to http://localhost:8000/ or the URL specified by your Django server.
Enter the name of the city you want to check the weather for in the search bar.
The application will display the current temperature, description, and an icon representing the current weather condition.


###Technologies Used
Django: A Python-based web framework used to build the web application and handle server-side operations.
OpenWeatherMap API: A popular weather data provider used to retrieve live weather data for different locations around the world.
Decision Trees: A machine learning algorithm used to predict weather conditions based on historical weather data.
HTML, CSS, and JavaScript: Front-end web technologies used to create the user interface and add interactive features to the web application.




