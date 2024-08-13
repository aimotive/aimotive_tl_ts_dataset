# aiMotive 3D Traffic Light and Traffic Sign Dataset
This repository stores the dataset introduced in the 'Accurate 3D Automatic Annotation of Traffic Lights and Signs for Autonomous Driving' paper. The dataset consists of 3D bounding boxes of traffic lights and traffic signs up to 200 meters from the ego vehicle.

## Abstract
3D detection of traffic management objects, such as traffic lights and road signs, is vital for self-driving cars, particularly for address-to-address navigation where vehicles encounter numerous intersections with these static objects. We introduce a novel method for automatically generating accurate and temporally consistent 3D bounding box annotations for traffic lights and signs, effective up to a range of 200 meters. These annotations are suitable for training real-time models used in self-driving cars, which need a large amount of training data. The proposed method relies only on RGB images with 2D bounding boxes of traffic management objects, which can be automatically obtained using an off-the-shelf image-space detector neural network, along with GNSS/INS data, eliminating the need for LiDAR point cloud data.

### Download
The dataset is made freely available for non-commercial research purposes only. The full dataset (~107 GB) can be downloaded from this [link](https://aimotive-dataset.s3.amazonaws.com/aimotive_tl_ts_dataset.zip).

### Videos
https://github.com/user-attachments/assets/f636a985-f7c9-48a2-a7ec-193f693f86ec

https://github.com/user-attachments/assets/bad33f4b-809f-436d-966c-254e2428fe60

https://github.com/user-attachments/assets/011a83e1-113a-4c7b-bc7b-af8fa8aa8d43




### Updates
- [Aug 13, 2024] We released the 3D Traffic Light and Traffic Sign dataset.


### TODO
- Include file structure description
- Define coordinate systems
- Upload the dataset loader and visualizer




- Add citation
