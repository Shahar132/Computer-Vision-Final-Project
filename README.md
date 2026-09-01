# Computer Vision Final Project

Object detection project for detecting **persons** and **vehicles** using YOLO models.

## Overview

The project compares multiple YOLO architectures for person and vehicle detection.

Models evaluated:
- YOLOv8n
- YOLO11n
- YOLO26n

The dataset was built from Flickr30k images and annotated for the two target classes.

## Dataset

- Training images: 1,200
- Validation images: 240
- Classes:
  - Person
  - Vehicle

## Results

Best model: **YOLO26n**

- mAP50-95: **0.5569**
- Best epoch: **95**
- Image size: 640
- Batch size: 16

## Technologies

- Python
- Jupyter Notebook
- PyTorch
- Ultralytics YOLO
- Computer Vision
- Object Detection

## Project Files

- `final_project_1.ipynb` – full training, evaluation and experimentation notebook

## Notes

The full dataset and trained model weights are not included in this repository due to file size and dataset distribution considerations.
