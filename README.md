# Novanector_python_01

Quiz Game
This is a simple quiz game implemented using Python's Tkinter library. The game presents a series of questions with multiple-choice answers and calculates the player's score based on their answers.

Features
Multiple-choice questions
Score tracking
Option to replay the game
Installation
Ensure you have Python installed on your system. You can download it from python.org.

Install Tkinter if it's not already installed. Tkinter usually comes with Python, but if you need to install it separately, you can do so using the following command:

sh
Copy code
sudo apt-get install python3-tk
Usage
Download the Elementary task.py file to your local machine.

Run the script using Python:

sh
Copy code
python Elementary\ task.py
Follow the on-screen instructions to play the game.

Code Overview
Questions: A list of quiz questions.
Options: A list of answer options for each question.
Answers: A list of correct answers (indexed from 1).
The game initializes with a welcome screen. Once the player starts the game, the first question is displayed with multiple-choice options. The player selects an answer and clicks "next" to proceed to the next question. At the end of the quiz, the player's score is displayed, and they have the option to play again.

Functions
start_again(): Resets the game to the initial state.
next(): Handles the logic for proceeding to the next question and calculating the score.
check(option): Ensures only one answer option can be selected at a time.
start_game(): Starts the game by displaying the first question.

Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
