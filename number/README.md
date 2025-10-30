# Number Guesser

The goal of this project is to develop an interactive number guessing game where the user attempts to identify a randomly generated number within a custom range. At the start, the user specifies the range by providing a lower and upper limit (e.g., A to B). The system then randomly selects a number within this range. The player must guess the correct number in as few attempts as possible. After each guess, the game provides feedback indicating whether the guessed number is too high or too low, helping the player adjust their next attempt accordingly.


## Algorithm: Number Guessing Game

### Input Range:
Prompt the user to enter the lower and upper bounds of the range.

### Generate Random Number:
Randomly select an integer between the specified lower and upper limits (inclusive).

### Determine Maximum Guesses:
Calculate the maximum number of allowed guesses using the binary search formula

### Start Guessing Loop:
Repeat until the user either guesses the number correctly or exhausts all allowed attempts:

### Prompt the user to enter their guess.

If the guess is greater than the target number:
Display "Try Again! You guessed too high."

Else if the guess is less than the target number:
Display "Try Again! You guessed too low."

Else:
Display "Congratulations! You guessed the correct number!" and end the game.

### End of Game:
If all guesses are used and the number is not found, reveal the correct number and display:
"Better Luck Next Time!"