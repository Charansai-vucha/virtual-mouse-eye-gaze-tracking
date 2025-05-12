# Virtual Mouse using Eye Gaze Tracking

This project demonstrates how to control the mouse pointer using eye gaze tracking. It uses the following libraries:
- **OpenCV**: For video capture and frame manipulation.
- **MediaPipe**: For detecting facial landmarks and estimating eye gaze direction.
- **PyAutoGUI**: For controlling the mouse cursor and simulating clicks.

## Features
- **Eye Gaze Tracking**: Detects facial landmarks around the eyes and maps the eye movement to control the mouse pointer.
- **Mouse Clicking**: Simulates a click when the eye gaze is stable over a specific point on the screen.

## Libraries and Tools Used
- `cv2` (OpenCV)
- `mediapipe`
- `pyautogui`

## Requirements

### Python Version
- Python 3.x

### Install Dependencies
Before running the application, you need to install the required libraries. Run the following command:

```bash
pip install -r requirements.txt
