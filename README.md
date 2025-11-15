# YOLOv11 ROS2 C++

Simple ROS2 node for running YOLOv11 ONNX inference using OpenCV + ONNX Runtime (CPU only).

### Features

- YOLOv11 inference (ONNX Runtime C++)

- OpenCV preprocessing & drawing

- ROS2 publisher for detection results

- Very lightweight, no CUDA required

### Prerequisites

- ROS 2 (Foxy / Humble)

- OpenCV ≥ 4.5

- ONNX Runtime (C++ API)

- cmake, colcon, rosdep

### Model Setup

Download YOLOv11 ONNX model and place files like this:

- models/yolov11.onnx

- models/coconames.txt

### Build & Run

Clone

    git clone https://github.com/ichsanyudika/Yolov11-ROS2-CPP.git
    cd Yolov11-ROS2-CPP

Build

    colcon build --symlink-install

Source

    source install/setup.bash

Run

    ros2 run yolo_ws main

### Result

![](output/output.png)  
