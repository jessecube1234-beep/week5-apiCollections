# Week 5 API Collections and Exploring the Weather API
This repository includes both Week 5 assignments:
1. API Collections
2. Exploring the Weather API Postman Assignment

##Weather API Postman Assignment

###Steps Taken
1. Created a new Postman collection named "Weather API Collection".
2. Set up an environment called "Weather API Environment".
3. Added a variable named "weatherApiKey" and assigned my OpenWeatherMap API key as its value.
4. Sent a GET request using the endpoint below:
https://api.openweathermap.org/data/2.5/weather?q=Chicago&appid={{weatherApiKey}}&units=imperial

###Variable Use and Benefits
The "{{weatherApiKey}}" variable let me use my API key without putting it directly in the URL. It also made it easy to reuse the same setup for other cities.
<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/4c01eef1-fe84-467c-8a77-5f634a587d06" />


###Response Analysis
The response shows live weather data for each city. It includes details like the temperature, how it feels, humidity levels, and a short description of the current conditions. The "200 OK" status means each request was successful.
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/311ebcd7-9abc-42d7-8d4b-152d8cff8548" />

---

##Exploring the Weather API Assignment

###Request URL
https://api.openweathermap.org/data/2.5/weather?q=Los Angeles&appid={{weatherApiKey}}&units=imperial

###Query Parameters
1. q: city name (Chicago, Los Angeles, etc.)
2. appid: API key stored as a Postman environment variable ({{weatherApiKey}})
3. units: imperial (setting units of measurement)

###Response Summary
The API returned current weather data for each city. Including: temperature, humidity and a description of the weather. The "200 OK" status means the request was successful.
<img width="1918" height="1024" alt="image" src="https://github.com/user-attachments/assets/e126cf4f-09e3-44ba-8ede-b4880f9214a7" />

###Reflection on Query Parameters
Query parameters tell the API what data to return. If they are missing or wrong, the API can reurn either an error or the wrong result.

