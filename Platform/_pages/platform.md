---
title: "Platform"
permalink: /platform/
author_profile: true
use_math: true
header:
  overlay_image: /assets/images/fig2_IONIQ.png
  overlay_filter: 0.5
---


<br/>
<br/>
<br/>







# [1] Platform
<br/>
![ ](https://drive.google.com/uc?id=15rjHH2t_Ow3KjwqwojH0FWO51TL-2640)

**Hyndai, IONIQ 2015 electric model** is used for data acquisition.


<br/>
<br/>


# [2] Sensor Configuration 

![ ](https://drive.google.com/uc?id=1sgIqOITYiS6zySF-AHeml5SstADCLUNt)

Hardware sensor configuration of MSC-RAD4R dataset with top view. Sensor coordinates of each sensor are represented, where the coordinate frame is shown with red(x), green(y) and blue(z) axes. The colored triangles represent the field of view of each sensor, yellow for camera and red for 4D Radar.


<br/>
<br/>
<br/>
<br/>




# [3] Sensor Specifications


Sensors     | Specifications                                         | Hz  | Topic Name                              | Message Type              | N
---         | ---                                                    | --- |  ---                                    |  ---                      | ---
Camera      | FLIR, BFS-16S2C, HFoV, VFoV 60x45, resolutions 720x540 | 15  | /camera_array/(left, right)/image_raw   | /sensor_msgs/Image        | 2
LiDAR       | Ouster, OS1-128, VFoV 45, range 200m                   | 10  | /ouster/points                          | /sensor_msgs/PointCloud2  | 1
4D Radar    | Oculii, Eagle, HFoV, VFoV 113x45, long range 400m      | 15  | /oculii_radar/point_cloud               | /sensor_msgs/PointCloud2  | 1
IMU         | Xsens, MTi-630, roll(0.2), pitch(0.5), yaw(1)          | 200 | /imu/data                               | /sensor_msgs/Imu          | 1
RTK-GPS     | Synerex, MRP-2000, RTK accuracy +- 3cm                 | 10  | /fix, /vel                              | /sensor_msgs/NavSatFix, /geometry_msgs/TwistStamped | 1
GPS         | UBlox, ZED-F9P, Pos. accuaracy 1.0 - 1.5m              | 10  | /ublox_gps/fix, /ublox_gps/fix_velocity | /sensor_msgs/NavSatFix, /geometry_msgs/TwitWithCovarianceStamped | 1
Wheel Speed | Autonics, PR30-10DN, detection dis. 10mm               | 100 | /autoev(left, right)_wheel_rpm, /autoev(left, right)_wheel_vel | /std_msgs/Float32stamped, /std_msgs/Floar32stamped | 2


<br/>
<br/>
<br/>
<br/>


# [4] 4D Radar Data Format 
Originally x, y and z are measured in Oculii coordinate, but these values were changed to LiDAR coordinates for the convenience of the ROS visualizer.


name    | description | units
---     | ---         | --- 
x       | oculii_z    | [m]
y       | - oculii_x  | [m]
z       | - oculii_y  | [m]
beta    | elevation angle | [degree]
alpha   | azimuth angle   | [degree]
power   | signal-to-noise(SNR) | [dB]
doppler | doppler velocity in radial direction  | [m/s]
range   | distance of point    | [m]
recoveredSpeed | recovered(absolute) speed in radial direction | [m/s]
denoiseFlag | flag for moving objects or noise | 1 or 0
