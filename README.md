 Volume and Brightness Control using Hand Gestures

## Description
This project enables controlling the system's volume and screen brightness using hand gestures captured by the webcam.
It utilizes computer vision techniques and Python libraries to detect hand gestures and translate them into corresponding system actions.

## Features
- Control volume: Increase, decrease, and mute/unmute the system's audio output.

- Adjust brightness: Increase or decrease the screen brightness based on hand gestures.

- Real-time feedback: Visual indicators on the screen to show the current volume level and brightness level.

## Installation
1. Clone this repository to your local machine:

    ```
    git clone https://github.com/Ragav-krishna/Volume-Brightness-Control.git
    ```

2. Navigate to the project directory:

    ```
    cd Volume-Brightness-Control

    ```

3. Install the required Python libraries:

    ```
     cv2
     mediapipe
     math
     hypot
     numpy 
     ctypes
     comtypes 
     pycaw
     google.protobuf.json_format 
     screen_brightness_control
    
    ```

## Usage
1. Run the main Python script:

    ```
    python main.py
    ```

2. Position yourself in front of the webcam, ensuring your hand is clearly visible.
3. Perform hand gestures as follows:
    - To control volume:(Right hand)
        - Thumb up: Increase volume.
        - Thumb down: Decrease volume.
        - Thumb and index finger pinch: Mute/unmute.
    - To adjust brightness:(left hand)
        - Swipe left: Decrease brightness.
        - Swipe right: Increase brightness.
