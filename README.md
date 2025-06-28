# Gesture-Recognition (ROS 2)

This module performs real-time **hand gesture detection** using a webcam feed. It uses **MediaPipe's Hand Landmark Model** to extract 21 keypoints per hand and applies simple rule-based logic to classify gestures based on finger positions.

## Features
- 🖐 Open palm 
- ✊ Fist 
- ✌ Peace sign 
- 👉 Thumb 
- 👈 Index 

## Run

```bash
ros2 run gesture_controller gesture_control


Dependencies

    OpenCV

    Mediapipe

    ROS 2 (Humble)
