# Object Detection for Autonomous Driving

## Overview

This project focuses on training three famous object detection models on the Masterarbeit D3FRZ dataset, which consists of 3000 images. The dataset primarily focuses on detecting objects related to autonomous driving, including cars, pedestrians, and trucks.

### Dataset

- **Dataset Name**: Masterarbeit D3FRZ
- **Dataset Source**: [Roboflow Universe](https://universe.roboflow.com/masterarbeit-d3frz/r-s_2k)
- **Number of Images**: 3000
- **Classes**: Car, Pedestrian, Truck

## Object Detection Models

### 1. SSD MobileNetV2

- **Description**: SSD MobileNetV2 is a variant of the Single Shot Multibox Detector (SSD) model, which uses MobileNetV2 as its base network architecture. It offers a good balance between speed and accuracy, making it suitable for real-time applications.
- **Performance**: MAP@0.5 = 55.8%

### 2. EfficientDet0

- **Description**: EfficientDet0 is part of the EfficientDet family of object detection models, known for their efficiency in terms of both computational resources and model size. EfficientDet models achieve state-of-the-art performance with fewer parameters.
- **Performance**: MAP@0.5 = 52.2%

### 3. YOLOv5s

- **Description**: YOLOv5s is a variant of the You Only Look Once (YOLO) object detection model. It is renowned for its simplicity, speed, and high accuracy. YOLOv5s uses a single neural network to predict bounding boxes and class probabilities directly from full images.
- **Performance**: MAP@0.5 = 59.0%

## Training

- **Framework**: PyTorch
- **Training Pipeline**: 
  - Data Preprocessing
  - Model Training
  - Evaluation
- **Hardware**: [Insert hardware specifications if available]
- **Training Strategy**: [Insert details of the training strategy, such as data augmentation techniques, learning rate schedule, etc.]

## Evaluation

- **Metrics**: Mean Average Precision (MAP) at IoU threshold 0.5
- **Benchmark Results**: [Insert comparison with state-of-the-art results if available]

## Usage

- **Inference**: Use the trained models for object detection tasks in autonomous driving scenarios.

## Acknowledgements

Special thanks to the creators of the Masterarbeit D3FRZ dataset for providing a valuable resource for autonomous driving research.

## License

This project is licensed under the [MIT License](LICENSE).

