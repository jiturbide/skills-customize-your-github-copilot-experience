
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, conditionals, and user input while practicing game logic and input validation.

## 📝 Tasks

### 🛠️ Create the Hangman Game

#### Description
Develop a text-based Hangman game where a player guesses letters to reveal a hidden word before running out of attempts. Use a list of words, track guessed letters, and display progress after each turn.

#### Requirements
Completed program should:

- Randomly choose a secret word from a predefined list of words.
- Show the player's progress using underscores or blanks, such as `_ _ _ _`.
- Accept one letter guess at a time from the user.
- Reveal correctly guessed letters in the word and keep incorrect guesses tracked.
- Limit the number of wrong guesses and display the remaining attempts.
- End the game when the player either guesses the word correctly or runs out of attempts.
- Print a clear win or lose message at the end.

Example output:

```python
Word: _ _ _ _ _ _
Guess a letter: a
Correct! Word: _ a _ _ _ _
```
