## Weather app

A simple **weather app** that based on a **users location** can find the relevant weather for that user.

### Sign up for api key

Go to https://openweathermap.org/appid and **sign up for an api key**. This key we will use for getting access to the weather api.

### First call to the weather api

To get some data from the api go to https://api.openweathermap.org/data/2.5/weather?q=copenhagen&appid=YOUR_APP_ID, where `YOUR_APP_ID` is substituted with the key you signed up for in the first step.

If you go to the [above url](https://api.openweathermap.org/data/2.5/weather?q=copenhagen&appid=YOUR_APP_ID) and see some weather json data then congrats 🎉.

### Fetching and Displaying weather data from a city

This following data have been showed:

- The chosen city
- Temperature
- Icon for the weather type
- Wind speed
- How clowdy it is
- When sunrise and sunset is
- a map showing where the city is located

![Weather man](https://media.giphy.com/media/3ohzdJlyD2InWwbJle/giphy.gif)
