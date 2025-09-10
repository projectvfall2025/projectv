# projectV - Object Detection & Vision-Language Modeling (VLM) for Construction Sites
Project Overview:
This project focuses on applying Object Detection and Vision-Language Models (VLMs) to enhance safety, monitoring, and automation in construction sites. By leveraging state-of-the-art using YOLOv8/YOLO11 for object detection and integrating Vision-Language reasoning, the system identifies and interprets visual elements like hardhats, workers, machinery, and unsafe conditions in real time.
The goal is to support safety compliance, incident prevention, and operational insights in dynamic construction environments.
Hardhat & PPE Detection – Detects safety gear such as helmets and identifies workers not wearing protective equipment.
Worker & Equipment Tracking – Tracks personnel and machinery across video streams for situational awareness.
Vision-Language Reasoning (VLM) – Converts detections into human-readable insights (e.g., "3 workers near the excavator, 1 without hardhat").
Confusion Matrix Analysis – Evaluates model performance with detailed per-class error insights.
Scalable Training – Trained with YOLO on a custom construction dataset (Hardhat vs. No-Hardhat) with augmentation for robustness.
Visualization – Bounding boxes, confidence scores, and validation predictions
