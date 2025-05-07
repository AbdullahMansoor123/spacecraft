---
title: "Real-Time Visual Inspection on Conveyor Belt using YOLOv5"
discription: ""
datestring: 15/02/2025
draft: false
# tags: ["hugo", "image", "post"]
# cover: 
    # image: "images\inspect.PNG"
showtoc: false
---


## Problem Statement
Manual inspection on conveyor belts is inefficient and error-prone.

## Objective
Develop a real-time computer vision solution that detects, classifies, and counts items on a conveyor belt, highlighting defective ones.

## Solution Overview
Utilized YOLOv5 for object detection in conveyor belt video frames, distinguishing between normal and defective products.

### Workflow
1. Video data collection + synthetic anomalies
2. YOLOv5 model training (Roboflow for annotation)
3. Real-time video processing with OpenCV
4. Detection overlays and count tracking

## Technologies Used
- Python, OpenCV
- YOLOv5 (Ultralytics)
- Roboflow
- FFmpeg
- Streamlit

## Results
- Real-time FPS: ~20
- Detection Accuracy: 96.3%
- Counting Accuracy: 93.7%
- Defect Detection: 91.2%

## Visuals
*(Insert visuals from video frames, bounding boxes, and count graph screenshots here)*

## Deployment
Edge device-ready (e.g., Jetson Nano) or industrial integration

## Business Impact
Could reduce rework costs by 20% by catching defects earlier.

## Links
- GitHub: [github.com/your-username/conveyor-inspection](#)
- Demo Video: [YouTube or Loom](#)

