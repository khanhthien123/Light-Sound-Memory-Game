# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **#** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Testing game interface](http://g.recordit.co/RovxOOda0O.gif)
![Toggling Start/Stop. Checking winningGame function](http://g.recordit.co/wRJUsHU7MM.gif)
![Giving players 3 strikes. Checking losingGame function](http://g.recordit.co/hq5RUpSRIf.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[https://www.w3schools.com/
https://www.tutorialsteacher.com/javascript/]


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[Although all the guides to complete these tasks have been laid out, there’s a few challenges giving a hard time. One of them is to understand why we are doing it this way. For example, when we created some constants and some global variables, I was very confused of why we had to create them and how they affected each other. And when we wrote the 2 functions: playSingleClue and playClueSequence, I was lost. I didn’t know what we were doing at that time, so I decided to write all the variables on paper, manually execute each line of code in those 2 functions and try to understand what was going on. Especially when there was a global method setTimeout() which was used in those 2 functions, and when I played the game, I noticed what should happen at each line of code. Gradually, I wrapped my head around what was actually going on but there was something missing. The “delay” variable should distance between 2 consecutive clues because it was increased over time. For instance, delay was first initialized with 1000ms, so the function waited 1000ms and then ran the function playSingleClue, then it was added by clueHoldTime and cluePauseTime, which meant it would wait 1000ms+ to play the next clue, but the game didn’t seem to work that way or I didn’t feel it that way.
All in all, running each line of code and see the changes in each variable gives me a much understanding of what’s going on and give me more confidence in modifying any features.
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[I haven’t deployed any web into production so I’m curious how to publish a website, and how we manage our website during production.
Also, I practiced back-end development using Flask or Django (Python web frameworks) as servers. For database, I used SQLite and SQL. So, do you use Django in your tech stack? If not, what do you use? Beside database and server, what else should we care about in the back-end?
What’s the hardest part in back-end development in particular? And in web development in general?
Would web development be saturated in the future because it’s so popular at present, in another word, I’m curious about web developer demand in the next 7 years?
]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[Add background music while playing, when winning and when losing the game.
Lengthen the pattern as the game goes on until the player loses and record their highest.
Create log-in system to keep track of highest score and there would be a dashboard showing the player’s score.
Give players the choice of difficulty. Slow, Moderate and Fast or 4 buttons, 6 buttons and 8 buttons.
I think completing the above functions would take more than a few hours, but the result would be a very interacting game and a place for people to enjoy.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


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