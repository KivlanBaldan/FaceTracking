# FaceTracking
A real-time face tracking and landmark detection module built with OpenCV and MediaPipe. Provides seamless abstraction for multi-face mesh mapping, bounding box tracking, and coordinate isolation.
# Real-Time Face Tracking Module

A modular, highly optimized Python implementation for real-time face tracking, bounding box generation, and high-fidelity facial landmark mapping. Powered by **OpenCV** and **Google's MediaPipe framework**, this repository provides an object-oriented API designed to be dropped into any computer vision project—including video analytics, expression profiling, or human-computer interaction layers.

---

## 🚀 Core Features

- **High-Fidelity Tracking:** Supports both ultra-lightweight **Face Detection** (bounding boxes and 6 key facial points) and high-density **Face Mesh** (468+ 3D facial landmarks).
- **Multi-Face Concurrency:** Seamless tracking across multiple faces simultaneously within a single video frame with unique ID assignment boundaries.
- **Dynamic Coordinate Harvesting:** Dedicated utility functions to extract raw pixel $(x, y)$ coordinates for targeted facial regions (e.g., eyes, lips, jawline) to track directional changes or gestures.
- **Optimized Performance:** Fully vectorized frame handling ensures low-latency execution and optimal frame-per-second (FPS) output over standard webcams.

---

## 📁 Repository Directory Structure

```text
├── data/                  # Storage for captured face snapshots or video log buffers
├── src/                   # Source code scripts
│   ├── FaceTrackingModule.py   # The core reusable object-oriented class file
│   └── MainApplication.py # Run script demonstrating real-time webcam integration
├── requirements.txt       # Software package dependencies
└── README.md              # Project documentation
