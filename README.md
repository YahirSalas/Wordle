**Description**:
This Wordle Game developed as part of my CISC179 GitHub Project, is a Python implementation of the classic word-guessing game using the Pygame library. Inspired by Baraltech's YouTube tutorial, the game challenges players to guess a hidden five-letter word through keyboard inputs, providing immediate feedback on the correctness of their guesses. The visual appeal is enhanced with background images and custom fonts.

**Features**:
The program initializes the Pygame library, sets up the game window with background and icon, and defines a five-letter hidden word for players to guess. Users interact with the game by entering letters, which are visually displayed on the screen. The game checks the correctness of each guess, updates the display accordingly, and tracks the number of attempts.
Input and Interaction: The game captures user input through the keyboard events, allowing players to input letters, trigger play-again, and interact with the game.
If/Else Statements: Employed for checking the correctness of each guessed letter and determining the game outcome (win, loss, or ongoing).
For Loops: Used in creating indicators for available letters on the keyboard, enhancing the graphical user interface.
While Loops: Implemented to enable multiple guesses until the correct word is identified or the maximum attempts are exhausted.
Functions: The code is modularized using functions such as draw_letter, check_guess, play_again, reset, create_new_letter, and delete_letter for better code organization and readability.
Strings: Strings are used to represent and manipulate words, both for the target word and the guessed words.
Modules: The words module is imported to access a list of words, adding an element of randomness to the game.

**Intended Functionality**:
Designed for simplicity and enjoyment, this game provides an interactive place for players to test their word-guessing skills. The Wordle Game concludes with a win if the correct word is guessed within a set number of attempts (six)  and declares a loss if the maximum attempts are reached without a correct guess.

