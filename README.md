# Hand Detection with MediaPipe and OpenCV

This project uses **MediaPipe** and **OpenCV** to detect and track hand landmarks in real-time using a webcam. The system detects multiple hands, visualizes key hand landmarks, and calculates the frames per second (FPS) of the video feed.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- `opencv-python`
- `mediapipe`

You can install the required dependencies using the following command:

```bash
pip install opencv-python mediapipe
```
## Code Overview
1. Imports:
We import OpenCV, MediaPipe, and time to capture video, detect hand landmarks, and calculate the FPS.

2. Hand Detection Setup:
We initialize MediaPipe Hands solution and create a hands object. We also initialize drawing_utils to visualize the landmarks and connections on the hands.

3. Main Loop:
The code continuously captures frames from the webcam, processes the frames to detect hand landmarks, and displays the landmarks on the screen.

Hand Landmark Detection: For each detected hand, landmarks are drawn on the image.

FPS Calculation: The FPS is calculated by measuring the time difference between consecutive frames and displayed on the screen.

Landmarks Visualization: For each hand, key landmarks are drawn as circles on the detected points. The connections between hand landmarks are also drawn to visualize the hand shape.

4. Exit:
Press 'q' to stop the webcam feed and exit the application.

## How to Run the Code
To run the script, simply execute the following command:

bash
Copy code
python HandDetection.py
## Usage
Start the webcam: The program will begin capturing the webcam feed.

Hand Detection: The program will detect the hand landmarks in the video feed and draw the key points and connections on the hands.

FPS Display: The frames per second (FPS) will be displayed in the top left corner of the screen.

Exit: Press 'q' to exit the webcam feed and stop the application.

## 🖼️ Screenshots
![Screenshot 2025-04-27 at 1 19 18 PM](https://github.com/user-attachments/assets/d71f698b-5bf0-4ce8-af41-7e8737bca040)


