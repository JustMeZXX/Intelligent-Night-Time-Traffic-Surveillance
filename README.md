# Night Time Vehicle Detection and Tracking by Fusing Vehicles Parts from Multiple Cameras

This repo is the official implementation for [Night Time Vehicle Detection and Tracking by Fusing Vehicle Parts from Multiple Cameras]

### Video Demo
[Video Demonstration]

### Dataset
[Dataset]

The dataset consists of synchronized front and rear-view night time traffic surveillance videos which are recorded by two iPhone 8 with 1920×1088 resolutions at 30 FPS. The captured videos are in both sparse and dense traffic situations, within which two lighting conditions, e.g., low and dark, are separately provided by adjusting the iPhone lens exposure time. 

The vehicles at each 1-minute video are all carefully annotated, where a vehicle at one frame is labeled as a 4x3 matrix with its identify and its four vertices in an anti-clockwise direction. 

The traffic monitoring ROI of both front and rear views are given in "ROI.mat". 

The traffic landmarks of these monitoring ROIs are provided in the videos named as "landmarks_front.avi" and "landmarks_rear.avi".  
