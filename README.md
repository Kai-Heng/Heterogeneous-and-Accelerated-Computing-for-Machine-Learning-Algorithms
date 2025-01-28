# Senior Design Project: Heterogeneous-and-Accelerated-Computing-for-Machine-Learning-Algorithms

**Team**: SDDEC24-05  
**University**: Iowa State University  

## Project Overview

This project involves developing a high-speed eye-tracking system to assist individuals with disabilities in performing day-to-day activities through eye movement tracking. The system includes three key models running in parallel:  
- Blink Detection  
- Pupil Tracking  
- Semantic Segmentation  

The implementation was carried out on the Xilinx Kria KV260 board, with a focus on achieving a throughput of 200 FPS for blink and pupil detection running simultaneously.

![Project Overview Diagram](https://sddec24-05.sd.ece.iastate.edu/images/HAML2.png)

### Problem Statement
The client aims to create a system to:
- Use pupil movement to control the mouse cursor.
- Predict the user’s state (e.g., seizures, stress, fatigue).

### Functional Requirements
- Implement three models (blink detection, pupil detection, and semantic segmentation) running in parallel.
- Ensure blink and pupil detection achieve 200 FPS throughput when running together.

### Constraints
- The client provides two ML models (blink and pupil tracking).
- The implementation is restricted to the Xilinx Kria KV260 evaluation board.

## Project URL
[Project Website](https://sddec24-05.sd.ece.iastate.edu/#)

## Features
- Real-time image processing pipeline with multithreaded architecture.
- Deployment on FPGA with DPU for hardware acceleration.
- Semantic segmentation model for high-speed image analysis.
