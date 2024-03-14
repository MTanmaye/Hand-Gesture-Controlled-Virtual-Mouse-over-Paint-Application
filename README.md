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

![Screenshot 2024-03-14 210700](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/5fc382b3-c77f-46ff-a414-d322491611a2)


Drag and drop: Close your hand into a fist and move it around to drag and drop objects.

![Screenshot 2024-03-14 210811](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/fe06ae91-15e4-45b6-97bb-2bcece1b26e2)


Right-click: Raise your index finger while keeping the other fingers closed.

![Screenshot 2024-03-14 210728](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/d6c54ad5-b322-4a82-9064-76e4b8290344)


Left-click: Raise your middle finger while keeping the other fingers closed.

![Screenshot 2024-03-14 210718](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/0e8c7ac0-04f7-4915-9cc6-42955f0b7d2a)


Double-click: Raise your index and middle finger while keeping the other fingers closed.

![Screenshot 2024-03-14 210743](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/16dcf06f-fd1c-49d5-b81d-db6d8fc28d73)


Scroll up: Move your index and middle finger towards the screen.

  ![Screenshot 2024-03-14 210841](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/d091c53b-64d1-417a-9f0c-9061953b3fe5)


Scroll down: Move your index and middle finger away from the screen.

  ![Screenshot 2024-03-14 210830](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/70fac155-7dd8-4dae-b142-05b8ea137a60)


Zoom in: Pinch your index finger and thumb together.

![Screenshot 2024-03-14 210800](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/3bf4f061-8395-4410-8407-5b49b2361554)

Zoom out: Spread your index finger and thumb apart.

 ![Screenshot 2024-03-14 210821](https://github.com/MTanmaye/Hand-Gesture-Controlled-Virtual-Mouse-over-Paint-Application/assets/114095621/90c62439-6cdd-449d-a2b8-51a8c8e6654b)
 


# How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The controller.py file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

# Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in comming commits of this project.

# License
This project is licensed under the Apache License 2.0. The Apache License 2.0 is a permissive license that allows you to freely use, modify, distribute, and sell the software.

Feel free to use, modify and distribute the code as you see fit under the terms of the Apache License 2.0. For more information, please refer to the LICENSE file in the root of the project directory.

