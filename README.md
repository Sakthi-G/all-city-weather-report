<h2 align="center">Welcome to all-city-weather-report 👋</h2>
<p>
  <a href="https://www.npmjs.com/package/all-city-weather-report" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/all-city-weather-report.svg">
  </a>
  <a href="#" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-ISC-yellow.svg" />
  </a>
</p>

> It is used to return cities weather report

## Install

```sh
npm install all-city-weather-report
```

## Usage

```javascript
// This package exports three functions, i.e) allTimeZones(),  timeForOneCity(),  nextNhoursWeather()
let {
  allTimeZones,
  timeForOneCity,
  nextNhoursWeather,
} = require("all-city-weather-report");

// => citiesWeatherReport consists of cities basic weather details like CityName, Temp, Humidity, Precipitation, etc
let citiesWeatherReport = allTimeZones();

// => dateAndTime consists of Date, Time along with city Name for provided city name
let dateAndTime = timeForOneCity(cityName);

// => consecutiveHrsData consists of consecutive hours temperature
let consecutiveHrsData = nextNhoursWeather(
  dateAndTime,
  hours,
  citiesWeatherReport
);
```

## Author

👤 **Sakthivel Ganapathy**

- Github: [@Sakthi-G](https://github.com/Sakthi-G)

## Show your support

Give a ⭐️ if this project helped you!
