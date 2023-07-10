# Hangman-Game
The Hangman Game is a classic word-guessing game implemented in Python using the Pygame library. It provides an interactive and entertaining gaming experience where players attempt to guess a secret word by suggesting letters. Each incorrect guess leads to the drawing of a hangman figure, with the objective being to guess the word before the hangman is fully drawn.

# Game Features
Random word selection: The game selects a word randomly from a predefined list of words.

Visual representation: The game displays a series of hangman images to represent the current state of the hangman figure.

Button interface: The game provides clickable buttons for each letter of the alphabet, making it easy for players to input their guesses.

Guess tracking: The game keeps track of the letters guessed by the player and updates the displayed word accordingly.

Win/Loss conditions: The game checks for win and loss conditions, ending the game appropriately and prompting the player to play again.

Restart functionality: Players can restart the game by pressing any key after winning or losing.

# How to Play
Launch the game by running the Python script using a Python interpreter.

The game window will appear, displaying the hangman image, the hidden word to guess, and the buttons for each letter.

Click on the buttons to guess letters and try to uncover the hidden word.

If a guessed letter is correct, it will be revealed in the hidden word display.

If a guessed letter is incorrect, a part of the hangman figure will be drawn.

Keep guessing letters until you either guess the word correctly or the hangman is fully drawn.

If you win, a winning message will be displayed, and you can press any key to play again.

If you lose, a losing message with the correct word will be displayed, and you can press any key to play again.

Press the Esc key or close the game window to exit the game.

Note: The game uses a predefined list of words stored in the words.txt file. You can modify this file to include your own words or customize the game further.

# Requirements
- Python 3.x
- Pygame library
