# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Sadia Akhter

Time spent: 10 hours spent in total

Link to project: https://glitch.com/edit/#!/broken-glaze-composer?path=index.html%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:


- [ ] List anything else that you can get done to improve the app!
-  add a button which could switch between dark mode and light mode

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
https://i.imgur.com/L5mbHa0.gif

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random#getting_a_random_integer_between_two_values
https://www.rapidtables.com/web/css/css-color.html#red
https://www.educative.io/edpresso/mathceil-mathfloor-and-mathround-in-javascript


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I got my first exposure to working with Javascript through this project. Picking up Javascript wasn’t as hard as I thought since I had previous programming experience in Python and Java. The most challenging part of this project was implementing the feature where the users have 3 tries in the game. The visual logic given on the instruction was very helpful for me to understand the feature. Once I understood the logic, coding up the logic was pretty straightforward at that point. So, I broke down the problem into smaller chunks.
I had a variable to keep track of the tries. First, I checked if the first guess was correct, if not I decemented the value by 1. When the user makes corrections, I added more logic to see if the user keeps making correct choices and when the number of correct guesses is equal to the length of the array of the pattern of the tiles, I could conclude that the user won the game. I also console logged the values in every step of these conditionals to make sure that my logic was sound.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Through this project, I got exposure to working with Javascript and got to learn how different components in Javascript interact with each other in the front end. This experience made me more interested in web development. Now that, I have learned some basics of Javascript, I would love to probably pick a more robust Javascript framework like React.js to build faster, scalable and simple front end apps. Even though I enjoy building UI components in the front-end, I would love to learn more about full stack development for example how backend and front end communicate with each other, connect to a database, authenticate users, etc. In simple words, I am more eager to learn about full stack development.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more hours to work on this project, I would have loved to finish up all the optional features. I would implement the timer because I think that would make the game more interesting and add more difficulty for the users to play the game. I could add a plus and minus button so that the users could change the timer.
I would also try to make the UI more visually appealing. With more time, I would have also added a button that users could toggle to change the theme of the game. For example, make the UI change from normal mode to dark mode or vice versa.




## Interview Recording URL Link

[My 5-minute Interview Recording]https://missioncollege-edu.zoom.us/rec/share/B52r1fwr45Nkwsuz_Z78_vkCM1jMyYuBXNqRsng9ZWT-48aTfMYpMpZCeg8iv7UN.90FV1LMxHFVTcUrc



## License

    Copyright [Sadia Akhter]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
