# Django weather App
### Description:
- A weather checking application built with Django, utilizing the OpenWeatherMap API to fetch current weather data. 
- The app features a simple and user-friendly interface developed with basic HTML and enhanced with Bootstrap for a responsive design.
- Users can easily search for weather details by entering city names.

## App Interface:

Image here

### Project Setup:
- Clone the repository
- Setup a virtual enviornment with venv like this `python3 -m venv venv`
- Install the requirements with `pip install -r requirements.txt`
- Run the default migrations with this command `python manage.py migrate`
- Run the migrations file first to setup the db with this commmand `python3 migrations/0001_initial.py`
- create superuser to access the admin panel `python manage.py createsuperuser`
- Run the server with this command `python3 manage.py runserver`
