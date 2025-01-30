# Plastic Detection System Using Drones and YOLO

## Overview
This project focuses on detecting plastic waste using drones equipped with the YOLO (You Only Look Once) object detection algorithm. The system is designed to process aerial images to identify plastic objects, aiding in environmental conservation efforts.

## Features
- **Plastic Detection**: Identifies plastic waste in aerial images.
- **YOLO-based Model**: Utilizes the YOLO algorithm for real-time object detection.
- **Dataset Processing**: Trained on a dataset of images containing plastic and non-plastic objects.
- **Bounding Box Annotation**: Highlights detected plastics in images.
- **Deployment on Drones**: Designed to integrate with drones for automated detection.

## Technologies Used
- **Deep Learning**: YOLO for object detection
- **Python**: Primary language for model development
- **OpenCV**: Image processing and manipulation
- **TensorFlow/PyTorch**: For training and deploying the model
- **Drone Integration**: Capturing aerial images for detection

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- TensorFlow / PyTorch
- OpenCV
- NumPy
- Matplotlib

## Dataset
The model is trained on a dataset containing images of plastic waste and other objects. The dataset was preprocessed using:
- **Data Augmentation**
- **Annotation with LabelImg**
- **Conversion to YOLO format**



## Results
- **Mean Average Precision (mAP)**: ~85%
- **Inference Speed**: ~30 FPS on a GPU
- **Plastic Detection Accuracy**: High precision and recall rates

## Limitations
- The model does not perform **real-time detection** on drones yet.
- Performance varies with lighting conditions and camera quality.
- The dataset may need further expansion for higher generalization.

## Future Improvements
- **Real-time drone integration** for in-flight plastic detection.
- **Model optimization** for improved efficiency on edge devices.
- **Integration with cloud storage** for data analysis and reporting.

## Contributors
- **Willayat Hussain**
- **Krishnanshu Mittal**


