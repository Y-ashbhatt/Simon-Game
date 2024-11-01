# [Simon Game](https://y-ashbhatt.github.io/Simon-Game/)

## Overview

The Simon Game is a classic memory game that challenges players to repeat increasingly complex sequences of colors and sounds. This implementation of the game is built using jQuery, providing a fun and interactive experience.

## Features

- **User Interaction**: Players can start the game by pressing any key and follow the color sequence by clicking the buttons.
- **Visual Feedback**: Buttons light up and play sounds in response to user interactions.
- **Game Logic**: The game generates a random sequence of button presses that the player must replicate.

## What I Learned

This project taught me valuable concepts in web development, including:

1. **Event Handling**: Detecting user actions with keypress and click events.
2. **Game Logic**: Generating random sequences and comparing user input using `nextSequence()` and `checkAnswer()`.
3. **State Management**: Managing game state with variables like `started`, `gamePattern`, and `level`.
4. **DOM Manipulation**: Using jQuery to update the HTML and animate buttons.
5. **Audio/Animation**: Playing sounds and adding visual effects with `playSound()` and `animatePress()`.
6. **Error Handling**: Restarting the game when the user makes a mistake with `startOver()`.

Overall, this project taught me how to build interactive games with JavaScript and jQuery.

## Installation

To run the Simon Game locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Y-ashbhatt/Simon-Game.git
   ```

2. Navigate to the project directory:

   ```bash

   cd Simon-Game
   ```

Open the index.html file in your web browser to play the game.

## Author

**Yash Bhatt**  
[GitHub](https://github.com/y-ashbhatt)  
[LinkedIn](https://www.linkedin.com/in/yashbatt30)

## Acknowledgments
This project was inspired by the classic Simon Game and serves as an excellent exercise in event handling, DOM manipulation, and game development with jQuery.
