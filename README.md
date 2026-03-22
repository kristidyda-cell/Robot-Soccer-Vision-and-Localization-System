# MSL soccer robot 

## Overview
This project implements a robot soccer vision and localization system in C++ using OpenCV and ROS. The codebase includes front vision and omnidirectional vision modules for ball detection, field-feature extraction, robot pose estimation, obstacle interpretation, and structured perception output for the world model and higher-level control logic.

The code supports competitions such as the FIRA RoboSot Soccer Competition and the RoboCup Middle Size Soccer Competition.

This repository was adapted from the NUDT Nubot MSL soccer robot codebase. Huge thanks to the original team.

## Drivers and development

### Camera
- camera_umd
- gscam and tiscamera ROS example
- zed-ros-wrapper