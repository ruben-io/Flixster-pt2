
# Android Project 4 - *Flixster pt 2*

Submitted by: **Ruben Velasquez**

**Flixster pt 2** is a movie browsing app that allows users to browse ... [TODO] 

Time spent: **6** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **Choose any endpoint on The MovieDB API except `now_playing`**
  - Chosen Endpoint: movie/video
- [x] **Make a request to your chosen endpoint and implement a RecyclerView to display all entries**
- [x] **Use Glide to load and display at least one image per entry**
- [x] **Click on an entry to view specific details about that entry using Intents**

The following **optional** features are implemented:

- [ ] **Add another API call and RecyclerView that lets the user interact with different data.** 
- [ ] **Add rounded corners to the images using the Glide transformations**
- [ ] **Implement a shared element transition when user clicks into the details of a movie**

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!


### App Walkthough GIF
<img src='https://imgur.com/L072MOV.gif' title='Walkthrough' width='' alt='Video Walkthrough' />

### Notes
I faced some challenges while making this application. I wrote the entire code and my application was running but nothing was popping up on the filxter screen. When I debugged, I found out that my activity_main.xml file had an issue. In this file, I did not set the android layout_width and andorid layout_height to "match parent" instead they were set to 0dps. Once, I corrected this issue my application ran fine.
## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2022] [Ruben Velasquez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
