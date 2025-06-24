# 🔌 Hand Gesture Controlled LEDs using MediaPipe and PySerial

Control multiple LEDs using hand gestures detected via your webcam! This project uses **MediaPipe** for hand tracking and **PySerial** to communicate with an Arduino that switches LEDs ON/OFF.

---

# 🎯 Objective

To create a touchless LED control system that recognizes finger gestures and sends corresponding commands to an Arduino through serial communication.

---

#💡 Features

- ✋ Real-time gesture detection using webcam  
- 🔄 Serial communication with Arduino using PySerial  
- 💡 Control up to 5 LEDs with different finger gestures  
- 🧠 Easily extendable to control more devices  

---

# 🛠️ Tech Stack

- **Python 3.7+**
  - MediaPipe
  - OpenCV
  - PySerial
- **Arduino UNO/Nano**
  - Relay or LED connected to digital pins

---

#🤖 Gesture-to-LED Mapping

| Fingers Shown | Action        | Arduino Serial Input |
|---------------|---------------|-----------------------|
| 1             | Turn ON LED 1 | `1`                   |
| 2             | Turn ON LED 2 | `2`                   |
| 3             | Turn ON LED 3 | `3`                   |
| 4             | Turn ON LED 4 | `4`                   |
| 5             | Turn OFF ALL  | `0`                   |

---

## 🚀 Setup & Installation

### ✅ Python Setup

```bash
pip install -r requirements.txt
python hand_gesture_led_control.py

