# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Prathisha Shyamsundar

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/sweet-uneven-book

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
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
 https://cdn.glitch.com/8ee8e58d-a387-44d6-8e29-eb7c9141b277%2Fgif1.gif?v=1616554633449
 
 https://cdn.glitch.com/8ee8e58d-a387-44d6-8e29-eb7c9141b277%2Fgif2.gif?v=1616554632390
 
 https://cdn.glitch.com/8ee8e58d-a387-44d6-8e29-eb7c9141b277%2Fgif3.gif?v=1616622851846



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

  I used some W3schools webpages to guide me with some CSS syntax.



2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I encountered in creating this project was to let the user have 3 strikes instead of only having one. 
At first, I had trouble figuring out whether the user had to try again on the same clue sequence or if the game 
should move on, but I ended up interpreting that the game should just move on to the next clue sequence after 
the mistake. The other big issue I had was trying to implement this because I was trying to update the mistake 
counter variable, but it would increment altogether since I was not updating it to move on to the next turn. 
Due to this, I tried to just stop incrementing it more than once for that turn and went through multiple versions and implementations of the guess function by using while loops, multiple if statements, and still could not get it to work. I finally got it to work a little by coming up with a whole other solution altogether and was checking how many mistakes there were before proceeding to call the loseGame function. If it was not more than 2, I would not call the function but increment the counter. However, I figured out later that this did not work as I intended it to either. So, I went on to try to solve this problem and ended up figuring out that I was not keeping account of the turn and the progress. So adding two more lines of code finally solved my problem. It took a while, but I tried again and again until I figured it out.



3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Although I know how to use HTML, CSS and basic JavaScript, I want to learn React and Node JS and how these features can improve web development tremendously. I want to know if using React would be easier to implement this project than how it is implemented now. I also would like to find out how using Bootstrap would affect the UI and how I can make it look better. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would try to make the UI better and make it look more appealing. I would also have completed all the optional components including the timer for the game. I would also try to take the 3 strikes feature further for people who might have trouble and let them have 3 tries for each clue sequence, so they can try it again until they get it right up to 3 times. Furthermore, I would also maybe implement a hint feature which the user could click on if they want a hint and this functionality would light up the button they are supposed to click.




## License

    Copyright [PRATHISHA SHYAMSUNDAR]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
