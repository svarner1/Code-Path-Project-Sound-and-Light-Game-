# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sydney Varner**

Time spent: **6.5** hours spent in total

Link to project: https://glitch.com/edit/#!/dandelion-kaput-pelican

## Required Functionality

The following **required** functionality is complete:

* [+] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [+] "Start" button toggles between "Start" and "Stop" when clicked. 
* [+] Game buttons each light up and play a sound when clicked. 
* [+] Computer plays back sequence of clues including sound and visual cue for each button
* [+] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [+] User wins the game after guessing a complete pattern
* [+] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [+] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/wlPwQ10.gif)
![](https://i.imgur.com/RnrTzB9.gif)
![](https://i.imgur.com/y25epUD.gif)
![](https://i.imgur.com/ERJzBTo.gif)
![](https://i.imgur.com/dz9Iyk2.gif)

Gif Created with ezgif.com.


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    I did not use any.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    I personally ran into a few challenges when attempting to implement some of the optional additions to the game. 
    Although these components were optional, I wanted to display that I took the initiative to go beyond what was required. 
    Unfortunately, the additions I wanted to add (reducing the time for each turn and adding an image to the buttons when clicked
    ,creating a random secret pattern) were pretty tricky for me to figure out to get them working smoothly with the code 
    I wrote to get the basic game working. 
    
    When I attempted to reduce the time for each turn, I ran into issues with the general usability of the program. Regardless of the amount of 
    miliseconds I chose to reduce from the time, it didn't seem like giving the sequence at a quicker pace worked very well. Either the pacing 
    would be too fast or slow enough that it did not seem like the timing was reducing. 
    
    When I attempted to create a new secret pattern each time the game was played, I did write a JavaScript function to create an array with random numbers.
    However, the game would not play the sequence after making this change.
    
    The issue I ran into when trying to add images to the buttons was just generally being sort of usure how to implement this feature. I thought to add an image inside
    the button and then use JavaScript (either using "getElementByID" and adding a class that gives a hidden display or another way).
    
    The last few hours of the time I spent working on the game included looking up resources for how to implement these features. 
    As well as writing and rewriting my code. I think I might have been able to implement 
    these features if I dedicated more time to the project.
    
    However, I would say that I still did overcome my challenges in a way. I am happy with the outcome of this game and I had a fun 
    time working on it! I did learn about some aspects of web development that I was unsure about, which was mainly how to 
    use JavaScript to make HTMl projects interactive). I now definitely think I might have been better off sticking to doing the general
    requirements and possibly adding more to the html and css pages to make my game more unique because I have more comfortability 
    with these parts of the program rather than JavaScript. I overcame my challenge by changing my goal in completing the pre-work, which
    ended up being to simply fulfill the requiremnts and to make sure my game worked smoothly in the end.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
    I would like to learn about the frameworks that most web developers use on a daily basis. I have heard of many (for example, such as react).
    In general, I have an understanding that most programmers choose the framworks, IDE's, etc that they are most knowledgeable about and 
    have the most comfortability with. But, I would like to in general learn about the different technologies used to create web sites
    and what the pros and cons of the various ones are. Further, I would like to determine which frameworks would be most useful to me!
    
    Overall, I would definitely like to develop some strong JavaScript skills.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
   I would add the few optional features I intented to implement. I would also add another page to the HTML project, such as a welcome page that gives basic intructions on how to play. 
   I would also add a feature to give the users a high score (which would also most likely require a longer sequence for the buttons).
   


## License

    Copyright [Sydney Varner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
