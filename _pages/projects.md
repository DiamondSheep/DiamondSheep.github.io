---
layout: archive
title: ""
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

Two-wheeled Robot
======

* Introduction
  This is a personal project to build a two-wheeled robot. With a 2D Lidar, a RGBD camera and an NVIDIA Jetson Nano, this robot has some capabilities of perception, positioning and navigation. The code will be opened soon.

<center>
<img src="/images/two_wheeled_robot.jpg" width="75%" height="75%">


Two-wheeled Robot
======

* Introduction
  This is the previous version of the above project. With a monocular camera (Pi Camera V2) and an Jetson Nano, this robot can perform some vision tasks, such as detection, segmentation. I built its hardware part with a L298N as motor driver and a PCA9685 as servo controller. But I removed the motor controller code because it's unsafe to directly connect L298N to Jetson Nano. So now it becomes an experiment platform for DNN model deployment.

[Code](https://github.com/DiamondSheep/Jetson_Project)

<center>
<img src="/images/Jetson_robot.jpg" width="75%" height="75%">
