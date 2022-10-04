
## Flix
Flix is an app that allows users to browse movies from the The Movie Database API.
### User Stories

#### REQUIRED (10pts)

- [X] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [X] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [X] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.



### App Walkthough GIF
<img src='https://imgur.com/L072MOV.gif' title='Walkthrough' width='' alt='Video Walkthrough' />

### Notes
I faced some challenges while making this application. I wrote the entire code and my application was running but nothing was popping up on the filxter screen. When I debugged, I found out that my activity_main.xml file had an issue. In this file, I did not set the android layout_width and andorid layout_height to "match parent" instead they were set to 0dps. Once, I corrected this issue my application ran fine.
## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
