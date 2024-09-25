# ImageLabeler

ImageLabeler is a Python-based tool that utilizes AWS Rekognition to automatically detect and label objects within images stored in an Amazon S3 bucket. The project extracts labels with a specified confidence threshold and visualizes them by drawing bounding boxes around detected objects. It provides an easy-to-use interface for analyzing images and visually displaying detected labels using Matplotlib.

## Features
- Automatic object detection and labeling using AWS Rekognition.
- Visualization of detected labels with bounding boxes around objects.
- Infrastructure setup using Terraform for managing AWS resources.

## Requirements
- Python 3.x
- Boto3
- Matplotlib
- AWS account with access to Rekognition and S3
- Terraform (for setting up AWS infrastructure)
