# Game of NIM

Welcome to the Game of NIM! This project implements the classic mathematical strategy game where two players take turns removing objects from various piles. The goal is to avoid being the player forced to take the last object.

## Features

- Two-player mode (Human vs. Human)
- Human vs. Computer mode with simple AI
- Command-line interface for easy interaction

## Files

- `nim.py`: Contains the main logic for the Game of NIM
- `play.py`: Script to start and play the game

## How to Play

1. **Setup:**
    - Clone this repository to your local machine:
      ```bash
      git clone https://github.com/Vish987/Projects.git
      ```
    - Navigate to the project directory:
      ```bash
      cd Projects/'Game Of Nim'
      ```

2. **Running the Game:**
    - Ensure you have Python installed on your machine
    - Run the game using the following command
      ```bash
      python play.py
      ```

3. **Game Rules:**
    - The game starts with a number of piles, each containing a number of objects
    - Players take turns to remove any number of objects from a single pile
    - The player forced to take the last object loses the game

## Example

When you run the game, you'll be prompted to choose a pile and the number of objects to remove from that pile. Follow the on-screen instructions to play the game.

The number of training games, number of piles, and objects in each pile can be modified in `nim.py`.

```plaintext
Playing training game 1
...
Playing training game 10000
Done training

Piles:
Pile 0: 1
Pile 1: 3
Pile 2: 5
Pile 3: 7

AI's Turn
AI chose to take 1 from pile 0.

Piles:
Pile 0: 0
Pile 1: 3
Pile 2: 5
Pile 3: 7

Your Turn
Choose Pile:
...
```
