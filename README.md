# Hand Gesture recognition system

A Autonomous Based PC or Mobile Control System 


# Environment
- OS: Windows 
- Platform: Python 3
- Librarys: 
	- OpenCV 3
	- appscript

# Requirements
- import cv2
- import numpy as np
- import copy
- import math
- import pyautogui
- import time

 ## How to run it?

- git clone https://github.com/vasundharab28/handgesture
- pip install -r requirements.txt
- python hand-gesture.py

- command : python hand-gesture.py  (For hand recognition)
- press `'b'` to capture the background model (Remember to move your hand out of the blue rectangle)
- press `'r'` to reset the backgroud model
- press `'ESC'` to exit
- command : python hand_voice.py    (For hand + speech recognition)

#### Gesture to Operate 
- 1.Switch right
- 2.Switch left
- 3.Scroll down
- 4.Scroll up
- 5.Maximize
- 0.Minimize

### Speech Recognition
Added speech recognition using python in this project for voice controlling of pc .
Run speech.py file for the same . And working on it for making it run simultaneously with gesture recognition module.

#### Voice Commands
- 1.Zoom In      : To zoom in the tab
- 2.Zoom Out     : To zoom out the tab
- 3.Close Tab    : To close the current tab on web browser
- 4.Screenshot	 : To take screenshot of the screen
- 5.Open Tab/New Tab :To open new the tab on web browser
- 6.Close Window : To close application 
- 7.Open Terminal : To open command prompt on windows

## References & Tutorials

1. OpenCV documentation: 
http://docs.opencv.org/2.4.13/
2. Opencv python hand gesture recognition:
http://creat-tabu.blogspot.com/2013/08/opencv-python-hand-gesture-recognition.html
3. Speech Recognition:
https://pypi.org/project/SpeechRecognition
