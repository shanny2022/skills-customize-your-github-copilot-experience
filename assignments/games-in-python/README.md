
# 📘 Assignment: Games in Python (Hangman)

## 🎯 Objective

Build a text-based Hangman game in Python to practice loops, conditionals, string handling, and user input.

## 📝 Tasks

### 🛠️ Set Up the Game State

#### Description
Use the starter code to prepare all variables needed to run Hangman.

#### Requirements
Completed program should:

- Randomly select one word from the provided `words` list.
- Create variables to track guessed letters, incorrect guesses, and the maximum number of allowed incorrect guesses.
- Store the selected word in a clearly named variable (for example, `secret_word`).

### 🛠️ Build the Main Game Loop

#### Description
Implement the loop where the player keeps guessing letters until they win or run out of attempts.

#### Requirements
Completed program should:

- Display the current progress of the word using underscores for unguessed letters.
- Ask the player for a letter guess on each turn.
- Update guessed letters and incorrect guess count based on whether the guess is correct.
- Continue running until all letters are guessed or the incorrect guess limit is reached.

### 🛠️ Show the Final Result

#### Description
End the game with a clear message so the player knows whether they won or lost.

#### Requirements
Completed program should:

- Print a congratulatory message if the player guesses the full word.
- Print a losing message if the player runs out of attempts.
- Reveal the secret word at the end of the game.
