# Weather-Dashboard


## Description

A weather dashboard using the OpenWeather API. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

## Installation

No installation needed! Just click on the follwing link to get started: https://bonnerac.github.io/Weather-Dashboard/

## To Use

Simply type the name of a city in the searchbar. The Weather Dashboard will provide you with lots of information about the current and future weather conditions of that city. Previous cities that you searched for will appear on the left side of the screen.

## Goals

This site is designed to take a city input from the user and display weather information about the selected city. The information includes:

* City Name and current weather icon
* Local Time
* Temperature 
* Humidity
* UV Index
   * with dynamically generated colors for index level
* 5 day forecast 
   * featuring dynamically generated date, weather icon, temperature, and humidity.
* A search history

The weather information is generated dynamically and site is mobile responsive.

## Technologies Used

For this project, I used:
* OpenWeather API
* JavaScript
* jQuery
* Bootstrap
* Moment.JS
* Google Fonts

## Complications

During the process of making this weather site, I did run into some problems: 

* Writing DRY code.
    * I got almost all of the elements on the page that I wanted, but I still feel like I was repeating myself a lot and could have used more for loops to cut down on my overall lines of code.
* Search History
    * Although I was able to store the user's previous searches in local storage, I was unable to make the search history reappear after refresh. I also was unable to have any city but the last search displayed. 
* Tablet View
  * App looks good on desktop and phones, but I had difficulty making it look good for tablets.
    
## Author
* Alex Bonner
   * https://github.com/bonnerac

## Credits and Thanks

Thank to Paul (https://github.com/PCeeeZy) for trying to guide me through my local storage problems. 
