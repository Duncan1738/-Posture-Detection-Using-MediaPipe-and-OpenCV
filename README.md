#  Posture Detection Using MediaPipe and OpenCV

This project tracks **upper body posture** using **MediaPipe Pose landmarks** and analyzes **neck and torso angles** to detect **good vs. bad posture**.  
It works in **real time via webcam** or with **pre-recorded video files** and highlights incorrect sitting postures by drawing joint lines and showing live angle feedback.

---

## Key Features

✅ **Real-time Posture Tracking** via webcam  
✅ **Offline Video Processing** with posture analysis  
✅ **MediaPipe Pose Detection** (25 keypoints)  
✅ **Neck and Torso Angle Calculation**  
✅ **Visual Feedback** (lines, angles, posture status)  
✅ **Bad Posture Warning** after prolonged misalignment  
✅ **Video Recording & Export (MP4)**  

---
## How It Works

### 📌 What it measures:
- **Neck Angle** – Between **left shoulder and left ear**
- **Torso Angle** – Between **left hip and left shoulder**
- **Shoulder Alignment** – Distance between left and right shoulder

### Posture Logic:
- **Good Posture:**  
  - Neck angle ≥ 45°  
  - Torso angle ≥ 10°  
  - Shoulders aligned  
- **Bad Posture:**  
  - Neck angle < 25°  
  - Torso angle < 10°  
  - Shoulder misalignment

If bad posture is sustained for more than `180 seconds`, a warning is triggered.

---

##  Requirements

📊 Example Output
Overlay:

Joint keypoints labeled 0–24

Angles displayed in real-time

Neck/torso analysis lines drawn on screen

Posture Status:

Good Posture in ✅ green

Bad Posture in ❌ red

📜 License
This project is licensed under the MIT License.

📧 Contact
Duncan Kibet
🔗 https://github.com/Duncan1738


