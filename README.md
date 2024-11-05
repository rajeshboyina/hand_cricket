# Hand Cricket Game

A real-time hand cricket game that uses hand gestures to simulate a cricket match, powered by OpenCV, MediaPipe, and pyttsx3 for audio feedback. The game allows users to play against the system using hand gestures to represent their score, and the system randomly generates its score. The match ends when both the user and the system select the same score.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How to Play](#how-to-play)
- [Contributing](#contributing)

## Features
- Real-time gesture recognition using MediaPipe.
- Random score generation by the computer.
- Visual score tracking and updates.
- Text-to-speech notifications for match results.
- Simple, interactive UI with real-time FPS display.

## Technologies Used
- *Python*
- *OpenCV*: For video capture and frame processing.
- *MediaPipe*: For hand tracking and gesture recognition.
- *pyttsx3*: For audio feedback.

## Setup and Installation

1. *Clone the repository*:
   bash
   git clone https://github.com/yourusername/hand-cricket-game.git
   cd hand-cricket-game
   

2. *Install dependencies*:
   bash
   pip install -r requirements.txt
   
   Ensure you have the required libraries: OpenCV, MediaPipe, and pyttsx3.

3. *Run the game*:
   bash
   python hand_cricket_game.py
   

## Usage
Run the game and follow on-screen instructions to start a match. You can view your live video feed in the top right, while your gesture-based scores will be updated in real time on the screen.

## Project Structure

## hand-cricket-game/
    ├── cricket_fingers/*        # Folder containing finger images used in the UI
    ├── main.py*                 # Main script to start the game
    ├── inst.png                # Instruction image for gameplay guidance
    ├── inst_modi.png           # Alternative instruction image
    ├── README.md
    └── requirements.txt        # Dependencies


## How to Play
1. *Starting the Game*:
   - Use five fingers (open palm) to reset and start a new match.
   
2. *Gameplay*:
   - Select a number (0–4) by showing corresponding fingers.
   - If your score matches the computer's randomly selected score, the game ends.
   - The scores of both user and computer are updated after each round.

3. *Ending the Game*:
   - The game ends when both player and system select the same score, with a match result shown on screen (win, loss, or draw).
   - Text-to-speech feedback announces the match result.

## Contributing
Feel free to fork this repository and submit pull requests. Suggestions and feature improvements are always welcome.


