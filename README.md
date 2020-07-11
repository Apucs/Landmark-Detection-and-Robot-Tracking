# Landmark Detection & Robot Tracking (SLAM)

## Project Overview

In this project, I have implemented SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! I have combined the knowledge of robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems. 

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.*

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking 


## Project Instructions

1. Clone the repository
```
https://github.com/Apucs/Landmark-Detection-and-Robot-Tracking.git
```

2. __Requirements for this project___
```
pip install -r requirements.txt
```

## __Inference__
> Initial __Omega__ matrix
<p align="center">
  <img src="./images/omega.png" width=50% height=50% />
</p>

> Initial __Xi__ matrix
<p align="center">
  <img src="./images/xi.png" width=20% height=10% />
</p>

> __Robot world__
<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>


LICENSE: This project is licensed under the terms of the MIT license.
