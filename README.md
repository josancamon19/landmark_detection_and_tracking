## Udacity Computer Vision Nanodegree
### Project Landmark detection and tracking

In this project, I implemented SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! I combined
what I learned about robot sensor measurements and movement to create a map of an environment from only sensor and 
motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time
and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active 
area of research in the fields of robotics and autonomous systems.


*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using 
*only* sensor and motion data collected by that robot. This is just one example for a 50x50 grid world. 

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

The project was broken up into four Python notebooks; the first two are for exploration of provided code,
and a review of SLAM architectures, **only Notebook 3 and the `robot_class.py` file contains the code built**:

__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking 

