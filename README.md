# Number Guessing Game

This is a simple **Number Guessing Game** implemented in Python. The game randomly selects a number between 1 and 100, and the player has to guess the number within 10 attempts. The game provides feedback on whether the guessed number is too high or too low and also gives hints on how close the guess is.

## Features:
- **Random Number Generation**: The game generates a random number between 1 and 100 for the player to guess.
- **Limited Attempts**: The player has 10 attempts to guess the correct number.
- **Score System**: The player’s score decreases with each wrong guess, and they can score up to 10 points if they win with fewer attempts.
- **Hints**: After each guess, the game provides feedback if the guess is too small or too large. It also informs the player if they are close to the target number.
- **Quit Option**: The player can quit the game anytime by typing "Q".

## How To Play:
1. Run the program.
2. The program will display the target range (1 to 100) and give you 10 chances to guess the correct number.
3. After each guess, you'll receive feedback:
   - If the number is too small, the game will tell you to think bigger.
   - If the number is too large, the game will suggest thinking smaller.
   - If you're close to the target, the game will encourage you to keep guessing.
4. The game ends when you guess the correct number, run out of attempts, or decide to quit.
5. After the game ends, you'll receive your score based on how many guesses it took to find the correct number.

## Game Flow:
1. The game prompts the player to guess a number between 1 and 100.
2. After each guess, the game will provide hints and feedback.
3. The player can quit at any time by typing "Q".
4. If the player guesses the correct number, the game will display the score.
5. If the player runs out of guesses, the game will end and display a "You Lose" message.

## Code Breakdown:
- **target**: A random number between 1 and 100 is generated for the player to guess.
- **score**: The score starts at 11 and decreases with each incorrect guess.
- **chance**: Keeps track of the number of guesses taken by the player.
- **Game Flow**: The game prompts the player to input a guess or quit the game. The program then checks if the guess is correct and provides feedback.
