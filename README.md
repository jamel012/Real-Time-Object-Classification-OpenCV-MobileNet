# 🧠 Real-Time Object Classification with OpenCV & MobileNet

This project uses a pre-trained MobileNet SSD (Single Shot Detector) deep learning model with OpenCV to classify real-world objects from a webcam feed in real-time.

---

## 🎯 Project Features

- Real-time object detection using your webcam.
- Detects 20 common objects including: **person, car, cat, dog, bottle, etc.**
- Uses lightweight MobileNet SSD for fast and accurate results.
- Displays object label and confidence percentage on the video frame.

---

## 🖥️ Demo

https://github.com/user-attachments/assets/3b66b38f-5410-4861-a817-b27704f84152

---

## 🗂️ Object Categories

['background', 'aeroplane', 'bicycle', 'bird', 'boat',
'bottle', 'bus', 'car', 'cat', 'chair', 'cow', 'diningtable',
'dog', 'horse', 'motorbike', 'person', 'pottedplant',
'sheep', 'sofa', 'train', 'tvmonitor']

yaml
Copy
Edit

---

## 📁 Project Structure

object_classification/
├── MobileNetSSD_deploy.caffemodel # Pre-trained model weights
├── MobileNetSSD_deploy.prototxt # Model architecture
├── object_classification.py # Main Python script
└── README.md # Project instructions

yaml
Copy
Edit

---

## ⚙️ Requirements

Install required Python packages:

```bash
pip install opencv-python numpy
📥 Download Pre-trained Model
You’ll need two files:

MobileNetSSD_deploy.prototxt

MobileNetSSD_deploy.caffemodel

Place them in the same folder as the Python script.

🚀 How to Run
bash
Copy
Edit
python object_classification.py
Press Q to quit the window.

🛠️ How It Works
Loads a pre-trained MobileNet SSD model.

Captures video from the webcam.

For each frame:

Runs object detection.

Draws bounding boxes and labels on detected objects.

🌟 Future Improvements
Save detected frames to disk.

Add sound alerts (e.g., “Person detected!”).

Detect from a video file instead of webcam.

Build a web interface for object uploads.

📚 Credits
OpenCV

MobileNet SSD

