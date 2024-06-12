Guess My Number Game
Overview
"Guess My Number" is a simple and fun web-based guessing game where players try to guess a randomly generated number between 1 and 20. The game provides feedback on each guess and keeps track of the player's score and high score.

Table of Contents
Features
Installation
Usage
Project Structure
Technologies Used
Contributing
License
Features
Random Number Generation: Each game session generates a new random number between 1 and 20.
User Feedback: Players receive feedback on their guesses (too high, too low, or correct).
Score Tracking: The game tracks the player's current score, which decreases with each incorrect guess.
High Score: The game records and displays the highest score achieved in the current session.
Reset Functionality: Players can reset the game and start over with a new number and score.
Installation
To run this game locally, follow these steps:

Clone the repository:

sh
Copy code
git clone https://github.com/AramisB/guess-my-number.git
cd guess-my-number
Open the project:
Open the index.html file in your preferred web browser.

Usage
Start the Game: Enter a number between 1 and 20 in the input box and click "Check!" to submit your guess.
Feedback: The game will display feedback on whether your guess is too high, too low, or correct.
Score: Your score decreases by 1 for each incorrect guess. The game ends when the score reaches 0.
High Score: If you guess the number correctly and your score is higher than the current high score, it updates the high score.
Reset: Click the "Again!" button to start a new game with a new random number and reset the score.
Project Structure
index.html: The main HTML file that sets up the structure of the game.
style.css: The CSS file that defines the styling of the game.
script.js: The JavaScript file that contains the game logic.
Technologies Used
HTML: Provides the structure of the game.
CSS: Adds styling to the game elements.
JavaScript: Implements the game logic and interactivity.
Contributing
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

Fork the repository:
sh
Copy code
git fork https://github.com/AramisB/guess-my-number.git
Create a feature branch:
sh
Copy code
git checkout -b feature-branch-name
Commit your changes:
sh
Copy code
git commit -m 'Add some feature'
Push to the branch:
sh
Copy code
git push origin feature-branch-name
Create a new Pull Request.
License
This project is open source and available under the MIT License.


