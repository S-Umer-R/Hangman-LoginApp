# Hangman Game with Login System - Windows Form App using C#

This repository contains a Hangman game implemented in a Windows Form Application using C#. The game is integrated with a login system that authenticates users before allowing them to play the game. User credentials are stored in a Microsoft Access database file named `db_users.accdb`.

## Features
- User login and registration system
- Hangman game with multiple levels
- Visual feedback using images for hangman stages
- Game logic for checking guessed letters and determining win/loss

## Prerequisites
- Windows operating system
- .NET Framework
- Microsoft Access Database Engine (to access the database file)

## Instructions
To run the program, follow these steps:

1. Clone the repository or download the source code files.
2. Open the solution file `Login System.sln` located in the `Login System` folder using Visual Studio or any compatible C# IDE.
3. Make sure the required dependencies are installed and referenced properly.
4. Build the solution to ensure all the project files are compiled successfully.
5. Set up the database:
   - Ensure you have the Microsoft Access Database Engine installed on your system.
   - Open the database file `db_users.accdb` located in the `Login System` folder.
   - If needed, update the database connection string in the code to match your database location or credentials.
6. Run the program from the IDE. The login form will appear.
7. If you already have an account, enter your username and password and click the "Login" button to access the Hangman game. Otherwise, click the "Register" link to create a new account.
8. After successful login, you will be redirected to the Hangman game screen. Choose a level to start playing.
9. Guess letters by entering them in the text box and clicking the "Guess" button.
10. The hangman image will update based on correct or incorrect guesses.
11. Keep guessing letters until you either solve the word or run out of attempts.
12. If you win or lose, a message box will appear, and you can choose to play again or exit the game.
13. To log out, close the Hangman game window. You will be redirected back to the login screen.

## Acknowledgements
The Hangman game logic and graphics are based on the original Hangman game concept.
