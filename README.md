# Football Analysis Project

## Introduction
The aim of this project is to detect and track players, referees, and footballs in video footage using YOLO, a state-of-the-art object detection model. To improve detection accuracy, we will fine-tune the model through additional training. We will also use K-means clustering for pixel segmentation to group players based on the color of their t-shirts, which will help in determining each team's ball possession percentage during the match.

Optical flow will be employed to measure camera movement across frames, enhancing the precision of player movement tracking. By applying perspective transformation, we can convert the scene’s depth and scale player movement from pixels to meters. Using this information, we will calculate the distance traveled and the speed of each player.

This project addresses real-world challenges in sports analytics, combining advanced computer vision and machine learning techniques, making it ideal for both beginners and experienced practitioners.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas# Football-Analysis-ML-
