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

![Screenshot 2024-03-14 211958](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/459d332e-404f-4a9a-bb37-d34320fef6dd)



Cursor freezing: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.

![Screenshot 2024-03-14 210700](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/5fc382b3-c77f-46ff-a414-d322491611a2)


Drag and drop: Close your hand into a fist and move it around to drag and drop objects.

![Screenshot 2024-03-14 210811](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/fe06ae91-15e4-45b6-97bb-2bcece1b26e2)


Right-click: When the thumb finger and the middle finger touch each other.

![Screenshot 2024-03-14 210728](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/26728136-a45d-4972-9e4a-128312c0d1f6)


Left-click: When the thumb finger and the forefinger touch each other.

![Screenshot 2024-03-14 212115](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/06dd5efa-9dc8-499b-a874-5fa956d3c2d4)


Double-click: When the thumb finger and the ring finger touch each other.

![Screenshot 2024-03-14 212340](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/11d5f6fc-56f8-470e-ab5c-e6af560da8d5)


Scroll up: Raise little finger and close all other fingers.

![Screenshot 2024-03-14 210841](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/6c67d679-260b-4c16-8fd4-53ea419379ce)


Scroll down: Raise index finger along with thumb finger and close all other fingers.

 ![Screenshot 2024-03-14 212537](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/7f6abc35-0c87-474e-a374-78a59a88022e)

Zoom in: Raise index figer with middle finger with gap betwwen fingers and all other fingers are closed.

![Screenshot 2024-03-14 210800](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/85e142ba-2708-41e9-869c-c0a57974ddd5)


Zoom out: Raise index figer with middle finger with no gap betwwen fingers and all other fingers are closed.

![Screenshot 2024-03-14 212513](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/eb0cce49-8c92-4882-a2e6-86e4226b4f6a)

 


# How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The controller.py file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

# Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in comming commits of this project.

# License
This project is licensed under the Apache License 2.0. The Apache License 2.0 is a permissive license that allows you to freely use, modify, distribute, and sell the software.

Feel free to use, modify and distribute the code as you see fit under the terms of the Apache License 2.0. For more information, please refer to the LICENSE file in the root of the project directory.

