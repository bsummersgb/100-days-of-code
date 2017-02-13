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

### Day 12: January 16, 2017

**Today's Progress:** Did some styling for the list on the Wiki viewer.

**Thoughts:** Missed a day yesterday - did not actually have one hour to spare a long shift at work. Back on track.

### Day 13: January 17, 2017

**Today's Progress:** Finalised styling | Code refactoring | Comment code

**Thoughts:** Finished off the Wikipedia app to meet all user story requirements

**Link to work:** [Wikipedia Viewer](https://bsummersgb.github.io/wikipedia-viewer/)

### Day 14: January 18, 2017

**Today's Progress:** Started on the Twitch TV app and successfully retrieved a list of channel objects.

**Thoughts:** Decent few sessions today. I'm really getting into the swing of these ajax calls now. I feel I achieved more in less time today which is a very motivational feeling. I'll start linking to my commits now as I didn't realise you could do that before.

**Link to work:** [Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/694143e74d647c41ff6d8cffeb086710b29db039)

### Day 15: January 19, 2017

**Today's Progress:** Came up against multiple bugs with subsequent solutions. Now experiencing 'brain melt' with another bug and will have to come back to it tomorrow.

**Thoughts:** Despite the bugs today was probably the most valuable yet. Coming up against these problems is a great way to learn and it feels great once you fix the problem. I just need to utilise callbacks and promises to ensure that my list is only populated after the ajax functions have finished running within the $.each() function.

**Link to work:** [Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/4c583c607747edd8b1434aca509d318b3dcbdff9)

### Day 16: January 23, 2017

**Today's Progress:** Hit my first major roadblock; I've been stuck for three days!! I've spent a few hours each day trying to resolve the issue with my ajax calls within the $.each() function but have yet to come up with a solution.

**Thoughts:** I've realised the main knowledge gap here has to do with executing code when all ajax iterations have completed, which involves using Promises. I'm chipping away at trying to understand this concept but it definitely feels like a higher-level leap. As a result, my code stands as of the last commit.

### Day 17: January 24, 2017

**Today's Progress:** FINALLY CRACKED IT!! Resolved a five-day bug in the code by using the concept of Promises.

**Thoughts:** So instead of using an each loop, I mapped each channel name two separate ajax calls and returned the resolved promises to a new array. Upon the resolution of the promises I was able to assign the API data to a new object which I then used to display all the channel info in the html. This was absolutely the highest level of coding I have implemented so far.
[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/cf860b83fe7e1f948dbf446ebc750a552d43c616)

### Day 18: January 25, 2017

**Today's Progress:** Made a few changes to the list template so I there are conditional classes set to each channel. I can now view what is currently running on the live streams and I am about to start showing and hiding streams based on their status.

**Thoughts:** So far the 100DaysOfCode challenge has been relatively successful. I did not commit anything for a few days because of a bug, however I was still working through the code; I just haven't counted those days towards the log. One thing I need to do is set up habitual time-blocks for when to code. I need a trigger/cue which will further reinforce the habit as currently I am just doing it when I have the time.

[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/6fdb7d78f7c53ea15dcd92cbe7bec29303b46cfc)

### Day 19: January 26, 2017

**Today's Progress:** Set up an error handler to display a placeholder logo and message for channels that don't exist

**Thoughts:** I have set up the error handle as a condition within the ajax call however, there may be a better way to do it within the then() function. It's just important for me to get it to work today as I have a big day at work.

[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/23e24cffb24781161ccfec056a9738f64d4e8e90)

### Day 20: January 27, 2017

**Today's Progress:** Spent the time just testing out different ways of showing the channel info depending on whether or not they are currently streaming.

**Thoughts:** Whilst I have it working with buttons, I think I should work on a tab/file diver style so I can test the functionality and discover any edge cases that might prevent this method working properly.

[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/e7c9a11bd6b61bc7ae23b6da1e5468b41391941e)

### Day 21: January 28, 2017

**Today's Progress:** A lot of time spent on styling today. It seems tedious but this is probably due to my lack of practice with CSS and flexbox.

**Thoughts:** I definitely prefer the programming side of web development!

[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/7e2e57c8d6398e2fe589892ce1f75ccb6717b731)

### Day 22: January 29, 2017

**Today's Progress:** Virtually completed the Twitch API application, with just some minor styles remaining. I also have to upload it to GitHub pages and CodePen.

**Thoughts:** Although it took longer than anticipated, it feels good to complete the third project. 100DaysOfCode is definitely helping me to be more consistent. I'm learning a lot faster even when it's just one hour per day as opposed to doing three hours every few days.

[Twitch TV App - latest commit](https://github.com/bsummersgb/twitchtv/commit/8fc87f747474caaab14e301fc4a6c0202f0cd832)


### Day 23: January 30, 2017

**Today's Progress**: Created a GitHub page for the Twitch TV app and started on some more algorithms.

**Thoughts** Feels good to post the live version of the Twitch TV app and to get cracking on with some more algorithms. More new JS please!

**Link(s) to work**
[Twitch TV App - DEMO](https://bsummersgb.github.io/twitchtv/)

1. [Boo Who](https://www.freecodecamp.com/challenges/boo-who#?solution=function%20booWho(bool)%20%7B%0A%20%20%2F%2F%20Check%20for%20the%20type%20of%20parameter%20with%20typeof%20and%20return%20true%20if%20it%20is%20a%20boolean%20primitive%0A%20%20%0A%20%20return%20typeof%20bool%20%3D%3D%3D%20'boolean'%3B%0A%20%0A%20%20%0A%7D%0A%0AbooWho(false`)`%3B)

### Day 24: January 31, 2017

**Today's Progress**: More algorithms.

**Thoughts** I think it would be smart to get a lot more practice with higher-order functions such as reduce, map, and filter.

**Link(s) to work**
1. [Sorted Union](https://www.freecodecamp.com/challenges/sorted-union#?solution=%0Afunction%20uniteUnique(arr)%20%7B%0A%20%20%2F%2F%20Convert%20the%20arguments%20object%20into%20a%20single%20array%2C%20then%20flatten%20it%20using%20reduce...%0A%20%20%2F%2F%20...then%20filter%20the%20current%20value%20(b)%20to%20check%20that%20the%20number%20is%20not%20in%20the%20array%20i.e.%20is%20-1%0A%20%20var%20uniqueArray%20%3D%20Array.from(arguments).reduce(function(a%2C%20b)%20%7B%0A%20%20%20%20return%20a.concat(b.filter(function(i)%7B%0A%20%20%20%20%20%20return%20a.indexOf(i)%20%3D%3D%3D%20-1%3B%0A%20%20%20%20%7D))%3B%0A%20%20%7D%2C%20%5B%5D)%3B%0A%20%20%0A%20%20return%20uniqueArray%3B%0A%20%20%0A%2F%2F%20**%20My%20earlier%20solution%20simply%20used%20reduce%20to%20flatten%20the%20array%20and%20then%20used%20a%20for%20loop%3A%20%0A%0A%2F%2F%20var%20singleArray%20%3D%20Array.from(arguments).reduce(function(a%2C%20b)%20%7B%0A%2F%2F%20%20%20%20%20return%20a.concat(b)%3B%0A%2F%2F%20%20%20%7D%2C%20%5B%5D)%3B%20%0A%0A%2F%2F%20%20%20var%20newArray%20%3D%20%5B%5D%3B%0A%20%20%0A%2F%2F%20%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20singleArray.length%3B%20i%2B%2B)%20%7B%0A%2F%2F%20%20%20%20%20if%20(%20!newArray.includes(singleArray%5Bi%5D)%20)%20%7B%0A%2F%2F%20%20%20%20%20%20%20newArray.push(singleArray%5Bi%5D)%3B%0A%2F%2F%20%20%20%20%20%7D%0A%2F%2F%20%20%20%7D%0A%2F%2F%20%20%20return%20newArray%3B%0A%20%20%0A%20%20%2F%2F%20if%20this%20value%20is%20already%20in%20the%20array%20then%20skip%20it%20%0A%7D%0A%0AuniteUnique(%5B1%2C%203%2C%202%2C%202%5D%2C%20%5B1%2C%20%5B5%5D%5D%2C%20%5B2%2C%20%5B4%5D%5D)%3B%0A)

### Day 25: February 1, 2017

**Today's Progress**: More algorithms.

**Thoughts** I think it would be smart to get a lot more practice with higher-order functions such as reduce, map, and filter.

**Link(s) to work**
1. [Convert HTML Entities](https://www.freecodecamp.com/challenges/convert-html-entities#?solution=function%20convertHTML(str)%20%7B%0A%20%20%0A%20%20%2F%2F%20Array%20to%20hold%20transformations%0A%20%20var%20holderArr%20%3D%20%5B%5D%3B%0A%20%20%0A%20%20%2F%2F%20Iterate%20through%20each%20character%20and%20replace%20any%20special%20characters%20with%20their%20HTML%20entity%20syntax%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20str.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20switch%20(str%5Bi%5D)%20%7B%0A%20%20%20%20%20%20case%20%22%26%22%3A%0A%20%20%20%20%20%20%20%20holderArr.push(%20str%5Bi%5D.replace(%2F%26%2Fg%2C%20'%26amp%3B')%20)%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20case%20%22%3C%22%3A%0A%20%20%20%20%20%20%20%20holderArr.push(%20str%5Bi%5D.replace(%2F%3C%2Fg%2C%20'%26lt%3B')%20)%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20case%20%22%3E%22%3A%0A%20%20%20%20%20%20%20%20holderArr.push(%20str%5Bi%5D.replace(%2F%3E%2Fg%2C%20'%26gt%3B')%20)%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20case%20%22'%22%3A%0A%20%20%20%20%20%20%20%20holderArr.push(%20str%5Bi%5D.replace(%2F'%2Fg%2C%20'%26apos%3B')%20)%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20case%20'%22'%3A%0A%20%20%20%20%20%20%20%20holderArr.push(%20str%5Bi%5D.replace(%2F%22%2Fg%2C%20'%26quot%3B')%20)%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20default%3A%0A%20%20%20%20%20%20%20%20holderArr.push(str%5Bi%5D)%3B%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20%0A%20%20%2F%2F%20Convert%20array%20of%20characters%20back%20to%20a%20string%0A%20%20return(holderArr.join(%22%22))%3B%0A%20%20%0A%20%20%0A%20%20%0A%7D)

2. [Spinal Tap Case](https://www.freecodecamp.com/challenges/spinal-tap-case#?solution=%0Afunction%20spinalCase(str)%20%7B%0A%20%20%0A%20%20var%20newStr%20%3D%20str%0A%20%20%20%20.replace(%2F_%2Fg%2C%20%22-%22)%0A%20%20%20%20.replace(%2F%5Cs%2Fg%2C%20%22-%22)%0A%20%20%20%20.replace(%2F%5Ba-z%5D(%3F%3D%5BA-Z%5D)%2Fg%2C%20%22%24%26-%22)%3B%20%0A%20%20%0A%20%20return%20newStr.toLowerCase()%3B%0A%7D%0A%0A%2F*%0A%20%20-%20Replace%20all%20underscores%20with%20dashes%0A%20%20-%20Replace%20all%20spaces%20with%20dashes%0A%20%20-%20Match%20all%20lowercase%20letters%20if%20they%20are%20followed%20by%20an%20uppercase%20letter.%20Then%20replace%0A%20%20%20%20it%20with%20the%20matched%20string%20followed%20by%20a%20dash%20%20%20%20%0A%20%20-%20Return%20the%20result%20lower-cased%0A*%2F%0A%0A%0AspinalCase('thisIsSpinalTap')%3B%0A)


### Day 26: February 2, 2017

**Today's Progress**: Fibonnaci algorithm.

**Thoughts** This was a toughie!

**Link(s) to work**
1. [Sum Fibonacci Numbers](http://)

### Day 27: February 3, 2017

**Today's Progress**: Sum algorithm.

**Thoughts** This was a toughie!

**Link(s) to work**
1. [Sum all Primes](https://www.freecodecamp.com/challenges/sum-all-primes#?solution=%0Afunction%20sumPrimes(num)%20%7B%0A%20%20%0A%20%20var%20arr%20%3D%20%5B%5D%3B%0A%20%20while%20(num%20%3E%200)%20%7B%0A%20%20%20%20arr.push(num)%3B%0A%20%20%20%20num--%3B%0A%20%20%7D%0A%20%20%0A%20%20%0A%20%20var%20sum%20%3D%200%3B%0A%20%20%0A%20%20%2F%2F%20Call%20the%20isPrime%20call%20back%20function%20on%20each%20number%20in%20the%20arr%20and%20then%20add%20it%20to%20the%20sum%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20arr.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20if%20(%20isPrime(arr%5Bi%5D)%20)%7B%0A%20%20%20%20%20%20sum%20%2B%3D%20arr%5Bi%5D%3B%20%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20%20%20%0A%20%20function%20isPrime(num)%20%7B%0A%20%20%20%20if%20(num%20%3C%202)%20return%20false%3B%0A%0A%20%20%20%20%2F*%20%0A%20%20%20%20%20%20An%20integer%20is%20prime%20if%20it%20is%20not%20divisible%20by%20any%20prime%20less%20than%20or%20equal%20%0A%20%20%20%20%20%20to%20its%20square%20root%0A%20%20%20%20*%2F%0A%0A%20%20%20%20var%20q%20%3D%20Math.floor(Math.sqrt(num))%3B%0A%0A%20%20%20%20for%20(var%20i%20%3D%202%3B%20i%20%3C%3D%20q%3B%20i%2B%2B)%20%7B%0A%20%20%20%20%20%20if%20(num%20%25%20i%20%3D%3D%3D%200)%20%7B%0A%20%20%20%20%20%20%20%20return%20false%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%0A%20%20%20%20return%20true%3B%0A%20%20%7D%0A%0A%20%20return%20sum%3B%0A%7D%0A%0AsumPrimes(10)%3B)

### Day 28: February 10, 2017

**Today's Progress**: Algorithms involving filter

**Thoughts** Ok, ok so I missed a week of commits to this log. Whilst I have still been working on the algorithms I hadn't actually passed any since they became more mathematically-focused, so I didn't feel I had anything to commit. Honestly, this filled me with a feeling of inadequacy and failure but this is something I need to find a resolution for in the future. If I get stuck on something for too long, it'd probably be wise to move on to something else. I can always come back to it later with a fresh head. Otherwise the two algorithms went very well.

**Link(s) to work**
1. [Finders Keepers](https://www.freecodecamp.com/challenges/finders-keepers#?solution=%0Afunction%20findElement(arr%2C%20func)%20%7B%0A%20%20var%20num%20%3D%200%3B%0A%20%20%0A%20%20%2F*%20arr.filter(func)%20would%20return%20an%20array%20with%20all%20values%20that%20pass%20the%20truth%20test%2C%20so%0A%20%20%20%20%20it%20makes%20sense%20simply%20to%20target%20the%20first%20element%20in%20that%20array%20and%20assign%20it%20to%20the%20%0A%20%20%20%20%20num%20variable.%0A%20%20*%2F%0A%20%20%0A%20%20num%20%3D%20arr.filter(func)%5B0%5D%3B%0A%20%20%0A%20%20return%20num%3B%0A%7D%0A%0AfindElement(%5B1%2C%203%2C%205%2C%209%5D%2C%20function(num)%7B%20return%20num%20%25%202%20%3D%3D%3D%200%3B%20%7D)%3B%0A)

2. [Drop it](https://www.freecodecamp.com/challenges/drop-it#?solution=%2F%2F%20Drop%20all%20elements%20from%20the%20start%20until%20one%20meets%20the%20true%20condition%2C%20and%20include%20all%20elements%20after%20that%20regardless%20of%20whether%20they%20are%20true%20or%20not.%0A%0Afunction%20dropElements(arr%2C%20func)%20%7B%0A%20%20%0A%20%20var%20newArr%20%3D%20%5B%5D%3B%0A%20%20%0A%20%20%0A%20%20if%20(arr.indexOf(arr.filter(func)%5B0%5D)%20%3D%3D%3D%20-1)%20%7B%0A%20%20%20%20return%20newArr%3B%0A%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20newArr%20%3D%20arr.slice(%20arr.indexOf(arr.filter(func)%5B0%5D)%20)%3B%0A%20%20%20%20%20%20return%20newArr%3B%0A%20%20%7D%0A%20%20%0A%20%20%2F*%0A%20%20%20%20If%20the%20index%20of%20the%20first%20element%20to%20match%20the%20predicate%20function%20is%20-1%2C%20i.e.%20no%20element%20%0A%20%20%20%20coerces%20to%20true%2C%20then%20return%20an%20empty%20array.%0A%20%20%20%20%0A%20%20%20%20Otherwise%2C%20slice%20the%20array%20from%20the%20index%20of%20the%20first%20value%20that%20matches%20the%20predicate.%0A%20%20%0A%20%20*%2F%0A%0A%7D%0A%0AdropElements(%5B1%2C%202%2C%203%2C%204%5D%2C%20function(n)%20%7Breturn%20n%20%3E%205%3B%7D)%3B%0A)

### Day 29: February 13, 2017

**Today's Progress**: Struggled with more algorithms, passed one.

**Thoughts** Have not been well for a few days.


1. [Everything Be True](https://www.freecodecamp.com/challenges/everything-be-true#?solution=%0Afunction%20truthCheck(collection%2C%20pre)%20%7B%0A%20%20%2F%2F%20Is%20everyone%20being%20true%3F%0A%20%20%0A%20%20%2F%2F%20create%20an%20array%20to%20which%20a%20%22t%22%20will%20be%20pushed%20if%20the%20predicate%20is%20true%2C%20and%20an%20%22f%22%20will%20be%20pushed%20if%20the%20predicate%20is%20false%0A%20%20var%20bools%20%3D%20%5B%5D%3B%0A%20%20%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20collection.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20if%20(collection%5Bi%5D%5Bpre%5D)%20%7B%0A%20%20%20%20%20%20bools.push(%22t%22)%3B%0A%20%20%20%20%20%20%0A%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20bools.push(%22f%22)%3B%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%7D%0A%20%20%0A%20%20%0A%20%20%2F%2F%20If%20%22f%22%20doesn't%20appear%20in%20the%20bools%20array%2C%20then%20all%20values%20must%20be%20%22t%22%20and%20hence%20all%20elements%20in%20the%20collection%20are%20truthy%0A%20%20if%20(bools.indexOf(%22f%22)%20%3D%3D%3D%20-1)%20%7B%0A%20%20%20%20return%20true%3B%0A%20%20%7D%20else%20%7B%0A%20%20%20%20return%20false%3B%0A%20%20%7D%0A%20%20%0A%7D%0A%0AtruthCheck(%5B%7B%22user%22%3A%20%22Tinky-Winky%22%2C%20%22sex%22%3A%20%22male%22%7D%2C%20%7B%22user%22%3A%20%22Dipsy%22%2C%20%22sex%22%3A%20%22male%22%7D%2C%20%7B%22user%22%3A%20%22Laa-Laa%22%2C%20%22sex%22%3A%20%22female%22%7D%2C%20%7B%22user%22%3A%20%22Po%22%2C%20%22sex%22%3A%20%22female%22%7D%5D%2C%20%22sex%22)%3B%0A)
