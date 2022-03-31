# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jessica Liu**

Time spent: **10** hours spent in total

Link to project: https://noon-fuschia-second.glitch.me/

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
https://recordit.co/51jpGAWpVZ

https://recordit.co/ciYHwoznwp 
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used google to figure out the frequencies for notes I wanted, to find pictures to customize my buttons, and to find the hex codes of colors I wanted for my buttons (I figured out I could do this from w3 schools). I used w3 schools and “webplatform.github.io” as references on how to implement different background images for my buttons, and also looked at general syntax for javascript, css, and html,  just to try to understand the code more.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The most challenging aspect of this project was figuring out how to customize my button images (when they are pressed) and how to change the colors. I do not have any background in HTML, javascript, or css, so I was confused on where to begin. I began with looking at the hyperlinked resources on the prework guide, and continued looking on the w3 website until I found more clues on what to do and what specifically to look into. From there I was able to search for more specific questions, where I found some examples on “webplatform.github.io”. I was able to figure out how to only show pictures when the buttons were clicked in css.
I also did not know how to find the color options for the buttons in css. I tried to look up the list of colors, but came across a w3 school article that talked about hex codes and how you could use it to get different colors. I tried out many colors to find a color palette I liked and found the hex codes for those colors. Both of these issues were problems with optional tasks, but I really wanted to customize the game to be a better representation of my style and personality.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing my submission, I would like to learn more on how exactly backend and frontend computing work together, as I do not have too much experience with web development. However, I am a new member of Fullstack at Brown, which is a club that works on full stack development, so I am excited to explore how the two work hand in hand to create an efficient website. I would also love to learn more about how to test different parts of my website without having to run through the entire game to check every detail. For example, writing tests to check the functionality instead of running through the whole game, after you add something new, seems more efficient. I am curious to see how different testing is in comparison to what I do for my classes in languages like python and java.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If  I had more time for this project, I would have 3 different difficulty levels (easy, medium, and hard), which the player can choose using a dropdown menu. I would have to write a new function that takes in the input (the player's choice), create different patterns for each level, and  have a different amount of buttons for each level (6 for easy, 10 for medium, and 20 for hard). I would also like to keep track of the player's personal best score (1 point for each right guess) for each level on the screen, while also displaying their current score



## Interview Recording URL Link

[My 5-minute Interview Recording] https://www.loom.com/share/06cd3c7bb5de425080b8d83a19b6d3dc


## License

    Copyright Jessica Liu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
