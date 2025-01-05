# volume-control-using-hand-gesture
This volume control module uses hand tracking to adjust the system volume. It detects the distance between the thumb and index finger to control the volume level, and adjusts it based on hand gestures. You can mute or change the volume using finger positions, making it a hands-free solution for controlling audio.

This project enables hands-free control of your computer's volume using hand tracking. It utilizes a hand detection model that tracks the position of your hands, particularly the distance between the thumb and index finger, to adjust the system volume. The distance determines the volume level—closer fingers decrease the volume, and as they move apart, the volume increases. Additionally, by detecting whether the pinky finger is down, the system mutes or unmutes the volume accordingly. This offers a highly interactive and intuitive way to control your device's audio, ideal for presentations, media playback, or any other situation where you don't want to use a mouse or keyboard.

## Features:
- **Hands-free volume control**: Adjust the volume using hand gestures.
- **Volume range control**: Adjust the system volume smoothly with dynamic finger distance.
- **Mute functionality**: Muting the volume by detecting the position of the pinky finger.
- **Real-time updates**: Instant feedback on the system’s volume level and gestures.

## Installation Guide:

### 1. Install Python:
Ensure Python 3.x is installed on your computer. You can download the latest version from the official Python website: [python.org/downloads](https://www.python.org/downloads/).

### 2. Clone or Download the Repository:
Clone or download the repository to your local machine. If you're using Git, run:

### 3. Install Required Libraries:
Open a terminal or command prompt in the project directory and run:

pip install -r requirements.txt

This will install all necessary dependencies like OpenCV, PyCaw, and Mediapipe.

### 4. Install PyCaw for Volume Control:
PyCaw is required to control the system volume. Install it by running:

pip install pycaw

### 5. Install OpenCV and MediaPipe for Hand Tracking:

Install OpenCV and MediaPipe for hand tracking by running:

pip install opencv-python mediapipe

### 6. Check Webcam Access:
Ensure your webcam is functioning properly, as the system uses the webcam to detect hand gestures.


### Running the Application:
Navigate to the folder where the script is located, and run the program with:

python volumeControl.py

### Adjusting the Volume:
Hand Detection: The program will detect your hand, and you will be able to see the webcam feed in a window.
Volume Control: Move your thumb and index fingers closer or farther apart to decrease or increase the volume.
Mute/Unmute: The volume mutes automatically when the pinky finger is down. Raise it again to unmute.
Stopping the Application:
To exit the program, press the 'q' key while the webcam feed window is active.
