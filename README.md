
# Hangman Game in Python

A simple implementation of the classic Hangman game using Python.

## Description

This is a text-based version of the Hangman game, where the player tries to guess a word by suggesting letters one at a time. The game ends when the player either guesses the word correctly or runs out of attempts.

## Features

- Randomly selects a word from a predefined list.
- Allows the player to guess one letter at a time.
- Tracks the number of attempts remaining.
- Displays the current state of the word, showing underscores for unguessed letters and revealing the correct ones as the player guesses.
- Handles invalid input, such as entering more than one character or non-alphabetical characters.
- Gives feedback on correct or incorrect guesses.
- Displays the guessed letters and attempts left.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
Navigate to the project directory:

bash
Copy
cd hangman-game
Run the program:

bash
Copy
python hangman.py
How to Play
When you run the game, it will randomly select a word.
You will be prompted to guess a letter.
The game will show you the current state of the word, with underscores for unguessed letters.
Keep guessing until you either guess the word correctly or run out of attempts.
If you run out of attempts, the game will reveal the correct word.
