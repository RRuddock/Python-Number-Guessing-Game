# Python Guessing Game

This is a simple guessing game based off the one found in 'A Byte of Python' by Swaroop C H found at http://www.swaroopch.com/notes/python/

The original code can be found in the section titled "Control Flow".

## Changes

1. Import random to use randint() to have the game pick a random number.
2. Import os in order to clear the screen.
3. Created a class called color and assigned values. (This code was found at http://stackoverflow.com/questions/8924173/how-do-i-print-bold-text-in-python with additional color values for background colors found at http://ascii-table.com/ansi-escape-sequences.php.
4. Added a section to have the user state which level they would like to play at. (Defining the max values)
5. Used a while loop and try to ensure that the user entry for the level of play is an integer.
6. Added various levels by setting the max value of randint() to be based on the user selection.
7. Used a while loop and try to ensure that the user entry for guesses are an integer.
8. Added a counter to the game to keep track of the number of guesses it takes for the player to correctly guess the number.
9. Add a line to disply the final count of guesses it took for the user to correctly guess the number.
10. Added color throughout the game to make it more lively.

## Usage

This game can be played by typing the following at the command prompt:
python guess.py
