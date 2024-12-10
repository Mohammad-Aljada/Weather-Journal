# FEND Project #3: Weather Journal
## Overview

**Weather Journal** is the third project of Udacity [Front End Web Developer](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd0011) nanodegree program. It requires to build a single-page JavaScript app which creates a weather record for user based on their input and data from [OpenWeatherMap API](https://openweathermap.org/api).

## Getting Started
### Prerequisites
1. Download [Node.js](https://nodejs.org/en/download/).
2. Install the following packages using ```npm```.
```sh
$ npm install express
$ npm install cors
$ npm install body-parser
```
### Running Locally 
To run **Weather Journal** locally:
1. Clone this repository.
2. ```cd``` into project directory.
3. Start the local server from command line.
```sh
$ node server.js
```
4. Open ```http://localhost:3030``` in your browser.
### Using Another API Key
To use your own OpenWeatherMap API key,
1. Create an account on [https://openweathermap.org/api](https://openweathermap.org/api).
2. In *app.js*, save your key in ```apiKey``` constant.
