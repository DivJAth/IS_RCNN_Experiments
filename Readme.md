Requirements:
1. Install torch, torch vision
2. git clone git@github.com:DivJAth/IS_RCNN_Experiments.git
3. Demo: IS_RCNN_Experiments/vision/torchvision/models/detection/faster_rcnn_experiment.ipynb

Files where the code was changed to integrate fast-rcnn and kalman filter
>a. Integration of Kalman filter and fast-rcnn  
   >> IS_RCNN_Experiments/vision/torchvision/models/detection/generalized_rcnn.py
 
>b. Kalman-filter and Hungarian Algorithm for tracking and detection.
   >> IS_RCNN_Experiments/vision/torchvision/models/detection/sort.py

<p align="center">
  <img src="results.gif" alt="Object Tracking with Fast-RCNN" height="700" width="900" />
  <p align="center">Sample output from Object Tracking with Fast-RCNN</p>
</p>

Reference:
1. SORT: A Simple, Online and Realtime Tracker Copyright (C) 2016 Alex Bewley alex@dynamicdetection.com
2. Fast-rcnn from torch vision

