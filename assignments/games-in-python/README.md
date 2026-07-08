# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Hangman game in Python to practice core programming skills, including loops, conditionals, string handling, and user input. By the end of this assignment, you will have a playable command-line game with clear win/lose behavior.

## 📝 Tasks

### 🛠️	Build the Core Hangman Loop

#### Description
Create the main game flow for Hangman. Your program should choose a secret word, let the player guess one letter at a time, and display progress after each guess.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Display the hidden word using underscores for unknown letters (example: `_ _ _ _`).
- Accept one-letter guesses from the player.
- Reveal correctly guessed letters in all matching positions.


### 🛠️	Handle Game Rules and End States

#### Description
Add the rules that make the game complete: wrong-attempt tracking, win/lose conditions, and final feedback to the player.

#### Requirements
Completed program should:

- Track remaining incorrect guesses and reduce attempts only for wrong letters.
- Prevent duplicate guesses from counting multiple times.
- End with a win message when the full word is guessed.
- End with a lose message when attempts run out and display the correct word.
