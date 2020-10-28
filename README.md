# Weather-Dashboard-Project

Weather Dash Board Project

## Objective

To create a Weather Application using retrieved API information for current as well as 5 day forecast . The user will enter U.S. city and receive the information and the app will also retain that city plus all cities entered so if application is " refreshed" the last city
entered will by default display that information back to the user.

## Software used in Project

(a) HTML
(B) Jquery
(c) CSS
(d) Moment JS
(e) Weather api
(f) AJAX

## HTML

HTML consisted of input for the city information with associated "button", area to display cities chosen for weather info , area
for current weather information and an area for the 5 day forecast

## Jquery / Javascript

Jquery used to connect the DOM elements to working variables in
the JS file as well as being able to append the results from the
API search using AJAX . Several functions were created for the
following:

(a) " fade in " of the "five day" forecast
(b) get city input
(c) appending buttons for each city entered for
refresh functionality
(d) retrieving weather information when buttons
clicked upon refresh
(e) storing all created buttons in "local storage"
(f) reloading buttons from "local storage" upon refresh
(g) retrieve "current weather" using API / AJAX
(H) retrieving " five day forecast " using API / AJAX

## TESTING

(a) Enter a city and receive current / 5 day information plus store
city for future reference : outcome successful
(b) ability to enter "n" number of cities and get current / 5 day
forecast one city after another and being able to store those
selected cities : outcome successful
(d) ability to refresh the page and retain all previous
selections plus show the weather for the last city entered: outcome successful

## FUTURE ENHANCEMENTS

Application can be modified to list weather information for
cities outside the U.S. as well as more detailed data
that can help the user better plan professional / personal
activities
