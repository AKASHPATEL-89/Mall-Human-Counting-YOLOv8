Mall Human Counting System using YOLOv8

This project is a real-time human counting system for malls developed using Python and YOLOv8.
It detects, tracks, and counts people moving UP and DOWN across predefined virtual lines in video footage.

The system uses object detection, multi-object tracking, and line-crossing logic to accurately count entry and exit movements.

FEATURES

Real-time person detection using YOLOv8

Multi-object tracking with SORT algorithm

Unique ID assigned to each detected person

Entry and exit counting using virtual lines

Region of Interest (ROI) masking to reduce false detections

Works with recorded video files

HOW IT WORKS

YOLOv8 detects persons in each video frame

SORT tracker assigns a unique ID to every person

Virtual lines are defined for UP and DOWN movement

When a tracked person crosses a line, the count is updated

ROI masking limits detection to the required area

TECH STACK

Python

YOLOv8 (Ultralytics)

OpenCV

SORT Tracking

NumPy

APPLICATIONS

Smart Malls

Crowd Management

Surveillance Systems

Public Place Monitoring

PROJECT STRUCTURE

Mall-Human-Counting-YOLOv8
│
├── Images (video and mask files)
├── Yolo-Weights (YOLOv8 model weights)
├── sort.py
├── project.py
├── requirements.txt
└── README.md

HOW TO RUN

Install required Python libraries

Download YOLOv8 weights and place them in the Yolo-Weights folder

Run the project using the command:

python project.py

KEY LEARNINGS

Real-time object detection pipeline

Multi-object tracking using SORT

Line-crossing based people counting

Practical application of Computer Vision concepts

AUTHOR

Akash Singh
B.Tech Student 
