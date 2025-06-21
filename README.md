# rice-image-augmentation-pipeline
A comprehensive pipeline for rice leaf image augmentation using TensorFlow and OpenCV in Google Colab, with Google Drive integration.
# Rice Image Augmentation Pipeline

This project is a Google Colab-compatible Python pipeline that:
- Authenticates with Google Drive
- Downloads rice leaf images from a shared folder
- Applies various image augmentation techniques using TensorFlow and OpenCV
- Saves augmented images back to your Drive

## Features
- Supports up to 1000 augmentations per class
- Horizontal & vertical flipping
- Rotation, cropping, zoom, shear
- Custom augmentations with OpenCV
- Works directly with Google Drive folders

## Requirements
Run this in Google Colab. Make sure:
- The rice leaf images are in a Google Drive folder (shared or owned)
- You update the `drive_folder_id` with your folder's ID

## Installation
```python
!pip install tensorflow gdown tqdm matplotlib
