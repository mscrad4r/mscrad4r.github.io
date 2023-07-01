---
title: "Dataset"
permalink: /dataset/
author_profile: false
use_math: true
header:
  overlay_image: /assets/images/rvizdemo2.png
  overlay_filter: 0.5
sidebar:
  nav: sidebar-track
---

<br/>
<br/>
<br/>





# [1] Data Acquisition Scenario

The unmanned platform acquired data along tracks A and B, which are described in below figures. The detailed data acquisition scenario is described as follows. The unmanned platform drove at a constant speed of 5 km/h from start to finish and was controlled by a wireless controller. Since an unmanned platform has a smaller chassis and weaker suspension than a real vehicle, it is more sensitive to abrupt changes in roll, pitch, and yaw directions that occur due to speed bumpers or U-turn sections. In addition, the unmanned vehicle maintained an appropriate distance to surrounding objects to avoid blocking the implemented sensors by the objects.


An observation vehicle was introduced as a control center for operating an unmanned platform. The observation vehicle followed the unmanned platform at a sufficient distance, 5 m back, to avoid affecting data acquisition and drove at the same speed as the unmanned platform. In addition, the observation vehicle controlled the overtaking vehicle so that it did not block the sensor's field of view when it returned to the lane in which the unmanned platform was driving. The person who operated the wireless controller for the unmanned vehicle sat in the passenger seat of the observation vehicle to minimize the continuously detected objects in the data.



<br/>
<br/>

# [2] Track A & B

<img src="/assets/images/Track_a__.png" width="100%" height="100%" title="CAD design of a ROS-based small unmanned platform" alt="1"/> 


* __Track A__ 

Noticeable spots located in the tracks are listed in above figure and the corresponding characteristics of each spots are as follows. Track A consists of 4 sections, $$ l_i^A (i=1 \sim 4)$$, which are mainly straight lanes. Additionally, there is no curved road with a significant change in direction, and at the last point, a U-turn is made at the end of section $$l_4^A$$ and returns to the opposite lane of the same road. Track A is mainly composed of moving vehicles, and the pedestrian road is clearly separated from the vehicle road.



* __Track B__ 

Track B consists of 4 sections, $$l_i^B \; (i=1\sim4)$$, and pedestrian roads consist primarily of the sections. In $$l_1^B$$ and $$l_3^B$$, pedestrians walking along buildings and trees were recorded in the data without any vehicles. Parked vehicles were captured in $$l_4^B$$, and pedestrians crossing the crosswalk with waiting vehicles were also included in both $$l_4^B$$ and $$l_2^B$$.



<br/>
<br/>


# [Appendix] Track C & D
<img src="/assets/images/Track_b__.png" width="100%" height="100%" title="CAD design of a ROS-based small unmanned platform" alt="1"/> 








