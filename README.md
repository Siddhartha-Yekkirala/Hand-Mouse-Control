
1. Project Overview

Hand Mouse Control is a Python-based application that allows users to control their computer mouse using hand gestures.
It leverages MediaPipe for real-time hand tracking, OpenCV for webcam input and image processing, and PyAutoGUI to control the mouse pointer and clicks.

Purpose:

To enable touchless mouse control.

To provide accessibility options for users with limited mobility.

To demonstrate computer vision and gesture recognition techniques.

2. Features

Move mouse pointer using the index finger.

Click by bringing thumb close to the index finger.

Works in real-time with webcam input.

Lightweight and easy-to-run Python script.

Can be extended for additional gestures (e.g., right-click, scroll).

3. Requirements

Python 3.x installed

Webcam

Internet connection (for installing dependencies)

Python libraries:

opencv-python

mediapipe

pyautogui

4. Installation
Step 1: Clone the Repository
git clone https://github.com/<your-username>/Hand-Mouse-Control.git

Step 2: Navigate to the Project Folder
cd Hand-Mouse-Control

Step 3: Install Dependencies
pip install opencv-python mediapipe pyautogui


On some systems, you may need to use pip3.

5. Usage Instructions

Open a terminal/command prompt in the project folder.

Run the Python script:

python hand_mouse.py


Controls:

Move index finger → Moves the mouse pointer.

Bring thumb close to index finger → Clicks the mouse.

Press 'x' → Exit the program.

Ensure your hand is visible and well-lit for accurate tracking.

6. Troubleshooting

Mouse jumps erratically: Ensure camera is stable and well-lit. Avoid sudden fast hand movements.

PyAutoGUI does not control the mouse: Run the script as administrator (Windows) or with proper permissions (Mac/Linux).

Dependencies not installing: Ensure pip is updated:

pip install --upgrade pip


Webcam not detected: Check if other applications are using the webcam.

7. File Structure
Hand-Mouse-Control/
│
├── hand_mouse.py        # Main Python script
├── README.md            # Project README
├── .gitignore           # Ignored files for Git
└── hand_mouse.gif       # Optional demo GIF

8. Future Improvements

Add right-click and scroll gestures.

Add gesture-based drag-and-drop functionality.

Implement gesture calibration for different screen resolutions.

Integrate GUI interface for easier setup.

9. References

MediaPipe Hands Documentation

PyAutoGUI Documentation

OpenCV Python Tutorials
