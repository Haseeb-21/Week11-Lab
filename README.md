- Weather Service - 
This service makes use of a script, .service, and .timer file to output a 3 day
forecast to a 'weather' file every hour.

Files:
    - weather_script
    - weather.service
    - weather.timer

weather_script
Using wttr.in, this script will output a 3 day forecast of the user's location
to a file named 'weather'. This file is located in the home directory and will be 
automatically created.

weather.service
This file will create a service that runs the weather script.

weather.timer
This file is used to run weather.service every hour. This means the weather file
containing the forecast will be updated each hour.

