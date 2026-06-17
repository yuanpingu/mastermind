# Mastermind Automation App
A Mastermind-style number guessing game developed using **UiPath Studio Web** and tested on local machine. The player has **10 attempts** to guess a randomly generated 4-digit code. After each attempt, the app provides feedback to help the player guess the correct code.

## Features
- Generates a random 4-digit code for the player to guess
- Allows up to 10 guesses per game
- Accepts and valdiates user input
- Compares each guess against the correct code and provides feedback
- Uses a message box to interact with the player

## UiPath Concepts Used
- Variables and data types
- Loops and repeated workflows
- Conditional statements
- User input and message boxes
- Input validation
- Workflow debugging

## How the game works
1. The application generates a random 4-digit code.
2. The player enters a guess through the input dialog.
3. The workflow compares the guess with the generated code
4. Feedback is displayed based on the result.
5. The process repeats until the player guesses correctly or uses all 10 attempts.

## Project Demo
- [Watch the demo video](Mastermind App Demo.mp4)

## Tools used
- UiPath Studio Web
- Canva and CapCut for project documentation

## Further improvements
- Add different difficulty levels
- Include a scoring system
- Track the player's previous guesses

## Further reading
- [UiPath Documentation](https://docs.uipath.com/)
