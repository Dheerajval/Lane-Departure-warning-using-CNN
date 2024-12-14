# Lane-Departure-warning-using-CNN

As of late, a troubling yet equally important issue, lane departure related accidents, has emerged- the 
danger zones being the road itself. The Lane Departure Warning System (LDWS) assists in this by 
identifying the limits of the lanes and alerting the driver in advance. Herein, we present an end to end 
solution for this problem which employs Convolutional Neural Network (CNN) technology to specify 
when a vehicle is in the lane and when it is to be corrected (left or right). 
In short, our main goal in this study is to analyze real—time videos and detect and predict when a 
vehicle deviated from the lane based on its boundaries. Autonomous and semi-autonomous vehicles 
mandate the use of lane detection systems. Our model uses CNN models and gives lane departure 
warnings for images inputs to assist in preventing vehicle accidents. The specific TuSimple dataset’s 
bent boundary images will be utilized to train and test our model. This set of data includes 3,626 clips 
of videos that were taken when cars were driven on a highway to create reasonable conditions for the 
detection of a lane.

A lane departure warning system (LDWS) detects unintended lane drifts, assisting drivers to stay within their designated lanes. This project leverages computer vision to alert drivers when a vehicle deviates from its lane.

Table of Contents
Overview
Features
Technologies Used
Installation
Usage
Demo
Contributing
License
Overview
This repository implements a Lane Departure Warning System using OpenCV and Python. The system processes live video feeds or pre-recorded videos to detect lane markings and triggers alerts for lane departures. It is designed to improve driving safety by warning the driver before an unintentional drift occurs.

Features
Real-time Lane Detection: Utilizes image processing to identify lane boundaries.
Warning Alerts: Provides visual or auditory alerts when a lane departure is detected.
Flexibility: Works with pre-recorded videos or live camera feeds.
Customizable Parameters: Adjust thresholds for lane detection accuracy.
Technologies Used
Python
OpenCV
NumPy
Installation
git clone https://github.com/your-username/lane-departure-warning.git
cd lane-departure-warning
Install dependencies:
git clone https://github.com/your-username/lane-departure-warning.git
cd lane-departure-warning
bash
Copy code
pip install -r requirements.txt  
Usage
Running the System:
bash
Copy code
python lane_warning_system.py  
Provide the path to a video file or use a live camera feed.
Observe the processed output with lane markings and warnings in case of deviation.
