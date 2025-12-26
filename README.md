# 🧍‍♂️ Mall Human Counting System using YOLOv8

This project is a **real-time human counting system** for malls developed using Python and YOLOv8.  
It detects, tracks, and counts people moving **UP and DOWN** across predefined virtual lines in video footage.

The system uses object detection, multi-object tracking, and line-crossing logic to accurately count entry and exit movements.

---

## Features

- Real-time person detection using YOLOv8
- Multi-object tracking with SORT algorithm
- Unique ID assigned to each detected person
- Entry and exit counting using virtual lines
- Region of Interest (ROI) masking to reduce false detections
- Works with recorded video files

---

## How It Works

1. YOLOv8 detects persons in each video frame
2. SORT tracker assigns a unique ID to every person
3. Virtual lines are defined for UP and DOWN movement
4. When a tracked person crosses a line, the count is updated
5. ROI masking limits detection to the required area

---

## Tech Stack

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- SORT Tracking
- NumPy

---

## Applications

- Smart Malls
- Crowd Management
- Surveillance Systems
- Public Place Monitoring

---

## Project Structure
Mall-Human-Counting-YOLOv8
│
├── Images/ # video and mask files
├── Yolo-Weights/ # YOLOv8 model weights
├── sort.py
├── project.py
├── requirements.txt
└── README.md





---

## How to Run

1. Install required Python libraries
2. Download YOLOv8 weights and place them in the `Yolo-Weights` folder
3. Run the project using the command:

```bash
python project.py


## Author

Akash Singh
B.Tech Student | Computer Vision Enthusiast

