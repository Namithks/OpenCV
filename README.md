<h1>Media Control Using Hand Gestures</h1>

My name is Namith ks , This project uses OpenCV, Mediapipe, and PyAutoGUI to create a hand gesture-controlled media player. The program captures video from the webcam, detects hand landmarks, and counts the number of fingers raised. Based on the number of fingers detected, it performs different actions on the media player.

<h2>Requirements</h2>
To run this project, you need the following libraries:
- OpenCV
- Mediapipe
- PyAutoGUI

## Usage

How to Run

1.Clone the repository:
git clone https://github.com/Namithks/OpenCV.git
cd OpenCV

2. Run the main script to start the hand gesture control:
    ```sh
    python main.py
    ```

3. Use the following gestures to control the media:
    - 1 finger: Press "right" key
    - 2 fingers: Press "left" key
    - 3 fingers: Press "up" key
    - 4 fingers: Press "down" key
    - 5 fingers: Press "space" key

### Key Functions

- **count_fingers(lst)**: Counts the number of fingers shown based on the hand landmarks detected.
- **Video Capture and Processing**: Captures video from the webcam, processes each frame to detect hand landmarks, and performs actions based on the number of fingers detected.

