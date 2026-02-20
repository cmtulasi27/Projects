# LiDAR–Camera Calibration & Temporal Synchronization Framework
## Overview
This project presents a comprehensive framework for spatial calibration and temporal synchronization between a LiDAR sensor and a monocular camera.
It ensures accurate alignment of multimodal sensor data for applications like autonomous driving and sensor fusion.

## Features
- Target-based LiDAR–camera calibration
- Temporal synchronization using timestamps
- Nearest neighbor frame matching
- Projection of 3D LiDAR points onto 2D camera images
- Custom dataset support

## Hardware Used

- Velodyne VLP-16 LiDAR
- Monocular Camera
- Checkerboard calibration target

## Methodology
- Data Acquisition – Capture LiDAR point clouds and camera images/videos.
- Frame Extraction – Convert video into timestamped frames.
- Timestamp Synchronization – Apply offset correction for clock drift.
- Nearest Neighbor Matching – Align LiDAR and camera frames.
- Calibration – Compute intrinsic & extrinsic parameters.
- Projection – Map 3D LiDAR points to 2D image plane.

## Tech Stack
- MATLAB (Calibration Toolboxes)
- Python (Data Processing)
- OpenCV
- Velodyne LiDAR Tools

## Results
- Accurate spatial alignment between sensors
- Successful timestamp synchronization
- Reliable LiDAR-to-image projection

## Applications
- Autonomous driving perception
- Multi-sensor fusion research
  
