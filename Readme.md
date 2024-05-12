# **Camera-based Localization of Unmanned Aerial Vehicles**

This project aims to develop a precise localization system for Unmanned Aerial Vehicles (UAVs) in scenarios where Global Navigation Satellite System (GNSS) signals are degraded or unavailable. The system integrates computer vision techniques, such as object detection, tracking, and Simultaneous Localization and Mapping (SLAM), with additional data sources like GPS and Digital Elevation Models (DEMs) to achieve accurate 6-DoF localization and navigation of UAVs.

## **Features**

- Object detection using **_YOLOv5_**
- Object tracking with **_DeepSORT_**
- Monocular SLAM implementation
- Bundle adjustment processes incorporating GPS and DEM data
- Simulated in a **_ROS-Gazebo_** environment

## **Installation**

1. Clone the repository:
git clone https://github.com/username/uav-camera-localization.git
2. Install the required dependencies (**_Python_**, **_MATLAB_**, **_ROS_**, **_Gazebo_**, etc.).

## **Usage**

1. Run the object detection and tracking module:
python object_tracking.py
2. Run the SLAM module with bundle adjustment:
monocular.m
3. Launch the Gazebo simulation:
roslaunch uav_sim gazebo.launch


## **Acknowledgments**

- [**_YOLOv5_**](https://github.com/ultralytics/yolov5)
- [**_DeepSORT_**](https://github.com/nwang57/dsort)
- [**_ORB-SLAM2_**](https://github.com/raulmur/ORB_SLAM2)
- [**_ROS_**](https://www.ros.org/)
- [**_Gazebo_**](http://gazebosim.org/)

## **References**

1. Hegazy, M., Abraham Boby, R., & Klimchik, A. (2024). Localization of a drone for landing using image-based visual servoing with image moments.
2. Larnaout, D., Gay-Bellile, V., Bourgeois, S., & Dhome, M. (2013). Vehicle 6-dof localization based on slam constrained by gps and digital elevation model information. In 2013 IEEE International Conference on Image Processing (pp. 2504-2508).
3. Ma, L., Zhao, S., An, B., & Meng, D. (2023). Visual localization with a monocular camera for unmanned aerial vehicle based on landmark detection and tracking using yolov5 and deepsort. International Journal of Advanced Robotic Systems.