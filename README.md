# test-project-1
CodePath Test Project - Summer 2020 Application
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Susan Guerrero

Time spent: 3 hours spent in total

Link to project: (https://glitch.com/edit/#!/light-sound-?path=index.html%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [Yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Yes] Game buttons each light up and play a sound when clicked. 
* [Yes] Computer plays back sequence of clues including sound and visual cue for each button
* [Yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Yes] User wins the game after guessing a complete pattern
* [Yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Yes] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)

##GIF
https://cdn.glitch.com/1f27d21d-43f8-467e-a8cd-47e997364c9a%2Fthumbnails%2Fezgif.com-video-to-gif.gif?1616654410077
- also could be found under "assets"


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[developer.mozilla.org - https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_Web_Audio_API]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[I had a reoccuring issue regarding the AudioContext variable in line 62. I used the developer tools to help me identify the problem. After analyzing the intructions over and over I couldn't understand why there wasn't any sound coming from the game. I Googled my question and after reading upon the same issue other pople had on developer.mozilla.com i was able try out the suggested alternatives of creating an instance of the audio context. In my case const audioContext = new AudioContext(); didnt work and window.webkitAudioContext; did. Not knowing much of JavaScript aside from the basics made me spend a lot of time trying to debug this error by myself, I had to ultimately refer to googling my issue.  ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I hope to undertand better more how JavaScript works and what other types of libraries JavaScript has to offer in order to enhance our projects. I found HTML and CSS really fun and a great way to express myself creatively. I loved it! I look forward to continue making projects of my own.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time to devlop the game further I would want to make the game more acessable and visually aimed for a specific audience. An example could be, adapting it towards children. Maybe the buttons could of been different anaimals with animal sounds and there could of been different levels with different there such as, space, numbers, languages and so much more. ]



## License

    Copyright [Susan Guerrero]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
