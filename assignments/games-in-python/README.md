
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Students will build a classic Hangman game in Python to practice string manipulation, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the Hangman game structure and randomly select a secret word from a predefined list.

#### Requirements
Completed program should:

- Define a list of possible secret words.
- Randomly select one word from the list when the game starts.
- Initialize game state for guessed letters and remaining attempts.

### 🛠️ Guess Processing and Display

#### Description
Implement letter guessing logic so the player can reveal letters and see their progress.

#### Requirements
Completed program should:

- Accept single-letter guesses from the user.
- Display the current word progress using underscores and revealed letters (e.g. `_ A _ _ _`).
- Track and show letters that have already been guessed.

### 🛠️ Win/Lose Conditions

#### Description
Add game-ending logic so the game finishes when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Decrease remaining attempts for incorrect guesses.
- End the game with a win message when the full word is guessed.
- End the game with a lose message when attempts are exhausted.
- Display the correct word when the player loses.

