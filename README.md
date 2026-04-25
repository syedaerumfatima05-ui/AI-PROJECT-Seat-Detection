**AI-Based Smart Campus Detection System**

**Available vs Occupied Seat Detection**

This project is developed as part of the SWS405 – Applied Artificial Intelligence course. It focuses on building a Computer Vision Object Detection system to identify whether seats in a campus environment are available or occupied using deep learning techniques.
The system uses a custom dataset collected from real campus locations, where images were manually annotated with bounding boxes to classify seats into two categories: available and occupied. The model is trained using the YOLOv8 (You Only Look Once) object detection algorithm, which is known for its balance between speed and accuracy, making it suitable for real-time applications.

**Project Objective**

The goal of this project is to develop an intelligent system that can:
Detect seats in images using object detection
Classify each seat as available or occupied
Provide bounding boxes with confidence scores
Support real-time smart campus applications
This system can be applied in environments such as libraries, classrooms, and study areas to help students quickly find available seating.

**Technologies Used**

Python
YOLOv8 (Ultralytics)
OpenCV
Roboflow (for dataset annotation and preprocessing)
Google Colab (for training and experimentation)

**Dataset**

A custom dataset was created for this project, consisting of images captured in various campus environments under different lighting conditions and angles. Each image was annotated with bounding boxes and labeled into two classes:
- Available Seat
- Occupied Seat
The dataset ensures diversity and adheres to ethical guidelines by avoiding identifiable faces and personal data.

**Key Features**

End-to-end AI pipeline (data collection → annotation → training → evaluation → inference)
Real-time object detection capability
Custom dataset tailored for campus environments
Model evaluation using precision, recall, and mAP

**Real-World Application**

This system can be integrated into a Smart Campus Solution, where cameras installed in study areas can automatically detect and display available seating in real time, improving space utilization and student convenience.
