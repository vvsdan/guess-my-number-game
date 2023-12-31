# Mini Project - Guess My Number!

This is a Javascript learning project focusing on DOM manipulation and creating checks for correct values. 
## Preview

![Guess The Number Game](https://dj-project-previews.s3.amazonaws.com/js-projects/guess-the-number-game.png)
## Live Project

This project is hosted on Netlify, please click [here](https://moonlit-entremet-aafb1d.netlify.app) to play
## How To Play

At the beginning of the game a secret number is generated, 1 to 20 inclusive. 

You will then click inside the field on the left side, enter your guess, then click "Check!" or press the enter key. 

If the correct value is guessed, the screen will turn green, letting you know that you've selected the correct number! 

Otherwise, each guess will tell you if your number is too high, or too low until the correct number is selected. 

High score is based on the number of guesses it takes. 

Did you win? Press "Again!" in the top left corner to try for a higher score! 
## About The Project

- The secret number is decided by Math.trunc and Math.random, generating a random number within the decided range of 1 to 20. 
- This project involved some DOM manipulation based upon imput from the user (i.e, guess too high, too low, or correct based on input).
- The project considers edge cases, for example, "0" is not recognized and letters are disallowed. 
- A high score is stored within the user's session. A high score is maintained when the user presses "Again!" in the top left corner, and other DOM elements are reverted to the initial state. 
## Acknowledgements

This project was completed as part of [Jonas Schmedtmann's](https://github.com/jonasschmedtmanny) Javascript course. 
