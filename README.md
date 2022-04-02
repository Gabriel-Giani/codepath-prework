# Codepath-prework

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Gabriel Giani**

Time spent: **5** hours spent in total

Link to project: (https://glitch.com/edit/#!/codepath-pre-work-project)

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
![](http://recordit.co/L2xjrh4cTs)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
No outisde resources were use.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered in the creation of this submission was when implementing the feature of sounds for the buttons. The instructions stated, at the top of your script.js files, add another two Global Variables that were given. After copying and pasting the 2 global variables, I proceeded to add the code for generating sounds to the bottom of the script.js file. As I added the code, many lines of the code I had added were red with error warnings appearing. The message of the error warning was that tonePlaying was not defined.  I looked back at the variables and could not find the tonePlaying variable. Looking at the previous step in the instructions, I could see where I had made my mistake, “at the top of your script.js files”. I had interpreted “at the top”, as the first line of the file. It was there where I would also find another mistake. Copying exactly from the instructions, one of the lines was commented out, “// var tonePlaying = false”. After removing the comment and rearranging the variables to the global variables area, I was able to resolve the issue I encountered. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing my submission and seeing how web pages are developed, I have questions regarding how websites can be optimized for so many different devices. Websites can be browsed from so many different devices, with the experience on most devices being very similar. For example, devices such as smartphones are mostly used in vertical or portrait style, while computers and most larger devices are use in horizontal or landscape style. How can websites be work so well on such a wide array of devices? With my submission, I had a hard time managing the preview of the game on just one screen. The way the buttons in the game would move depending on the size of the windows did not feel very polished and I was not very pleased with the way it came out. Optimizing the way web pages adjust to the devices display would be something I would like to learn about.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would like to improve the layout of the buttons. The way the buttons adjust depending on the size of the window was not aesthetically pleasing. I felt that with more time, it is something that could be fixed and it would greatly help with the visuals of the game. The pattern of the game was also something I would have like to work on more. An idea I had considered was possibly adjust the timing, sounds, and selection of buttons to match up with the tune or beat of a familiar song. 



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
