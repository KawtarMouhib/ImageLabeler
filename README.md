# ImageLabeler

ImageLabeler is a Python-based tool that utilizes AWS Rekognition to automatically detect and label objects within images stored in an Amazon S3 bucket. The project extracts labels with a specified confidence threshold and visualizes them by drawing bounding boxes around detected objects. It provides an easy-to-use interface for analyzing images and visually displaying detected labels using Matplotlib.

The setting up of the aws structure is done using Terraform (S3 bucket - Iam roles 
