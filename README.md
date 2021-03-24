# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Vincent Langlois**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/four-spectrum-asterisk?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [y] Game buttons each light up and play a sound when clicked. 
* [y] Computer plays back sequence of clues including sound and visual cue for each button
* [y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [y] User wins the game after guessing a complete pattern
* [y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [y] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [y] Computer picks a different pattern each time the game is played
* [y] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- [Y] shorten the length of the game for recording and testing purposes

## Video Walkthrough

Here's a walkthrough of implemented user stories:
http://g.recordit.co/ltMfT1fEXd.gif - Basic functionality plus additonal button and shorten playtime
http://g.recordit.co/epEG4bYQNI.gif - Three Guesses functionality plus randomized pattern demonstration



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I used this link to help me understand how to use random number generators with arrays in JavaScript: https://javascript.plainenglish.io/how-to-generate-an-array-of-random-numbers-in-javascript-f883de667e84]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[The most challenging part of this submission was creating the game logic within the gues function. This was due to the code being provided for us, meaning I had to look over preexisiting code to see what functions I could use and what variables I had. To overcome this issue, I looked over the UML chart provided to map out how the if-else statements should've been structured. From that, I sought out variables existed that could allow for the boolean conditionals to be constructed, such as progress. Using all that I could, I was able to construct the guess's game logic with ease.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I'm curious about how far JavaScript can go with web development. I know its a language I've been wanting to understand for quite a while, and making these browser-based games may be a way I can pursue JavaScript and learn from web development knowledge as well.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I would make a few additional modes with the game. These modes would include one where the user has to use only the audio cues to pick the right selection, and one where the location of the buttons would change each time, requiring the user to use only the color and the audio of the button to make their selection. The colorless mode can also be applied to that mode.]



## License

    Copyright Vincent Langlois

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.