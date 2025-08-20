Hand Gesture Control using MediaPipe & PyAutoGUI
This project enables real-time hand gesture control of keyboard inputs using MediaPipe and PyAutoGUI. It detects hand landmarks from a webcam feed and maps specific gestures to keyboard actions.

🚀 Features
* Real-time hand tracking using MediaPipe
* Control keyboard inputs using hand gestures
* Simple and lightweight implementation
* Works on Windows, macOS, and Linux

📦 Installation
1. Clone the repository: git clone https://github.com/your-username/hand-gesture-control.git
2. cd hand-gesture-control
3. 
4. Install dependencies: pip install -r requirements.txt
5.  Or install manually: pip install opencv-python mediapipe pyautogui
6. 

🧩 Usage
1. Connect a webcam to your computer.
2. Run the script: python hand_gesture_control.py
3. 
4. A webcam window will open. Show your hand in front of the camera and use the following gestures:
Gesture	Fingers	Action
👆	1 finger	Press Right Arrow
✌️	2 fingers	Press Left Arrow
🖖	3 fingers	Press Up Arrow
✋	4 fingers	Press Down Arrow
🖐️	5 fingers	Press Spacebar
	4	Press Esc to exit the program.

📝 Notes
* Currently supports single-hand detection.
* Gesture accuracy may vary depending on lighting and camera quality.
* Adjust thresholds in the code if required for better performance.

🤝 Contributing
Contributions are welcome! If you find any issues or have suggestions:
* Open an issue
* Submit a pull request

📄 License
This project is licensed under the MIT License.
