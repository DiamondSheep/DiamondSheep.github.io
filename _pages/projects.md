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

## Introduction
  
  This is a personal project to build a two-wheeled robot. With a 2D Lidar, a RGBD camera and an [**NVIDIA Jetson Nano**](https://developer.nvidia.com/embedded/jetson-nano-developer-kit), this robot has some capabilities of **perception**, **positioning** and **navigation**. The code will be opened soon.

<center>
<img src="/images/two_wheeled_robot.jpg" width="80%" height="80%">
</center>

---

Jetson Robot
======

## Introduction

  This is the **previous version** of the above project. With a monocular camera (Pi Camera V2) and an NVIDIA Jetson Nano, this robot can perform some vision tasks, such as **detection**, **segmentation**. I built its hardware part with a [**L298N**](https://www.alldatasheet.com/datasheet-pdf/pdf/22440/STMICROELECTRONICS/L298N.html) as the motor driver and a [**PCA9685**](https://www.alldatasheet.com/datasheet-pdf/pdf/293576/NXP/PCA9685.html) as the servo controller. But I removed the motor controller code because it's unsafe to directly connect L298N to Jetson Nano. So now it becomes an experiment platform for DNN model deployment. [**Code**](https://github.com/DiamondSheep/Jetson_Project)

<center>
<img src="/images/Jetson_robot.png" width="70%" height="70%">
</center>

---

Pickup-Tennis Robot
======

## Introduction

  This is a project for the **National Undergraduate Training Program for Innovation and Entrepreneurship**. With a monocular camera (Pi camera V1), a [**Raspberry Pi 3B**](https://www.raspberrypi.com/products/raspberry-pi-3-model-b/) and a roller mechanism, the robot can detect, track and "pick up" the tennis. The project fail in half, since the Raspberry Pi processed the image quite slowly, and the latency damage much stability of the robot. (Maybe that is the reason that I study model compression and accelaration) Unfortunately, all of the code had been lost.

<center>
<img src="/images/tennis_robot.jpg" width="75%" height="75%">
</center>

---

FSEC 2017
======

  I participated in the [**Formula Student Electric China**](http://www.formulastudent.com.cn/c737) (FSEC) in 2017. As the leader of car-body group, I was responsible to the [**computing fluid design**](https://en.wikipedia.org/wiki/Computational_fluid_dynamics) of our racing car. Specifically, I designed and simulated the aerodynamic kits, including the diffusor, front and rear wings which can provided more stability for our racing car.

<center>
<img src="/images/fsae.jpg" width="75%" height="75%">
</center>