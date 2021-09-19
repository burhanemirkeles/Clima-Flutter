# Clima ☁

## About Project

This project is a companion project to The App Brewery's Complete Flutter Development Bootcamp. The objective of this project is to learn about asynchronous programming in Dart. When project is finished you'll  be able to find out the live weather data in the current location of the device as well as the weather for any city you can think of!
The final view of application: 
![](https://github.com/burhanemirkeles/Clima-Flutter-emirkeles/blob/Clima-Flutter-emirkeles/gif/clima_app_completed_gif.gif?raw=true)
## Objectives Covered
* How to use Dart to perform asynchronous tasks.
* Understand async and await.
* Learn about Futures and how to work with them.
* How to network with the Dart http package.
* What APIs are and how to use them to get data from the internet.
* What JSONs are and how to parse them using the Dart convert package.
* How to pass data forwards and backwards between screens using the Navigator.
* How to handle exceptions in Dart using try/catch/throw.
* Learn about the lifecycle of Stateful Widgets and how to override them.
* How to use the Geolocator package to get live location data for both iOS and Android.
* How to use the TextField Widget to take user input.

# Development Journal

### dev Sprint #1
After seeing this project on The App Brewery's Complete Flutter Development Bootcamp, I created a fork and started working on it. While working on the project, I had to change some of the code written in the course because some features used in the course were outdated.
I changed,
* the Geolocator package to 7.6.2 and used newer features of it.
* API services of openweathermap.org to a newer version.

### dev Sprint #2
* I coded the services parts which reads and uses data from JSON files that comes from API.
* A loading animation added for pre-loading sequence.
* Lots of refactoring on location and weather data services.
* At the end of this sprint, application can read and show real-time weather data from https://openweathermap.org/ "Current Weather Data API".

### dev Sprint #3
* A new screen that allows users to search with a TextField Widget any city's weather condition added. When adding this screen, I learned how to pass data backwards through the navigation stack.






