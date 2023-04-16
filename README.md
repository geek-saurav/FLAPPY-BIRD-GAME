# FLAPPY-BIRD-GAME
This is a simple implementation of the classic Flappy Bird game in Python using Pygame library.

## Prerequisites
To run this game, you need to have Python 3 and Pygame installed on your system.

## Getting Started

Clone the repository and navigate to the downloaded folder. Then, run the following command to start the game:

`python flappy_bird.py`

## Game Rules
The objective of the game is to navigate the bird through the pipes without colliding with them. The bird automatically moves forward and the player can control the bird's height by pressing the spacebar or up arrow key.

If the bird collides with a pipe or hits the ground, the game is over. The score is incremented every time the bird passes a pipe.

## Code Structure

The code consists of two main functions: welcomeScreen() and mainGame().

The welcomeScreen() function displays the welcome screen of the game with the game logo and a message prompting the user to press space or up arrow key to start the game.

The mainGame() function is the core of the game. It contains the game loop and handles the bird's movement, pipe generation, collision detection, and score updates.

The game assets, such as images and sounds, are stored in the gallery directory.

## Acknowledgments
This game is inspired by the classic Flappy Bird game developed by Dong Nguyen.

## Future Improvements

- Add a high score system
- Implement a game over screen with an option to restart the game
- Add more levels and challenges to the game.
