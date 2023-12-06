## Overview

This is a simple implementation of the Mastermind game in C. The game involves a codemaker setting a secret code, and the codebreaker attempting to guess the code within a limited number of attempts.

## Usage

### Building the Code

To build the code, use the provided Makefile. Open a terminal in the project directory and run:
make

Running the Game
The executable is named mastermind. You can run it with the following command:

./mastermind [-c secret_code] [-t attempts]
Optional command line arguments:

-c: Set the secret code manually. If not provided, a random code will be generated.
-t: Set the number of attempts. Default is 10.
Gameplay
Follow the on-screen prompts to make guesses. The game provides feedback on each guess, and you can enter "stop" at any time to end the game.

File Structure
main.c: Main source file containing the game logic.
Makefile: Makefile for building the executable.
