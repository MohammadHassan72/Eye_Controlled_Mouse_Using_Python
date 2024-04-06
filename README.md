**Eye Controlled Mouse Using Python**

This project enables control of the mouse cursor using eye movements detected from a webcam feed. It utilizes computer vision techniques to track the position of the eyes and translates those movements into mouse cursor movements. The script is written in Python and requires the OpenCV, Mediapipe, and PyAutoGUI libraries.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/eye_controlled_mouse.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd eye_controlled_mouse
    ```

3. Install the required libraries using pip:
    ```bash
    pip install opencv-python mediapipe pyautogui
    ```

### Usage

1. Run the Python script:
    ```bash
    python eye_controlled_mouse.py
    ```

2. A webcam window will open, and the script will start detecting your eyes.

3. Move your eyes to control the mouse cursor on the screen.

4. Blink or perform a specific eye gesture to simulate a mouse click.

5. Press any key to exit the program.

### Dependencies

- OpenCV (cv2): For capturing and processing webcam frames.
- Mediapipe: For face mesh detection to identify eye landmarks.
- PyAutoGUI: For controlling the mouse cursor and simulating mouse clicks.

### License

This project is licensed under the [MIT License](LICENSE).

### Author

[Mohammad Hassan](https://github.com/MohammadHassan72)

### Acknowledgements

- The project was inspired by the work of various computer vision researchers and developers in the field.
- Special thanks to the contributors of OpenCV, Mediapipe, and PyAutoGUI libraries for their valuable contributions.

### Note

- This project is for educational and experimental purposes only. Use it responsibly and considerate of others' privacy and consent.
- The accuracy and performance of the eye-tracking system may vary depending on environmental conditions and the quality of the webcam.
