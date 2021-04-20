# Night Time Vehicle Detection and Tracking by Fusing Vehicles Parts from Multiple Cameras

This repo is the official implementation for [Night Time Vehicle Detection and Tracking by Fusing Vehicle Parts from Multiple Cameras]

### Video Demo
The video demo will be released here. [Video Demonstration]

### Dataset
The dataset can be downloaded from: [Dataset]. 

The dataset consists of synchronized front and rear-view night time traffic surveillance videos which are recorded by two iPhone 8 with 1920×1088 resolutions at 30 FPS. The captured videos are in both sparse and dense traffic situations, within which two lighting conditions, e.g., low and dark, are separately provided by adjusting the iPhone lens exposure time. 

The vehicles at each 1-minute video are all carefully annotated, where a vehicle at one frame is labeled as a 4x3 matrix with its identify (first column) and its four vertices (second and third columns) in an anti-clockwise direction. These labels are given in "dense_dark_ground_truths.mat", "dense_low_ground_truths.mat", "sparse_dark_ground_truths.mat" and "sparse_low_ground_truths.mat". 

The traffic monitoring ROI of both front and rear views are given in "ROI.mat". 

The traffic landmarks of these monitoring ROIs are provided in "landmarks_front.avi" and "landmarks_rear.avi".

### Code

The code will be released here. 

### Bibtex
If you find our work useful in your research, please consider citing:

    @inproceedings{zhang2020night,
      title={Night Time Vehicle Detection and Tracking by Fusing Sensor Cues from Autonomous Vehicles},
      author={Zhang, Xinxiang and Story, Brett and Rajan, Dinesh},
      booktitle={2020 IEEE 91st Vehicular Technology Conference (VTC2020-Spring)},
      pages={1--7},
      year={2020},
      organization={IEEE}
    }

    The Transactions paper will be added here after online. 
