# Multitask-Learning-of-Fruit-Attributes

### This project introduces a novel approach to fruit attribute classification using deep learning. It focuses on two key tasks:

1. Size Classification: Classifying fruits as small, medium, or large using monocular RGB images, enhanced by depth information from MiDaS.

2. Multitask Classification (Size + Ripeness): Implementing a single CNN backbone for parallel classification of both fruit size and ripeness.

### Motivation

Accurate fruit size and ripeness estimation is essential for applications such as yield estimation, autonomous harvesting, and precision agriculture. Traditional object detection models, such as Faster R-CNN, struggle with size classification. Our approach bypasses this limitation by integrating depth information and leveraging multitask learning.