---
title: "Home"
permalink: /home/
author_profile: true
use_math: true
header:
  overlay_image: /assets/images/URBAN_D0.png
  overlay_filter: 0.5
---


<br/>
<br/>
<br/>


# Welcome to MSC RAD4R dataset!  :)
<br/>
<br/>
<br/>


# [1] Motivation

Simultaneous Localization And Mapping(SLAM) technology is essential for global localization and route planning of autonomous driving. 
Since most of existing SLAM techniques are limited in dynamic environments such as city or complex urban, many studies are being conducted to address this issue.
The 4D Radar, which has been in the spotlight recently, is a very good sensor in perspective of SLAM because it can easily classify static objects from measured Doppler velocity. 
It also has the advantage of high resolution and robustness in extreme weather conditions. 
Therefore, academia and many companies have recently been conducting research based on 4D Radar dataset. 
However, most of the recently opened 4D Radar dataset publications focus on 3D object detection. 
Therefore, odometry sensors are often insufficient, which is disadvantageous for 4D Radar odometry and SLAM research. 
From this point of view, this paper proposed a 4D Radar dataset containing various odometry sensors based on ROS framework, which is widely used by robotics engineers. 
In addition, the newly proposed LiDAR-camera calibration method applicable to low resolution LiDAR and Radar-camera calibration were performed. 
Finally, 4D Radar odometry’s feasibility under dynamic environments such as metropolitan areas is shown in this work. 
The dataset can be freely accessed via the following link : https://iphone7743.github.io/mscrad4r.
<br/>
<br/>
<br/>
<br/>




# [2] Data Sample (Urban D0)

![](https://drive.google.com/uc?id=1pz9lH7BQAQttLVk7U3NNHJNcXIGde1BQ)


FLIR BFS-U3-16S2C Stereo cameras, Ouster OS-1 128ch LiDAR, Oculii Eagle 4D Radar, Xsens MTi630 AHRS IMU, Synerex MRP-2000 RTK-GPS, Ublox ZEDF9P GPS, Autonics PR30-10DN Wheel sensors data are provided.
Also, calibration information and data used for calibration are given in this dataset.
<br/>
<br/>
<br/>
<br/>





# [3] Collection Course (Urban, Daejeon)
![](https://drive.google.com/uc?id=1LgPSM2OCXNDIW6d2gyCqaSVkfUp4WFi4)

ata collection courses overview for urban areas. Red and blue points mean the starting point and the ending point of the courses, respectively.
The data was obtained from areas with a discernible population (Yuseong-gu, Daejeon, South Korea, latitude : 36.392508, longitude : 127.398195).
<br/>
<br/>
<br/>
<br/>





# [4] Collection Couse (Rural, Daegwallyeong)
![](https://drive.google.com/uc?id=1Jt0OKf4zaX9Zi865KD1ELaisZ5S5L5X3)

ata collection courses overview for rural areas. The data was mostly obtained on roads or alleys that were not heavily populated. 
In addition, data on snowy environments was acquired (Daegwallyeong-myeon, Pyeongchang-gun, Gangwon-do, South Korea, latitude : 37.677758, longitude : 128.700295).
<br/>
<br/>
<br/>
<br/>
