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
</center>


Jetson Robot
======

* Introduction

  This is the previous version of the above project. With a monocular camera (Pi Camera V2) and an NVIDIA Jetson Nano, this robot can perform some vision tasks, such as detection, segmentation. I built its hardware part with a L298N as motor driver and a PCA9685 as servo controller. But I removed the motor controller code because it's unsafe to directly connect L298N to Jetson Nano. So now it becomes an experiment platform for DNN model deployment. [Code](https://github.com/DiamondSheep/Jetson_Project)

<center>
<img src="/images/Jetson_robot.png" width="75%" height="75%">
</center>


Pickup-Tennis Robot
======

* Introduction

  This is a project for the National Undergraduate Training Program for Innovation and Entrepreneurship. With a monocular camera (Pi camera V1), a Raspberry Pi 3B and a roller mechanism, the robot can detect, track and "pick up" the tennis. The project fail in half, due to the Raspberry Pi processed the image quite slowly. Unfortunately, this robot was built in 2017 and all of the code was lost.

<center>
<img src="/images/tennis_robot.jpg" width="75%" height="75%">
</center>