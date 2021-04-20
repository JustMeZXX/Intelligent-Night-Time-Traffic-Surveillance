# Night Time Vehicle Detection and Tracking by Fusing Vehicles Parts from Multiple Cameras

This repo is the official implementation for [Night Time Vehicle Detection and Tracking by Fusing Vehicle Parts from Multiple Cameras]

### Video Demo
The video demo will be released here. [Video Demonstration]

### Dataset
The dataset can be downloaded from: [Dataset]. 

The dataset consists of synchronized front and rear-view night time traffic surveillance videos which are recorded by two iPhone 8 with 1920×1088 resolutions at 30 FPS. The captured videos are in both sparse and dense traffic situations, within which two lighting conditions, e.g., low and dark, are separately provided by adjusting the iPhone lens exposure time. 

The vehicles at each 1-minute video (1800 frames) are all carefully annotated, where a vehicle contour (in polygon) at each frame is labeled as a 4x3 matrix. The matrix rows reprenset vertices of a vehicle contour in an anti-clockwise direction. The vehicle identies are given in the first column, and the x-y coordinates of vertices are given in the second and third columns. These polygon annotations are provided as .mat files in folder "vehicle_contour_polygon". 

Also, the annotations of vehicle headlights and taillights at each 1-minute video are provided, where a vehicle headlight or taillight (in bbox) at each frame is labeled as a 1x4 vector [left (x-coordinate), top (y-coordiante), width, height]. These bbox annotations are provided as .mat file in folder "headlight_and_taillight_bbox". 

The traffic monitoring ROI of both front and rear views are provided in "ROI.mat", and their corresponding traffic landmarks are provided in "landmarks_front.avi" and "landmarks_rear.avi", respectively.



### Code

The code will be released here. 

### Bibtex
If you find our work useful for your research, please consider citing:

    @INPROCEEDINGS{9128989,
      author={Zhang, Xinxiang and Story, Brett and Rajan, Dinesh},
      booktitle={2020 IEEE 91st Vehicular Technology Conference (VTC2020-Spring)}, 
      title={Night Time Vehicle Detection and Tracking by Fusing Sensor Cues from Autonomous Vehicles}, 
      year={2020},
      volume={},
      number={},
      pages={1-7},
      doi={10.1109/VTC2020-Spring48590.2020.9128989}}

    The Transactions paper will be added here after appearing online. 
