# Hand Gesture Mouse Controller

This project enables users to control their computer mouse using hand gestures detected via a webcam. It utilizes **MediaPipe**, **OpenCV**, **PyAutoGUI**, and **pynput** to recognize and execute different mouse actions based on finger movements.

## Features
- **Move Mouse**: Moves mouse on your **index finger tip**.
- **Left Click**: Triggered when the **index finger rolls** (bends significantly).
- **Right Click**: Triggered when the **middle finger rolls**.
- **Double Click**: Triggered when **both index and middle fingers roll** simultaneously.
- **Take Screenshot**: Triggered when a **fist (all fingers curled)** is detected.

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/Ansh2909/Mouse_Control_Using_Hand_Gestures.git
cd Mouse_Control_Using_Hand_Gestures
```

### 2. Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

#### Required Libraries
- `opencv-python`
- `mediapipe`
- `pyautogui`
- `pynput`
- `numpy`

## How to Run
Run the script using the following command:
```bash
python app.py
```
This will open a webcam window where you can control the mouse using gestures.

## File Structure
- **app.py**: Main script that runs the hand tracking and gesture detection.
- **utils.py**: Helper functions for angle calculations and distance measurement.

## Usage
1. Ensure your webcam is working.
2. Run `app.py`.
3. Use gestures to control the mouse:

## Exit
Press **ESC** to exit the application.
