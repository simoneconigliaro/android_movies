# Android Popular Movies App
Popular Movies app for Udacity Android Developer Nanodegree
## Description
- The app fetches movies from <a href="https://www.themoviedb.org" target="_blank">The Movie DB</a> showing to the user a scrolling grid of movie posters. 
- It allows the user to sort the order by most popular, top rated and favourite movies. 
- Tapping on one of the posters will open a details screen with additional information such as original title, movie poster image thumbnail, synopsis, user rating, release date, trailers and reviews. 
- Always on the detail screen, the user can mark a movie as a favourite by tapping the heart icon and it will be stored in a local database. 
- The app handles data persistence using a content provider and a sqlite database.

## Libraries
- [Picasso](http://square.github.io/picasso/) for image loading
- [Butterknife](https://jakewharton.github.io/butterknife/) for field and method binding for Android views

## Screenshots
<img src="https://github.com/simoneconigliaro/android_movies/blob/master/Screenshot_1.png" width="270"/>&nbsp;
<img src="https://github.com/simoneconigliaro/android_movies/blob/master/Screenshot_2.png" width="270"/>&nbsp;
<img src="https://github.com/simoneconigliaro/android_movies/blob/master/Screenshot_3.png" width="270"/>

## Getting Started
The app uses The Movie Database API. You can get an API key signing up <a href="https://www.themoviedb.org/account/signup?language=en-EN" target="_blank">here</a> and set it in gradle.properties

