# 100 Days Of Code - Log

Let's do this!

### Day 1: January 3, 2017

**Today's Progress:** Forked the repo for #100DaysOfCode, compressed some jpegs, implemented a dynamic background image that changes based on the user's local weather, and used a case statement and some Sass.

**Thoughts:** Great first day that started off getting reacquainted with forking a Git repo. I also used a mixin for the dynamic background which was particularly satisfying as I'm finally applying concepts learned in tutorials into my own projects. Not sure how to link to a live preview of my work on GitHub yet but I'll figure that out tomorrow. Woohoo!


### Day 2: January 4, 2017

**Today's Progress:** Implemented some styling to the app (I am no designer!). Used some flexbox. Also implemented a celcius to farenheit function for the temperature. Now to figure out how to toggle it back to celcius.

**Thoughts:** It's hard to work on a weather app with today's weather being so hot! Started later in the day and I found it difficult to get going. However, I successfully managed to achieve my mini goal of converting the temperature to farenheit. I should finish this off tomorrow.

**Link to work:** [Local Weather App](https://bsummersgb.github.io/local-weather-app/)


### Day 3: January 5, 2017

**Today's Progress:** Made a function that toggles the temperature between the metric and imperial measurements. Learnt how to host the app on GitHub pages. Also saw the power of using global variables to store the ajax data.

**Thoughts:** I set my timer for an hour to figure out the functionality of the unit conversion and managed to do it in 40 minutes, with time to spare to set up a project page on GitHub. However, there is an issue with my background images not loading on the live demo. On first inspection, it seems to be a common issue but I'm yet to figure it out.

**Link to work:** [Local Weather App](https://bsummersgb.github.io/local-weather-app/)

### Day 4: January 6, 2017

**Today's Progress:** Fixed the issue with the background images not displaying on GitHub pages - see thoughts below.

**Thoughts:** The image directory was not showing in the source because the root path had changed when it was pushed up to GitHub pages. Previously, I was linking to the images with /assets/img/rain.jpg however, the root folder is now actually bsummersgb.github.io. So I changed the path to /local-weather-app/assets/img/rain.jpg and that fixed the issue. However, this also means that the images no longer work on my local machine, but I think I can leave my master branch with the local environment path and only use the gh-pages branch for the full path.

**Link to work:** [Local Weather App](https://bsummersgb.github.io/local-weather-app/)

### Day 5: January 7, 2017

**Today's Progress:** Long shift at work so could only do some code commenting and refactoring of the weather app.

**Thoughts:** Still very valuable to force yourself to go back over and understand my code. Even though it was only 30 minutes of work before I go to sleep, I'm keeping up the habit of coding every day!

**Link to work:** [Local Weather App](https://bsummersgb.github.io/local-weather-app/)

### Day 6: January 8, 2017

**Today's Progress:** Trying to fixed issues with having mixed content on GitHub pages. Used https where possible.

**Thoughts:** The OpenWeather API doesn't https without a paid subscription. I may have to change the API I use - forecast.io is anothe option.

**Link to work:** [Local Weather App](https://bsummersgb.github.io/local-weather-app/)

### Day 7: January 10, 2017

**Today's Progress:** Started on the Wikipedia Viewer and created some basic structure for the app.

**Thoughts:** Finding the documentation for the Media Wiki API very difficult to follow. This should be a relatively straight forward project once I construct the correct call to the API but it is proving difficult. Also feeling guilty for missing yesterday but the time I had assigned to code at the end of my shift was unavoidably removed. I had better ensure that I do not leave that to chance again in future and always code in the day.

### Day 8: January 11, 2017

**Today's Progress:** Sussed out the correct call to the API.

**Thoughts:** Feeling happy that I finally cracked the documentation just by searching for the 'opensearch' property. I still don't think the docs are user-friendly though. Now just to figure out how to use a loop to iterate through the data and populate my unordered list.

### Day 9: January 12, 2017

**Today's Progress:** Spent a lot of time delving into the jQuery ajax function and learnt about the templating engine Mustache.js. Also figured out how to display the data in an unordered list as individual list items with a for loop.

**Thoughts:** A big victory today once I figured out how to correctly implement a for loop to iterate through the API data. Mustache.js is also super interesting and avoids messily constructed strings of html and variables in my JavaScript code. I just need to figure out how to grab the url for each list-item and place it in the <a> tag's href value.

### Day 10: January 13, 2017

**Today's Progress:** Now successfully displaying data in a formatted list using Mustache and template tags.

**Thoughts:** I felt I stepped up massively with the complexity of my code. I realised that the Mustache.render method does not accept an array as an argument. Instead of bailing on using Mustache I figured out how to convert my array data into object form which allowed for the use of the templating engine and the $.each function. I would like to look further into the each() method as well as reduce() and map().

### Day 11: January 14, 2017

**Today's Progress:** No project work as I attended a NodeSchool meetup.

**Thoughts:** Felt like a bit of a deep dive but it was good to expose myself to Node.js.

### Day 12: January 15, 2017

**Today's Progress:** Did some styling for the list on the Wiki viewer.

**Thoughts:** Missed a day yesterday - did not actually have one hour to spare a long shift at work. Back on track.

### Day 12: January 15, 2017

**Today's Progress:** Finalised styling | Code refactoring | Comment code

**Thoughts:** Finished off the Wikipedia app to meet all user story requirements

**Link to work:** [Wikipedia Viewer](https://bsummersgb.github.io/wikipedia-viewer/)



<!-- ### Day 2: January 4

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) -->
