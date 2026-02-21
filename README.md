# 🎥 Movement Detector (OpenCV)

A real-time motion detection system built with Python and OpenCV.  
This project detects movement in a video file using background subtraction and contour detection.

---

## 🚀 Features

- 📹 Detects motion in pre-recorded video files
- ⚡ Real-time frame processing
- 🎯 Adjustable sensitivity and minimum contour area
- 🛠 Compatible with multiple OpenCV versions
- 🖥 Live visualization:
  - Original video feed
  - Threshold (debug) view
- ⌨ Press `q` to exit detection

---

## 🧠 How It Works

1. Capture the first frame as the background reference.
2. Convert frames to grayscale and apply Gaussian blur.
3. Compute absolute difference between background and current frame.
4. Apply thresholding and dilation.
5. Detect contours.
6. If contour area exceeds minimum threshold → Movement Detected.

---

## 📂 Project Structure
MovementDetector.py

123.mp4

README.md

requirements.txt

---

## 📈 Future Improvements

- Live webcam support
- Background updating mechanism
- Save snapshots when movement detected
- Email / Telegram alert integration
- AI-based object classification

---

## 🏗 Built With

Python

OpenCV

---

## 👨‍💻 Author

Snigdho Das

Computer Applications Student
