<p align="right">  
   <img src = "images/vibot.png" width = 80>
</p >

<p align="center">  
   <img src = "images/ub.png" width = 400>
</p >

# <p align="center">Master of Computer vision and Robotics</p >   
<h3 align="center">Visual Servoing Project</h3> 

   
<h4 align="center"> 
Supervisors: Omar TAHRI
</h4> 

<p align="center">                       
Students: <br>  
 MUHAMMAD IZZUL<br> Pranavan Ramakrishnan<br> Cheng CHEN
</p>

## Contents
- [Introduction](#introduction)
- [Objectives&Tasks](#Objectives-and-Tasks)
- [Related techniques](#Related-techniques)
- [Implementation](#Implementation)
- [Conclusion](#Conclusion)
- [References](#References)


## Introduction




## Objectives and Tasks




## Related techniques




## Implementation
**Following line**
- To launch the map and bringup turtlebot
      
      roslaunch turtlebot3_gazebo turtlebot3_autorace.launch 
- To launch the calibration 
	   
      roslaunch t3_camera t3_intrinsic_camera_calibration.launch
      roslaunch t3_camera t3_extrinsic_camera_calibration.launch
- To launch the follow the line
	   
      roslaunch t3_follow_line t3_lane_detects.launch
	   roslaunch t3_follow_line t3_lane_controls.launch

__Demonstration__ of Following line:<br>
<p align="center">
<img src="video/t3_follow_line.gif"/></p> <br>
Please click this link to download the full <a href="video/t3_following_line_video.mp4">video</a>

      




## Conclusion




## References
