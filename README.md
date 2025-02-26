# Gaze-Controlled Mouse System

This project implements a gaze-controlled mouse system using Python and OpenCV. It enables users to move the mouse cursor using eye movement and perform clicks with blinks. The system also features momentum tracking for smooth cursor movement and adaptive speed adjustments.

## Features
- **Gaze Tracking**: Detects eye movement and maps it to cursor movement.
- **Blink-Based Clicking**: Performs mouse clicks when a blink is detected.
- **Momentum Tracking**: Ensures smooth and natural cursor movement.
- **Adaptive Speed Control**: Adjusts cursor speed based on gaze position.

## Installation
### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.x
- OpenCV (`cv2`)
- dlib
- numpy
- pyautogui

### Install Dependencies
```bash
pip install opencv-python dlib numpy pyautogui
```

## Usage
Run the script using:
```bash
python gaze_mouse.py
```

### Controls
- Move your eyes to control the cursor.
- Blink to perform a mouse click.
- Adjust settings for sensitivity and momentum in the script if needed.

## Customization
You can modify parameters such as:
- Cursor speed
- Blink detection threshold
- Momentum decay factor

These settings can be adjusted within the script to better fit user preferences.

## Applications
- Assistive technology for individuals with mobility impairments.
- Hands-free interaction for hygiene-sensitive environments.
- Gaming and augmented reality applications.

## Contribution
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.

---

### Author
Likith B S 

For questions or suggestions, feel free to open an issue!

