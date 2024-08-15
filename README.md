Driver Drowsiness Detection using OpenCV and Keras
Overview
Driver drowsiness detection is a system that can detect when a driver is becoming drowsy and alert them to prevent accidents. This project uses deep learning and computer vision techniques to monitor the driver's eyes and facial expressions to determine their state of alertness.

This project leverages OpenCV for real-time video capture and processing, and Keras (with TensorFlow backend) for building and running a Convolutional Neural Network (CNN) model to classify drowsiness.

Features
Real-time Eye Blink Detection: Monitors the driver's eye state to detect blinking patterns and eye closure.
Head Pose Estimation: Detects head tilts and turns to assess whether the driver is paying attention.
Drowsiness Detection: Analyzes facial features to detect signs of fatigue, such as prolonged eye closure or yawning.
Alert System: Sounds an alarm when signs of drowsiness are detected.
Technologies Used
Python 3.x
OpenCV for image and video processing
Keras with TensorFlow backend for building the CNN model
dlib for facial landmark detection
Numpy for numerical operations
Pygame for playing alert sounds
