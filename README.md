# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Amy Tse

Time spent: 5 hours spent in total

Link to project: https://memory-game-proj.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] 

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://recordit.co/00WbvvPebC


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.w3schools.com/css/css3_buttons.asp
https://www.w3schools.com/js/js_random.asp
https://www.w3schools.com/cssref/pr_background-image.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I encountered a challenge when randomizing the pattern for each round. Specifically, I was unsure of how to use the randomize function. 
Since I have never coded in Javascript before, it was a little tricky figuring out how to implement a loop since I'm used to C++ and Python loops. Luckily,
its quite similar to C++, and with a little help from searching up how to implement the randomize function, I was able to figure it out. Also, displaying images only when the button is pressed was a bit tricky to figure out, but 
after looking at material online, I was able to figure it out by implementing a class for the image and changing its visibility when the button is hovered over. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this miniproject, I am interested in how to create other elements of a website. For example, creating a toolbar or menu, 
or even a widget. Furthermore, I am curious about how to create, say a locked page that requires a password to enter. 
Or, a small window that opens up when you click a button. To what extent can a button be programmed to?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a couple more hours to work on this project, I'd like to work on adding new features and working on the design of the game.
- Adding corresonding animal sounds bites instead
- Adding a timer
- Every time someone wins the game, a new button, or animal is added. Everytime you lose, an animal (button) is taken away.
- Every time you win the game, you earn money and you can use that money to buy new animals, or buttons. 
- Adding a scoreboard: shows how many times you have played, and a list of your personal records. Perhaps, if it was an online game, a feature that would compare scores to other players.
- Adding a feature where the player can choose their difficulty, and how long they want the pattern to be.
- The more difficult, the faster the hold time, and the more buttons that would exist.
-Another theme idea I had for this game: music themed.
-Each button is a musical note, and there would be a database of patterns stored. A pattern is randomly chosen, and the player must continue playing until they finish the whole pattern, or if they are able to guess the song. There would be a box on the bottom of the page that would allow the player to input a title or artist. (simple tunes like twinkle twinkle little star)


## License

    Copyright [AMY TSE]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.