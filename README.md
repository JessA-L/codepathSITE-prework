# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jessica Allman-LaPorte**

Time spent: **5** hours spent in total

Link to project code: https://glitch.com/edit/#!/codepath-pre-work-simone <br>
Link to live project: https://codepath-pre-work-simone.glitch.me


## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn



## Video Walkthrough (GIF)

* GIF of User winning the game after guessing a complete pattern: 
<br><img src=https://recordit.co/SpQxFpdpb1.gif width=250><br>

* GIF of "Start" button toggling between "Start" and "Stop" when clicked.; <br>
    Then, User loses the game after an incorrect guess: 
    <br><img src=https://recordit.co/uVFhAFh0ft.gif width=250><br>



## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.<br><br> 
    MDN. “Array.prototype.length” 
    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length <br>
    Stackoverflow. “How to append something to an array?” https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

	The most difficulty I had was with creating the “guess” function. More specifically, I was easily able to write the program to where it would play the sequence and then accept a guess. If the guess matched the last tone of the sequence, it counted it as correct. The challenge I had was in writing the program so that it accepted more than one tone as the guess and to check whether each tone in the sequence of the guess was correct. 
    
	I used a few different methods to alleviate this problem. First, I created a “cheat sheet” in a notebook, which helped me remember the variable names and what they were being used for. This helped me to realize that I had used the progress variable instead of guessCounter. Then, I updated the pseudocode in the program to make sure it matched the instructions and flowchart precisely. I noticed that I missed the part of the instructions where it said to use nested conditional statements (I had not nested my conditional statements). I find that taking the time to reorganize and plan outside of the IDE is helpful in finding a solution. It was also helpful to take a second look at the html file, as I had forgotten where guess() was being called. This is where using Javascript had the steepest learning curve for me in this pre-work, since my programming experience has been with Python and C. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Jessica Allman-LaPorte]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.