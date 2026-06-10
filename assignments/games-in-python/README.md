
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game using Python to practice string manipulation, loops, conditionals, and user input handling.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create a function that initializes the game and selects a random word from a predefined list.

#### Requirements
Completed program should:

- Choose a secret word randomly from a list of words.
- Store the correct letters and the current display state using underscores for hidden letters.
- Track letters that have been guessed by the player.

### 🛠️ Gameplay Loop and Win/Lose Logic

#### Description
Implement the main Hangman gameplay loop where the player guesses letters until they win or run out of attempts.

#### Requirements
Completed program should:

- Prompt the player to guess one letter at a time.
- Reveal correctly guessed letters in the word display.
- Track remaining incorrect guesses and do not penalize repeated correct letters.
- End the game when the word is fully guessed or the player uses all allowed attempts.
- Display a win message if the player guesses the word, or a lose message if they run out of attempts.
