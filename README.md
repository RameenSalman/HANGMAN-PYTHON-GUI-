

# Hangman Game (Tkinter)

This project is a fully interactive Hangman game implemented with Python and Tkinter. It uses external word lists for multiple difficulty levels, renders the Hangman drawing step-by-step based on incorrect guesses, and enforces strict input validation. The game also includes a limited hint system that reveals random letters without breaking the core logic.

## Features

* Tkinter-based GUI (no console interaction)
* Three difficulty modes using separate word lists
* Progressive Hangman drawing mapped to wrong attempts
* Strict validation for single-letter input
* Prevention of repeated guesses
* Hint system with capped usage based on word length
* Automatic win/lose detection with final pop-ups

## Setup & Execution

Make sure these files are in the same directory:

```
hangman.py
easy.txt
medium.txt
hard.txt
```

Run the game:

```
python hangman.py
```

## Requirements

* Python 3.x
* Tkinter (included with standard Python on most systems)

## Notes

* Word lists must contain lowercase words, one per line.
* Changing difficulty simply switches the word source file.
* All game state (attempts, hints, guessed letters) resets each session.


