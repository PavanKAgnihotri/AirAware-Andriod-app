# AirAware-Andriod-app

App Idea
AirAware is a mobile application that shows the real-time air quality information using
public API like WAQI. Based on the Air Quality Index (AQI), this app shows simple,
actionable health tips for users. Some of the features include automatic or manual
location based AQI tracking, health tips and historical trend graphs. The main aim of this
app is to create a user-friendly experience that prioritizes health over any technical
details.

Purpose: The main purpose of AiAware is to make air quality data easily
accessible and understandable for everyday users. Based on the current
conditions, our app provides health-focused tips. During the period of poor
quality, the app helps the users make informed decisions about any outdoor
activity and take preventive measures. It raises awareness about environmental
health by educating users about the pollutants, their sources and their impact
both indoors and outdoors.

Target users: AirAware is mainly designed for a broad audience about air quality
and its effects on health. Main target users include:
○ Athletes, joggers and for any outdoors going users who monitor air quality
before exercising.
○ For people with any respiratory conditions.
○ People living in highly polluted cities.


MVP (Minimum Viable Product): The main goal is to build a working app that
provides real-time air quality data and basic health tips.

Key Features in MVP:
Real time AQI by location: Automatic location detection via GPS. It also
has manual city search input.
Simple health tips based on AQI levels
Clean and simple UI: AQI value with categories like Good, Moderate etc.
API Integration: Fetching data from WAQI APIs.
● Goal Functionality for Full App: MVP is expanded by adding interactivity and
many usability features. Some of the features are:
○ Historical AQI trend graphs: View the weekly air quality trends.
○ Multi city Support: The app allows the users to track AQI for multiple
locations.
○ Reduce API calls and improve app speed.

Stretch Goals:
Some of the future enhancements that can be made for our App are:
1. Personalized health profile and tips recommendations.
2. Recommend tourist places based on the AQI data.
3. Global coverage and Language support.

Key Data Objects
The AirAware app mainly relies on the WAQI API for the data. So the key data objects
for the app include:
UserLocation: latitude, longitude.
AQIData: AQI, dominant pollutant, health tips, forecast data.
SearchQuery: user-entered city/location name, API results.
All the data is temporarily stored and cached and does not have any long term storage.

Application Screens
1. Start-Up Screen:
This screen appears when the app is opened. It contains the App logo appearing
with a loading animation and the title of the application below it as a simple
description. The app fetches the user location and makes the start-up calls as the
logo appears.
2. Current Location’s AirQuality Data Screen:
This screen appears when the user presses anywhere on the start-up screen.
Users are presented with the air quality data from their current location. Here in
this screen the current location data is fetched from the user-location and then
queries the WAQI API to get the response for the location which then displays
the AQI score, pollutant level, the forecast data for a week in the form of a graph,
along with the health tips which can be viewed by swiping (gesture detection).
This screen also has a button to go to the search screen.
3. Search Screen:
When the user presses on the button in the second screen then it takes to the
Search screen. Here the user has an option to type in the city of their preference
and the app calls the WAQI API to get the air quality data for that city. Similar to
the second screen the Air Quality data and the health tips.

Target Platform
The AirAware project is mainly based on the Android platform. It is so that the project is
prioritized on one platform that is Android and to utilize the feasibility of development in
Android and Kotlin along with its global market share and easier use of location and
sensor data.
