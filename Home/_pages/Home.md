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

Recently, several 4D radar datasets have been published due to its high resolution and robustness in extreme weather conditions. However, most of the recent 4D radar dataset publications have insufficient odometry sensors, which is disadvantageous for 4D radar odometry research. To tackle this problem, this paper presents a 4D radar dataset with various odometry sensors based on a robot operating system (ROS) framework called MSC-RAD4R, which stands for Motivated for SLAM in City, ROS-based Automotive Dataset with 4D Radar. Our dataset at a glance includes 98,786 pairs of stereo images, 60,562 frames of LiDAR data, 90,864 frames of 4D radar data, 60,570 frames of RTK-GPS, 60,559 frames of GPS, 1,211,486 frames of IMU data and 6,057,276 wheel data covering approximately 51.6km and 100 minutes of automotive data in various environments including day, night, snow and smoke. In particular, our setup includes a high-resolution 79GHz Adaptive PDM FMCW Oculii 4D radar, which provides approximately 5,000-20,000 points per frame and operates at a long range of 400 meters with a frequency of 15Hz. It is expected that the proposed dataset will be useful for researchers working on 4D radar SLAM. The dataset is freely accessed via the following link: https://mscrad4r.github.io.
<br/>
<br/>
<br/>
<br/>




# [2] Data Sample (Urban D0)

<!--![](https://drive.google.com/uc?id=1pz9lH7BQAQttLVk7U3NNHJNcXIGde1BQ)-->
![ ](/assets/images_gitblog/URBAN_D0.png)

FLIR BFS-U3-16S2C Stereo cameras, Ouster OS-1 128ch LiDAR, Oculii Eagle 4D Radar, Xsens MTi630 AHRS IMU, Synerex MRP-2000 RTK-GPS, Ublox ZEDF9P GPS, Autonics PR30-10DN Wheel sensors data are provided.
Also, calibration information and data used for calibration are given in this dataset.
<br/>
<br/>
<br/>
<br/>





# [3] Collection Course (Urban, Daejeon)
<!--![](https://drive.google.com/uc?id=1LgPSM2OCXNDIW6d2gyCqaSVkfUp4WFi4)-->
![ ](/assets/images_gitblog/Daejeon.png)

Data collection courses overview for urban areas. Red and blue points mean the starting point and the ending point of the courses, respectively.
The data was obtained from areas with a discernible population (Yuseong-gu, Daejeon, South Korea, latitude : 36.392508, longitude : 127.398195).
<br/>
<br/>
<br/>
<br/>





# [4] Collection Couse (Rural, Daegwallyeong)
<!--![](https://drive.google.com/uc?id=1Jt0OKf4zaX9Zi865KD1ELaisZ5S5L5X3)-->
![ ](/assets/images_gitblog/Gangwondo.png)

Data collection courses overview for rural areas. The data was mostly obtained on roads or alleys that were not heavily populated. 
In addition, data on snowy environments was acquired (Daegwallyeong-myeon, Pyeongchang-gun, Gangwon-do, South Korea, latitude : 37.677758, longitude : 128.700295).
<br/>
<br/>
<br/>
<br/>




# [5] Collection Couse (Loop, Daejeon)
<!--![ ](https://drive.google.com/uc?id=1hrgsr18wcnNOQmUfs4DTNR_QiXSQcrAd)-->
![ ](/assets/images_gitblog/LOOP.PNG)

Data collection courses overview for loop areas. Red and blue points mean the starting point and the ending point of the courses, respectively.
The data was obtained from areas with a discernible population (Gwanpyeong-dong, Yuseong-gu,Daejeon, South Korea, latitude : 36.416685, longitude : 127.407457).

<br/>
<br/>
<br/>
<br/>




# [6] Collection Couse (Smoke, Daejeon)
<!--![ ](https://drive.google.com/uc?id=1uPhXfngsGP7rPj6mxK14PQ-93OlIBGAt)-->
![ ](/assets/images_gitblog/Course_SMOKE_A.PNG)

<br/>
<!--![ ](https://drive.google.com/uc?id=1WwlcfOe8BFbF3UOykYFMjbzEcJl8_CZM)-->
![ ](/assets/images_gitblog/Course_SMOKE_B.PNG)

Data collection courses overview for smoke areas. Red and blue points mean the starting point and the ending point of the courses, respectively.
The data was obtained from areas KAIST munji campus (Munji-dong, Yuseong-gu,Daejeon, South Korea, latitude : 36.392536, longitude : 127.397305).

<br/>
<br/>
<br/>
<br/>


# [7] Data Tree Example
<br/>
![ ](/assets/images_gitblog/Data_tree.png)

Please check above data tree example.


<br/>
<br/>
<br/>
<br/>
