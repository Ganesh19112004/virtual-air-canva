Virtual Air Canva — Gesture-Controlled Drawing Application
Overview
Virtual Air Canva is a gesture-controlled drawing application that allows users to create art and drawings in the air using their hand movements. Powered by Python, OpenCV, and MediaPipe, it uses hand gesture recognition to draw on a canvas, offering an intuitive and interactive way to create without a physical stylus.

Features
Hand Gesture Recognition: Utilizes MediaPipe to track hand landmarks and finger positions.

Real-Time Drawing: Draws lines on the canvas based on hand movements, specifically the index finger.

Color Palette: Multiple color options to select for drawing.

Brush Thickness Control: Adjust the brush thickness with simple gestures.

Eraser Mode: Switch between drawing and erasing with a gesture.

Undo/Redo: Undo the last stroke or clear the entire canvas.

Save Artwork: Save your drawing as a .png file.

Interactive UI: Custom button layout rendered on the webcam feed for a seamless user experience.

Technologies Used
Python

OpenCV

MediaPipe

NumPy

Deque (for efficient undo/redo logic)

Setup Instructions
Install Dependencies

To run this project, you need Python installed on your machine. You also need to install the required libraries:

bash
Copy
Edit
pip install opencv-python mediapipe numpy
Run the Application

To run the application, simply execute the Python script:

bash
Copy
Edit
python virtual_air_canva.py
The camera feed will appear in a window, and you can start drawing in the air using hand gestures. Press ESC to exit the application.

How It Works
Camera Setup: Captures real-time video using OpenCV.

Hand Gesture Recognition: MediaPipe tracks the hand and identifies the position of the index finger to detect gestures for drawing.

Drawing & UI Interaction: The user can select colors, change brush thickness, toggle eraser mode, and perform undo/redo actions using the on-screen buttons.

Canvas Overlay: A transparent canvas is displayed on top of the camera feed to show the drawing as it is being created.

Controls
Hand Gestures:

Draw: Move your index finger to draw on the canvas.

Erase: Hold the index finger down over the canvas and move it.

UI Buttons: Tap the buttons displayed on the screen by moving your finger over them.

Keyboard:

Press ESC to exit the application.

Features in Detail
Brush Options: Use the buttons to select from different brush sizes (thin, medium, thick, extra thick).

Undo/Redo: Use the "Undo" button to go back to the previous stroke or "Clear" to clear the entire canvas.

Save: Save your current artwork as a .png file with a timestamp.

Screenshots
Application Interface

Contributing
Feel free to fork and modify the project as needed. If you have any suggestions or improvements, please submit an issue or a pull request.


Instructions for Saving Artwork
When you’re done with your creation, simply click the Save button, and the drawing will be saved with a timestamp.
