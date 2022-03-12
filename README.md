# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Irfan Khan**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/codepath-prework?path=index.html%3A1%3A0

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

<img src="http://g.recordit.co/N7gtGMMYVx.gif" width=500>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

 To complete this project, I used "UDEMY 2022 complete WEB Development Bootcamp" to learn more about JavaScripts and their implementation.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
 
The first part of the project where I had to set up the webpage wasn't a challenge. I had prior experience in HTML and CSS, which I extensively used to do personal  projects. Unfortunately, I did not have any knowledge about Javascripts, and it was a challenge for me to write the logic for the game without understanding   anything at first. I didn't want to write the program without knowing how everything worked together. So, to overcome this challenge, I watched some videos from the "Udemy 2022 complete WEB Development Bootcamp" and learned the essential topics needed to implement Javascript. After that, I understood the code's logic and found it easier to focus. Once I was done with the game's basic functionality, I implemented some optional features to make the game more exciting and challenging at the same time. One feature was that the game would select random patterns every time the game started. So, I had some issues creating a random array of elements but later, I fixed that by creating two simple functions (getPattern and clearPattern). Every time the game starts, getPattern is called to create a random pattern, and clearPattern is called every time the game stops.
Apart from that, I found this project exciting and was fun to implement. In addition, I was able to learn a new programming language (Javascripts) that I can use to enhance my projects and build websites in the future.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

While working on this project, I learned essential elements of WEB development, especially how we can control the UI (Front-end) from the back-end. Everything seems compact and powerful. Even then, I have some questions about WEB development: "How to optimize our website?", "How to add security layers to a website?" and "How to deploy and manage our websites?" These are some of the questions I am looking forward to learning through the Codepath SITE internship program. This knowledge will help me become a successful WEB developer in the future, and I can pursue my goals right after graduation with sufficient experience.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
 
Although the required steps of the projects were enough to build a fully functional game, I would have loved to add some extra twitches to enhance the experience. Unfortunately, this is my midterm week, and I had very little time to add those extra utilities. 
If I did have the time, I would have implemented three different tier game experiences: Beginner, Moderate, and Pro. Each level would have a different number of buttons and game speed. For example, the "Beginner" mode would have four buttons but constant speed. The "Moderate" mode would have six buttons and three attempts, but each time the guess is made, it would increase the game speed by a certain amount. The "Hard" mode would have eight buttons, and it would be similar to the moderate mode but with only one attempt. This enhancement would have made the game more exciting and challenging at the same time.
At the start of the game, it would show the details of each mode, and the user could select which mode they want to play. Then the game would start with the required number of buttons and other necessary specifications.


## Interview Recording URL Link

[My 5-minute Interview Recording] 
https://www.loom.com/share/03dfac708ba845e1bee260f94fd6f58a


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
