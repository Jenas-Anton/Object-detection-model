# 🚗 Object Detection Model & Real-time Vehicle Counter

This repository contains two related projects:
1. Object Detection Model
2. Real-time Vehicle Counter

Both projects use OpenCV for detecting and counting vehicles in video streams, making them ideal for traffic monitoring applications.

## 🎯 Object Detection Model

This Python script uses OpenCV for real-time vehicle detection in videos. It employs background subtraction, contour detection, and centroid tracking to identify vehicles crossing a specified line.

### Key Features
- Background subtraction for isolating moving objects
- Contour detection to identify vehicle shapes
- Centroid tracking to count vehicles crossing a predefined line
- Real-time display of vehicle count and bounding boxes

## 🚦 Real-time Vehicle Counter

Building upon the Object Detection Model, this script provides a comprehensive solution for real-time vehicle counting in video streams.

### Key Features
- Background subtraction using MOG algorithm
- Contour detection for accurate vehicle identification
- Centroid tracking for precise counting of vehicles crossing a specified line
- Real-time visualization of vehicle count and bounding boxes

## 🛠️ Requirements

To run these scripts, you'll need:
- Python 3.x
- OpenCV
- NumPy

## 🚀 Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/object-detection-vehicle-counter.git
   ```

2. Install the required packages:
   ```
   pip install opencv-python numpy
   ```

## 💻 Usage

1. Navigate to the project directory:
   ```
   cd object-detection-vehicle-counter
   ```

2. Run the desired script:
   ```
   python object_detection_model.py
   ```
   or
   ```
   python real_time_vehicle_counter.py
   ```

3. Follow the on-screen instructions to select the video input and set the counting line.

## 📊 Output

Both scripts will display a window showing the video feed with:
- Bounding boxes around detected vehicles
- A line indicating the counting threshold
- Real-time count of vehicles that have crossed the line

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/your-username/object-detection-vehicle-counter/issues) if you want to contribute.



