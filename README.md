# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Luan Ho

Time spent: 7

Link to project: https://github.com/luanho2018/Clickly-Color-Game

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial - 
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial - 
* [x] More than 4 functional game buttons -
* [x] Playback speeds up on each turn - 
* [x] Computer picks a different pattern each time the game is played - 
* [x] Player only loses after 3 mistakes (instead of on the first mistake) - 
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] User has a limited amount of time to enter their guess for the whole game

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
  - More buttons
  - Time limit that decrements by an amount of time
  - More sounds
  - Ability to select how the game is played. 
    - For example, having to drag a button into another button in a pattern.
  - Infinite time mode?
  - Scoreboard
  - (I did not implement these features but would have loved to given more time)

## Video Walkthrough

Here's a walkthrough of implemented user stories:
Walkthrough video:
https://www.youtube.com/watch?v=Kvr_q3QhFYo&ab_channel=LuanHo

Gifs:
![](https://i.imgur.com/E73qapU.gif)
![](https://i.imgur.com/GxEQT7Z.gif)
![](https://i.imgur.com/9iqAvmQ.gif)
![](https://i.imgur.com/ralcY1x.gif)
![](https://i.imgur.com/AGTuLIq.gif)




## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://forums.tumult.com/t/audio-play-error-with-javascript/13418
I used this to find out my issue about the AudioPlayer error. Though it told me to do other steps, I decided it would be better to use another browser. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
I used this for a method that used Math.random to bound it to have a max int.

https://stackoverflow.com/questions/8818543/how-to-give-html-button-tag-an-image/8818584
I used this to find out how to change the button to pictures when clicked 


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One problem I had was that the sounds from clicking each button was not working. I thought I had followed the directions from the github perfectly and tried repeatedly to read the instructions word by word to see if I had missed something but to no avail. I tried to delete all the code to write the project from the beginning 3-4 times but nothing still worked. I even tried to remake the whole project by creating a whole new glitch. I did this 3 times and it still didn???t work. Finally, I wanted to give up and try to email Codepath but I decided to try again the next day to see if I had been doing something wrong the whole time. The next day, the same problem persists. I dug deeper into this problem using the JavaScript developer console and found an error that read, ???AudioContext not supported.??? I decided to look to the internet to find a solution. I came across a website that stated that my version of Safari did not support ???AudioContext???, which was the main object used to create the sound in the first place. 
There on, I downloaded Google Chrome, redid the entire project once again, and found everything working. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

A question I have about web development is about the intricacy of the developer console. At first glance, it seems like its difficult to read and use.I wonder if there is an easier way to debug code by using an easier to understand console. In comparison to an IDEA such as IntelliJ where I do most of my coding, the console seems so tedious to work through. Another question that I have about web development is how developers keep up with all the latest technology in the web such as new javascript code and functions. I've always questioned if and how developers have to constantly update their website when some technology comes out. For example, if a new and improved "AudioPlayer" was created, how would developers implement that into their sites? Would they have to recreate everything in code or do they generally just ignore the new technologies because their current code is already working.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time on the project, I would want to implement this into a more entertaining and interactive game. I would have wanted to create a "Start Game" screen that would transition into the actual game. Something that I thought about doing while making the project itself is possible implementing a function that would allow the buttons to split into many smaller buttons. Each button would act as a new button that would become apart of the game. 



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
