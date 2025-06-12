# Player_movement_analyzer

## Introduction
The objective of this project is to detect and track players, referees, and footballs in a video using YOLO (You Only Look Once), a state-of-the-art object detection algorithm. To enhance detection accuracy, we will fine-tune and train the model on domain-specific data.

Beyond detection, we aim to assign players to their respective teams by analyzing the color of their jerseys. This will be achieved through K-Means clustering, a pixel segmentation and clustering technique that identifies dominant colors. With accurate team classification, we can compute meaningful match statistics, such as the percentage of ball possession by each team.

To understand player dynamics within the game, we will apply optical flow techniques to estimate camera movement between frames. This adjustment is crucial for isolating player motion from camera-induced motion. Furthermore, we will incorporate perspective transformation to map the image coordinates to real-world distances. This allows us to quantify a player's displacement and speed in meters rather than pixels.

By integrating these techniques, the project enables detailed analysis of player performance and team dynamics. It encompasses core computer vision concepts and real-world challenges, making it a comprehensive and educational endeavor for both beginners and experienced machine learning engineers.

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
- 
