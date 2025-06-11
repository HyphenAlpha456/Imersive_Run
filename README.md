# 🎮 Gesture-Controlled Game Using MediaPipe

A computer vision-based interactive system that uses **real-time body pose detection** to control a game using physical gestures — jump, crouch, move left/right, and even clap to start!

---

## 🧠 Inspiration

Traditional games rely heavily on keyboard and mouse input. This project explores **natural gesture-based controls** for a more immersive and inclusive experience. With minimal hardware (just a webcam), users can play a simple game using only their body movements.

---

## 🚀 Features

* Detects real-time body landmarks using **MediaPipe Pose**.
* Controls game character with:

  * 🙌 Clap to Start
  * 🕴️ Lean Left / Right → Move Left / Right
  * ⬆️ Jump Gesture → Jump
  * ⬇️ Crouch Gesture → Duck
* Displays gesture classification feedback on screen.

---

## 📁 Files Used

* `GestureControlledGame.py` – Main application script with OpenCV, MediaPipe, and PyAutoGUI logic.
* `requirements.txt` – List of dependencies.
* `README.md` – Project documentation (this file).

---

## 🛠️ Technologies Used

* **Python 3.12.5**
* **OpenCV** – Real-time video processing
* **MediaPipe** – Pose estimation and landmark detection
* **PyAutoGUI** – Simulating keyboard inputs
* **Matplotlib** – Optional visualization

---

## ✅ Practical Use Cases

This project can be adapted for:

### 🕹️ Gesture-Based Game Control

Control casual or fitness games hands-free using full body movements.

### 🧠 Neurodiversity-Friendly Interfaces

Provide **alternative input systems** for users with disabilities.

### 🏋️ Fitness & Physical Therapy Gamification

Gamify rehab and fitness exercises — track correct postures and movements.

### 🎮 Hands-Free Gaming

Perfect for VR/AR settings or motion-based arcades.

### 🧑‍🏫 Educational Games for Kids

Engage children in physical learning via interactive pose-based play.

### 🏠 Smart Home Interaction (Experimental)

Potential to extend gestures for home automation (e.g., clap to toggle lights).

### 🎥 Interactive Art Installations

Allow visitors to interact with exhibits using gestures — no contact needed.

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python GestureControlledGame.py
```

Make sure your webcam is connected. Press `Esc` to exit.

---

## 📌 Notes

* Works best with a well-lit room and minimal background clutter.
* Mid-line calibration is done based on your shoulder height at startup.
* All inputs are simulated using PyAutoGUI — no external hardware needed.

---
