Color Tracking Object using OpenCV
📌 Project Overview

This project implements Color Tracking Object Detection using Python and OpenCV. The application detects and tracks a specific color in real-time using a webcam or video feed. It highlights the detected colored object with bounding boxes or contours.

This project is ideal for beginners in Computer Vision and real-time image processing.

🎯 Features

Real-time color detection and tracking

Works with webcam or video input

Supports HSV color space for accurate detection

Detects a single or multiple colored objects

Lightweight and easy-to-understand code

🛠️ Technologies Used

Python 3

OpenCV (cv2)

NumPy

📂 Project Structure
color-tracking-object/
│
├── src/
│   ├── color_tracker.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── assets/          # (optional screenshots)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-beduduruhasini/color-tracking-object.git
cd color-tracking-object

2️⃣ Install Required Libraries
pip install -r requirements.txt


Or manually:

pip install opencv-python numpy

▶️ How to Run the Project
python src/main.py


📷 Press q to exit the camera window

🧠 How It Works

Captures frames from the webcam

Converts frames from BGR to HSV

Applies color thresholds to create a mask

Finds contours of the selected color

Tracks and highlights the detected object in real-time

🎨 Supported Colors

You can modify HSV ranges in the code to track:

Red

Blue

Green

Yellow

Any custom color

📸 Sample Output

Bounding box around detected colored object

Real-time object tracking

Smooth detection under normal lighting

🚀 Applications

Robotics

Object tracking systems

Gesture recognition

Surveillance

Computer vision learning projects

🔮 Future Enhancements

Track multiple colors simultaneously

Add GUI to select colors dynamically

Improve tracking using Kalman filters

Integrate with robotics hardware

👩‍💻 Author

BEDUDURU HASINI
B.Tech – Computer Science Engineering
