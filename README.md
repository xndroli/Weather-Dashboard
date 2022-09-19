# Server-side API: Weather-Dashboard

Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

Using the [OpenWeather One Call API](https://openweathermap.org/api/one-call-api) I will create an application that retrieves weather data for cities, using localStorage to store any persistent data.

## Table of Contents

- [User-Story](#User-Story)
- [Acceptance-Criteria](#Acceptance-Criteria)
- [Demo](#Demo)
- [Live Application](#Live-Application)

## User Story

```md
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

## Acceptance Criteria

```md
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
```

## Demo

The following image shows the web application's appearance and functionality:

[![Web API: Coding Quiz](./assets/images/weatherDashboard-demo.png)](https://xndroli.github.io/Weather-Dashboard/)

## Live Application

[See Live Weather Dashboard](https://xndroli.github.io/Weather-Dashboard/)

---

© 2022 xndroli. Confidential and Proprietary. All Rights Reserved.
