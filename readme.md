###How to launch PBVS with mico simulation

Package Used:
* ROS Packages
    * [realsense2_camera](https://github.com/intel-ros/realsense)
    * [ros_opencl_caffe](https://github.com/intel/ros_opencl_caffe)
* PCL
* OpenCV 3.4.3
* Boost

---
#### Object Recognition
clCaffe uses 


---

#### Package Summary
This package combines object recognition, object tracking, point cloud processing and visual servoing to achieve visual servoing for objects without prior model.

object recognition --> obejct tracking --> point cloud extraction -> 


1. roslaunch arm_vs vs_ar_tag_tracking.launch
2. rosservice call /mico_interaction/switch_controllers "controllers_to_be_turned_on: 'velocity'