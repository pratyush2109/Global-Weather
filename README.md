# Global Weather and Forecast React App

This project was created to display the current weather of the selected place as well as forecast for the next 7 days of the selected place.

## Used API's

In the project directory, the used API's are:

### GeoDB Cities API

GeoDB is an online cities database. 
It exposes city, region, and country data via both GraphQL and REST APIs

The GeoDB cities API is used in this project to predict the cities that the user \
is trying to type in and search. For the purpose of this project, the cities with a \
minimum population of 1,00,000 will only be displayed as options.

### OpenWeather API

For each point on the globe, OpenWeather provides hyperlocal minute forecast, historical data, \
current state, and from short-term to annual and forecasted weather data.

It is used to get the current weather as well as the forecast for next few days \
of the searched place.

### `Functioning`

When the user tries to type in a place, the Geodb Cities API \
is called and it tries to get the cities or town names that the user \
is trying to search for. Once the user finds the same, the user can just \
select the place.

Once the required place is selected, the OpenWeather API is called \
and it will fetch the forecast of the searched place and the same will be \
displayed along with some other details related to weather.\


### `Initial State of the web-app`

![Pic1](https://user-images.githubusercontent.com/39798918/179822397-cb26ca8a-79ed-4d83-b3c9-cd8c245322e8.png)

### `When the user tries to search for a place`

![Pic2](https://user-images.githubusercontent.com/39798918/179822467-37645883-a4c1-4c47-8d1a-9601051b6624.png)

The probable cities/town are getting displayed once the user starts to type in the \
city or town the user wants to search for.\

### `When the user selects a place`

![Pic3](https://user-images.githubusercontent.com/39798918/179822606-b62cc981-f026-4a31-8c16-e9f38c4b20db.png)

The current weather of the search place is getting displayed along with some other \
details related to the current weather of the searched place.

![Pic4](https://user-images.githubusercontent.com/39798918/179822755-5a0e013f-0795-4590-8123-089126518a51.png)

Along with the current weather the forecast weather for 7 days is also displayed along \
with other details related to weather.

![Pic5](https://user-images.githubusercontent.com/39798918/179822946-176934da-5afc-4f1c-91fc-578763158234.png)

When the forecast is expanded, some other details like Pressure, Humidity etc. are also displayed.

### `References`

1. OpenWeather API: https://openweathermap.org/
2. GeoDB Cities API: https://rapidapi.com/wirefreethought/api/geodb-cities/
