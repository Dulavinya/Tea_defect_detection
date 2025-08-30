# Tea Defect Detection

This project applies advanced computer vision and deep learning techniques to detect defects in tea leaves. It leverages state-of-the-art models for leaf detection, yield quality prediction, and disease classification, aiming to automate tea quality assessment and assist in crop monitoring.

## Project Structure

- **Leaf_detection.ipynb** – Detects tea leaves in images using YOLOv8.
- **Yield_quality_detection.ipynb** – Predicts yield quality from tea leaf images using YOLOv8.
- **Leaf_disease_detection.ipynb** – Classifies tea leaf diseases using VGG16 (work in progress).
- **Fertilizer_Deficiency_Detection.ipynb** – Identifies nutrient deficiencies in tea leaves (future work).

## YOLOv8 (You Only Look Once v8)

YOLOv8 is the latest iteration of the YOLO object detection family, designed for fast and accurate real-time detection. Unlike traditional methods, YOLO predicts bounding boxes and class probabilities in a single forward pass, making it highly efficient.

**Use in this project:**
- Detecting tea leaves in images.
- Predicting yield quality based on visual leaf features.

**Advantages:** High speed, real-time performance, and robust detection accuracy.

## VGG16

VGG16 is a deep convolutional neural network with 16 layers, developed by the Visual Geometry Group at Oxford. It uses small 3×3 convolutional filters stacked deeply, followed by pooling and fully connected layers for image classification.

**Use in this project:**
- Classifying healthy vs diseased tea leaves.
- Detecting specific disease patterns for early intervention.

**Advantages:** Simple yet powerful architecture, effective for image classification tasks with limited data.

## Applications

- Automated leaf detection for dataset preparation and plantation monitoring.
- Yield and quality assessment to optimize tea production.
- Early disease detection to reduce crop losses.
- Potential extension to nutrient deficiency detection and other crop health monitoring.
