---
layout:     post
title:      "Estimating depth from images"
subtitle:   "ROS + Realsense Camera"
author:     "bythew3i"
header-img: "img/post/"
tags:
    - ROS
    - robot
    - Realsense Camera
    - Computer Vison
---

### Environment
- Ubuntu 18.04
- [ROS Melodic](http://wiki.ros.org/melodic/Installation/Ubuntu.)
- RealSense D435 camera

### Requirement
- [RealSense driver](https://github.com/IntelRealSense/librealsense/blob/master/doc/distribution_linux.md)
- [realsense2_camera ROS package](https://github.com/IntelRealSense/realsense-ros)


### Result

##### Input:
> My black Yale notes binder’s height is 29.7cm.

<img src="/img/post/20190925/V-4-1.png">
<img src="/img/post/20190925/V-4-2.png">
<img src="/img/post/20190925/V-4-3.png">

##### Output:
<img src="/img/post/20190925/V-4-4.png">
```
Top-left: (321, 161)
Bottom-right: (411, 275)
Estimated depth: 1.6076545619m
Estimated depth from depth image: 1.53564919162m Difference between estimates: -0.0720053702764
```