# Rock-Paper-Scissors-Game
This game 
Please retain the directory structure for smooth functioning of code.

# Installation
Note: Only windows systems will support automatic installation of necessary modules.
Please refer to requirements.txt for requirements for different OS, or change the "py -m" to "python3 -m" on lines 9 & 10 of the code.

SUMMARY: 
The project can be easily run on any windows machine (with admin access as some modules require installation which could be restricted on networked computers). The script automatically starts installation of necessary modules on running it the first time (only for windows). It then displays the user interface made using PyQt5 with the buttons. Upon clicking the game button, the user's camera is opened and the game starts by pressing the Spacebar. The cvzone module then recognises the hand and when the timer hits, it checks the number of fingers open, based upon which the computer checks if the user has shown rock, paper or scissors. Computer makes its choice using the random module and the choice is displayed using the OpenCV module. It compares user input with the computers and then updates the score accordingly, upon pressing the spacebar again, the timer starts. Upon clicking the ASL button, the sign language detection script is run. It detects the sign based on the inputs already stored in the trained_model.p file if it exists.

# Rock Paper Scissors with Computer Vision

This Python project implements a Rock Paper Scissors game using computer vision techniques. It utilizes the `cvzone` module for hand detection to recognize hand symbols and updates the score accordingly.

## Features:
- Hand detection using `cvzone` for precise gesture recognition.
- Real-time gameplay against the computer.
- Score tracking for both the player and computer.
- Simple and intuitive user interface.

## Requirements:
- Python 3.10
- OpenCV
- cvzone

## Usage:
1. Clone the repository: `git clone https://github.com/assholeonly/rock-paper-scissors-cv.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the game: `python main.py`

Feel free to contribute and improve this project!
