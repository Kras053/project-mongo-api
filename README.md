# Project Mongo API

This week I built an API using MongoDB and mongoose. I used seed data and created routes with app.get() with status codes with try and catch method.

Routes: 
    
      "/netflixShows": "Get whole array of the Netflix movies and TV shows",
      "/netflixShows/release_year/'year of release'": "Get array of shows from a specific release year",
      "/netflixShows/title/'title of show'": "Get one specific show by it's title"
    

## The problem

If I had more time I would solve why the try and catch method is not working properly, it only returns error for the release_year when letters are typed otherwise all is considered success. 
I'd like to find the correspondent to .includes() method to be able to search and return partly written key words and also more endpoints. Now I could not include cast since it would work if there were only one actor in crew like Christian Morales, but not for Winona Ryder who has other cast members.

## View it live
https://project-mongo-api-shows.herokuapp.com/

