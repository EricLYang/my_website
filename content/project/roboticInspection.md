+++
# Date this page was created.
date = "2017-01-01"

# Project title.
title = "RobotInspection"

# Project summary to display on homepage.
summary = "CCNY Robotics Lab proposes a robotic solution for infrasturcture inspection using UAV and wall climbing robot"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "WallClimb/IMG_0812.JPG"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deepInspection", "robotsInspection", "IGVC", "robotics", "design", "autonomous-robot"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "IROS2017/pipeline.jpg"
caption = "DeepInspect"

+++

We address the problem of using robotic approach to do infrastructure inspection. The unaccessable tunnel, bridge, and other concrete regions challengs the tradional labor intensive method. Illustration of CityFlyer and New Generation Rise-Rover

![This is an image](/img/WallClimb/IMG_0812.JPG)

First, CCNY Robotics Lab proposed a new generation of wall climbing robot, called Rise-Rover, to perform impact-echo (IE) acoustic inspection using a machine learning approach to do signal analysis. The wall climbing robot system structure is illustrated below:


![This is an image](/img/WallClimb/framework.jpg)

The design mimic the tentacles of an octopus, with dozens of negative pressure unit to provide seamless transition between ground and the wall.  
![This is an image](/img/WallClimb/wallclimbing.jpg)

We propose a machine learning approach to learn the patterns of the waveforms and spectra (especially the latter) that provide information about the existence and locations of flaws (cracks, voids, delamination, etc.) in concrete plates:

![This is an image](/img/WallClimb/svmDetection.JPG)

This is a site detection in Queens, NY.

![This is an image](/img/WallClimb/2017wallClibingDepth.bmp)

CityFlyer is able to be online SLAM and crack/spalling detection based on our new detect-network and segmentation network.





