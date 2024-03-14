# Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application
This is a Python project for controlling a computer's mouse cursor & paint operations using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, app.py and controller.py. The app.py file contains the main program logic while controller.py is responsible for handling the mouse cursor movement and click events.

There is an extra file, requirements.txt which you can use to install the libraries required for this project.

 # Requirements
 To run the program, the following libraries are required:

OpenCV

Mediapipe

PyAutoGUI


You can install these libraries using pip:

pip install opencv-python mediapipe pyautogui

Or you can use the following command using pip to avoid any library version issue:

pip install -r requirements.txt


# How to Run
After installing the required libraries, run the app.py file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

Cursor moving: Raise all fingers together and move your hand to move the cursor and control it.

![Screenshot 2024-03-14 210148](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/3c115834-551f-4bcf-9922-6d4d8e3f9129)

Cursor freezing: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.

     Mouse_freezing

Drag and drop: Close your hand into a fist and move it around to drag and drop objects.

     Drag

Right-click: Raise your index finger while keeping the other fingers closed.

     Right_click

Left-click: Raise your middle finger while keeping the other fingers closed.

     Left_click

Double-click: Raise your index and middle finger while keeping the other fingers closed.

     Double_click

Scroll up: Move your index and middle finger towards the screen.

     Scrolling_up

Scroll down: Move your index and middle finger away from the screen.

     Scrolling_down

Zoom in: Pinch your index finger and thumb together.

     Zooming_in

Zoom out: Spread your index finger and thumb apart.

     Zooming_out


# How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The controller.py file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

# Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in comming commits of this project.

# License
This project is licensed under the Apache License 2.0. The Apache License 2.0 is a permissive license that allows you to freely use, modify, distribute, and sell the software.

Feel free to use, modify and distribute the code as you see fit under the terms of the Apache License 2.0. For more information, please refer to the LICENSE file in the root of the project directory.

