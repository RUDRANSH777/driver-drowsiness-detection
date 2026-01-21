# Driver Drowsiness Detection System 🚗😴

The **Driver Drowsiness Detection System** is a real-time computer vision–based application designed to monitor a driver’s alertness using facial landmarks and eye-blink analysis.  
The system continuously analyzes webcam video input and triggers an audible alert when signs of drowsiness or sleep are detected, helping to reduce the risk of road accidents.

---

## ✨ Key Features
- **Real-time face detection** using Dlib’s frontal face detector
- **Facial landmark extraction** (68-point model)
- **Eye Aspect Ratio (EAR)**–based blink detection
- Classification of driver state into:
  - Active
  - Drowsy
  - Sleeping
- **Audio alarm alert** when sleep is detected
- **Live FPS monitoring** for performance tracking
- Works with standard webcam input

---

## 🧠 How the System Works
1. Captures live video frames from the webcam
2. Detects the driver’s face in each frame
3. Extracts eye landmarks using a pre-trained facial landmark model
4. Computes eye blink ratios to analyze eye closure duration
5. Determines the driver’s state (Active, Drowsy, or Sleeping)
6. Triggers an alert sound if prolonged eye closure is detected

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Facial Landmark Detection:** Dlib
- **Numerical Computation:** NumPy
- **Utility Functions:** imutils

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/RUDRANSH777/driver-drowsiness-detection.git
cd driver-drowsiness-detection
