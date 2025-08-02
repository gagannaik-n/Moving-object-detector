# Moving-object-detector
This Python script uses OpenCV to implement a simple motion detection system through your webcam. It detects and highlights moving objects in real-time by comparing consecutive frames from the video feed.

# 🎥 Moving Detection using OpenCV
This Python project uses OpenCV to detect moving through your webcam in real time. It highlights moving objects by drawing yellow rectangles around them and labeling them as "Moving Object".

## 🛠 Requirements
- Python 3.x
- OpenCV
- NumPy
  
Install dependencies:
pip install opencv-python numpy

## ▶️ How to Run
https://github.com/gagannaik-n/Moving-object-detector.git
python moving_detector.py
Press `q` to exit the program.

## ⚙️ How It Works
- Captures video from webcam.
- Converts frames to grayscale and applies Gaussian blur.
- Calculates difference between frames to detect moving.
- Draws a rectangle around detected moving objects.
  
## ✏️ Customization
To make detection more or less sensitive, change:
if cv2.contourArea(c) < 1000:
Lower value = more sensitive to small motion.

## 📄 License
Free to use for learning and personal projects.
