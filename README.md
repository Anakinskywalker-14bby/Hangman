# Hangman Game

A simple command-line Hangman game implemented in Python, designed to help learners practice key programming concepts including dictionaries, lists, nested if statements, and the string and random Python modules.

## Overview

This Hangman game allows players to guess letters to complete a hidden word. The game randomly selects a word from a predefined list, and players have a limited number of attempts to guess the word correctly. It's a great project for beginners to explore Python's core data structures and control flow.

## Learning Objectives

- **Dictionaries:** Manage the word bank and track guessed letters.
- **Lists:** Handle the word's letters and display the current state of the guessed word.
- **Nested If Statements:** Implement game logic for validating guesses and updating the game state.
- **String Module:** Utilize string manipulation for word processing.
- **Random Module:** Randomly select words for the game.

## Features

- Random word selection from a predefined word bank
- Visual display of the hangman state
- Input validation for single-letter guesses
- Limited attempts to guess the word
- Clear win/lose conditions

## Getting Started

### Prerequisites

- Python 3.6 or higher
- No external libraries required (uses built-in `string` and `random` modules)

### Installation

Clone the repository:
```sh
git clone https://github.com/Anakinskywalker-14bby/Hangman.git
```

Navigate to the project directory:
```sh
cd Hangman
```

## Usage

Run the main script:
```sh
python hangman.py
```

Follow the prompts to guess one letter at a time.  
Try to guess the word before running out of attempts!  
After the game ends, choose to play again or exit.

## Project Structure

- `hangman.py`: Main script containing the game logic
- `README.md`: Project documentation
- `.gitignore`: Git ignore file for excluding unnecessary files

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements or additional features.