+++
# Date this page was created.
date = "2017-01-01"

# Project title.
title = "DeepInspect"

# Project summary to display on homepage.
summary = "From end of 2016, I was supported by US Dept. of Transportation of the project: Tier I University Transportation Center: Inspecting and Preserving Infrastructure through Robotic Exploration (INSPIRE Center). We proposed a new approach using Unmanned Aerial Vehicle(UAV) towards a Concrete Structure Spalling and Crack database (CSSC), we also fined tuned the vgg 16 with a detection baseline for spalling/crack detection."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "IROS2017/systemFramework.jpg"

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
The inspection system consists of three subsystems, including: 1) Control and Mission system (CMS): a quadrotor UAV with mission planner and navigation control system. It fuses visual odometry with inertial measurement unit (IMU) data, called visual inertial odometry (VIO) with an output frequency of 100 HZ, for robust positioning control. 2) Deep-Inspector: Towards a CSSC database system with very deep CNN for spalling and crack detection and labelling. It is performed on the ground station via wireless data transition at 2 HZ. 3) visualpositioning and mapping (P&M): loop closing is introduced to reduce drift of visual odometry (VO) to guarantee accurate positioning and 3D point cloud mapping with defect area registration for visualization. Hardware of CMS is consist of CityFlyer and a laptop based ground system. Since the paper mainly discuss the deep database system and 3D positioning with defect registration.

![This is an image](/img/IROS2017/pipeline.jpg)

The detection network is fine tuned based on vgg16 with pre-trained model:

![This is an image](/img/IROS2017/section3.jpg)

We did several tests with CSSC dataset and field test with CityFlyer:
![This is an image](/img/IROS2017/IMG_0812.JPG)

![This is an image](/img/IROS2017/fieldTestResults_Page_1.jpg)

![This is an image](/img/IROS2017/fieldTestResults_Page_2.jpg)

Now, we move forward with a higher labeled dataset with pixel level accuracy of target spalling/crack region for segmentation, we looking forward to collaborate. If interested, please email: chiyangliang At gmail Dot com

{{% staticref "img/IROS2017/IROS2017.pdf" %}}Download our IROS 2017 and ROBIO 2017 Paper{{% /staticref %}}


