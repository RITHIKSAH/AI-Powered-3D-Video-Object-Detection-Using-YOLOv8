# AI-Powered 3D Video Object Detection Using YOLOv8

This repository contains an AI-powered 3D video object detection system, developed as part of HackaFuture2025 (24-hour hackathon by Atkins).
The project uses YOLOv8 to detect key objects (hurdle, steel, no entry, and Person) in 360° construction videos, improving site monitoring and safety analysis.

Features
- Trained YOLOv8 model on a custom dataset
- Real-time object detection on images and videos
- Automated dataset preprocessing and corrupt image removal
- Processed 360° construction video with labeled detections

Installation

1. Clone the Repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2. Set Up a Virtual Environment (Recommended)
conda create --name yolo_env python=3.9 -y
conda activate yolo_env

3. Install Dependencies
pip install ultralytics opencv-python torch torchvision tqdm matplotlib


Jupyter notebook code file can be found in repository.


