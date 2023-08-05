# rock-paper-scissors

This Python script lets you play the classic Rock Paper Scissors game using hand gestures captured from your webcam. The script uses the MediaPipe library to detect hand landmarks and gestures, allowing you to make your choice by forming different hand shapes.

# Features
Capture hand gestures using your webcam to choose rock, paper, or scissors.
Randomly generate the computer's choice.
Determine the winner based on the chosen gestures.
Utilize text-to-speech functionality to announce the game's outcome.

# Requirements
Python 3.x,
OpenCV (cv2),
Pyttsx3 (pyttsx3),
MediaPipe (mediapipe)

# Usage
Ensure you have all the required dependencies installed. You can use the following command to install them:

<pre>
python pip install opencv-python mediapipe pyttsx3
</pre>

Run the script using Python:
<pre>
python filename.py
</pre>
        
Place your hand in front of the webcam, forming either a fist, open palm, or V sign to choose rock, paper, or scissors respectively.

The computer's choice will be randomly generated, and the winner of the game will be announced using text-to-speech.

# Notes
The script uses the mediapipe library to detect hand landmarks. Make sure your webcam is functioning and well-lit for accurate gesture detection.
Press 'q' to exit the game.
Feel free to modify the code to improve or expand the functionality as desired.
