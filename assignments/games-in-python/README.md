# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python by practicing string handling, loops, conditionals, and random selection.

## 📝 Tasks

### 🛠️ Create the Word-Guessing Game

#### Description
Write a Python program that randomly selects a secret word and lets the player guess one letter at a time.

#### Requirements
Completed program should:

- Choose a word from a predefined list using `random.choice()`.
- Show the hidden word in underscore format, such as `_ _ _ _ _`.
- Accept letter guesses from the user with `input()`.
- Reveal correctly guessed letters in the hidden word.

### 🛠️ Track Attempts and End the Game

#### Description
Add the game flow that tracks incorrect guesses, limits attempts, and announces whether the player wins or loses.

#### Requirements
Completed program should:

- Keep track of how many guesses the player has left.
- Display the current progress and incorrect letters after each guess.
- End the game when the word is fully guessed or the attempts are exhausted.
- Print a clear win or lose message at the end of the game.
