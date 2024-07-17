# Robust Real-Time Vehicle License Plate Detection System

## Overview
This project implements a real-time vehicle license plate detection system using YOLOv8 for vehicle and license plate recognition. The system is enhanced with the SORT algorithm for tracking and an interpolation algorithm to recover missing license plate data when plates are temporarily obscured.

## Features
- **YOLOv8 for Detection**: Uses YOLOv8 for accurate detection of vehicles and license plates.
- **SORT for Tracking**: Implements the Simple Online and Realtime Tracking (SORT) algorithm to track vehicles across frames.
- **Interpolation for Data Recovery**: Recovers license plate numbers obscured by other vehicles using an interpolation algorithm.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/robust-vehicle-license-plate-detection.git
   cd robust-vehicle-license-plate-detection
