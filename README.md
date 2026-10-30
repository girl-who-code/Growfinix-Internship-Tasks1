# Growfinix-Internship-Tasks1
Task 1: Automated Image/Video Metadata Extraction 
# Task 1: Automated Image/Video Metadata Extraction

## Project Overview

This project implements an automated Computer Vision Pipeline that analyzes DSLR images and cinematic video frames to extract important metadata.

The system uses YOLOv8 for object detection, OpenCV for image processing, and K-Means clustering for dominant color palette extraction.

## Objectives

- Automatically detect objects in images and video frames.
- Extract the five dominant colors from images.
- Calculate image brightness and lighting scores.
- Analyze image contrast.
- Generate automatic metadata tags.
- Export metadata into CSV and JSON formats.

## Technology Stack

- Python
- OpenCV
- PyTorch
- YOLOv8
- Scikit-learn
- K-Means Clustering
- Pandas
- Matplotlib
- Google Colab

## Key Features

1. Object Detection using YOLOv8.
2. Dominant Color Extraction using K-Means.
3. Brightness and Lighting Analysis.
4. Contrast Score Calculation.
5. Automatic Metadata Tagging.
6. Video Frame Extraction.
7. CSV and JSON Report Generation.

## How to Run

1. Open the Google Colab notebook.
2. Install the required libraries.
3. Load the pretrained YOLOv8 model.
4. Upload images or video files.
5. Execute the image analysis functions.
6. Perform object detection and color extraction.
7. Analyze brightness and contrast.
8. Process video frames.
9. Generate metadata reports.
10. Download the generated output files.

## Expected Outputs

- Object detection images with bounding boxes.
- Five dominant colors for each analyzed asset.
- Brightness and lighting scores.
- Contrast scores.
- Automatically generated metadata tags.
- CSV and JSON metadata reports.

## Project Files

- `Task1_Image_Video_Metadata.ipynb` – Google Colab implementation.
- `image_video_metadata.csv` – Extracted metadata.
- `image_video_metadata.json` – Structured metadata.
- `annotated_images.zip` – Annotated object detection images.

## Conclusion

This project demonstrates an automated media metadata extraction system using Computer Vision and Deep Learning techniques. It helps organize digital media assets by identifying objects, extracting color information, analyzing image quality, and generating metadata automatically.

## Internship

**Organization:** Growfinix  
**Task:** Task 1 – Automated Image/Video Metadata Extraction

