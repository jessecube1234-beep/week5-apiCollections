# week5-apiCollections
Week 5 API Collections assignment.

##Weather API Postman Assignment

###Steps Taken
1. Created a new Postman collection named "Weather API Collection".
2. Set up an environment called "Weather API Environment".
3. Added a variable named "weatherApiKey" and assigned my OpenWeatherMap API key as its value.
4. Sent a GET request using the endpoint below:
https://api.openweathermap.org/data/2.5/weather?q=Chicago&appid={{weatherApiKey}}&units=imperial

###Variable Use and Benefits
The "{{weatherApiKey}}" variable let me use my API key without putting it directly in the URL. It also made it easy to reuse the same setup for other cities.

###Response Analysis
The response shows live weather data for each city. It includes details like the temperature, how it feels, humidity levels, and a short description of the current conditions. The "200 OK" status means each request was successful.