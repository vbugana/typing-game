# Typing Game

Game to beat the clock by typing random words

## Description

This is a JavaScript code for a word typing game. The game displays a random word from an array and the user has to type the word correctly within a certain time limit. The game keeps track of the score and difficulty level.

The code starts by selecting the necessary elements from the HTML document using their IDs. It then creates an array of words to be used in the game and initializes variables for the random word, score, and time. The difficulty level is set using the `localStorage` API to save the user's preference for the next time they play the game.

The game then focuses on the input field for the user to start typing and starts the timer using the setInterval method. The `getRandomWord` function generates a random word from the array, and the `addWordToDOM` function displays the word on the screen. The `updateScore` function increments the score when the user types a correct word. The updateTime function decreases the time by 1 second and updates the time element on the screen.

The `gameOver` function is called when the time runs out, displaying the user's final score and a button to restart the game.

There are two event listeners included in the code. The first listens for user input and compares it to the random word, and then updates the score and time accordingly. The second listens for the settings button to be clicked, toggling the display of the difficulty level settings form. When the user changes the difficulty level, it is saved in `localStorage` and used in the game.


## Project Specifications

- Create game UI including a difficuly setting
- Generate random word and place in DOM
- Score increase after word is typed
- Implement timer
- Add certain amount of time after word is typed based on difficulty
- Store difficulty setting in local storage

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
