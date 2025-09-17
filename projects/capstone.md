---
layout: project
type: project
image: img/swerveProjectHome.jpg
title: "High School Capstone"
date: 2022
published: true
labels:
  - Robotics
  - C
  - Holonomic Drive
  - Vex
summary: "Culminating capstone project that involves ground up development of a holonomic drive system."
---

<img class="img-fluid" src="../img/swerveWheelMod.JPG">

The capstone project serves as a year long project that aims to utilizes ones knowledge obtained over the course of high school to a singular project. It consisted of three different branches, engineering, health, and business. In particular, I was part of the engineering discipline and decided to team up with a fellow engineering student to create a holonomic drive system. However, this project was inhibited by the lack of funding and mentorship provided to us when designing the mechanical aspects of it. Resulting in the use of old VEX Robotics parts which had a very locked down architecture and archaic libraries. 

The holonomic drive describes an omnidirectional robotic drive that allows each individual wheel to move and rotate simultaneously in any direction. This is done by having a motor for rotation and an another for backward and forward motion. My partner was responsible for designing the mechanical aspect of the drive, but I was able to give input as needed. I was mainly responisble for programming the software that was flashed onto the brain of the vex controller. I specifically remember with struggling with using C as it had no object oriented functionality, which made it had to make specific abstractions. On top of that I had a particularly hard time finding a way to implement optimized angles. For example, if you can imagine an unit circle at 45 degrees, when you want to go to 0 or 360 degrees instintively you would want move to the right. However, you can also move left which is much slower, so I had to implement a way to calculate which way would be optimal for the wheel to move. My partner and I have worked on my interation of the project and one of those final prototypes are shown above. If you noticed one of the motors go straight through the 3D printed gear and moves just the wheel forward and backwards. The other motor is used to rotation as I have mention.

This capstone project became one of those projects that pushed me to pursue this type of engineering discipline. I enjoy being able to work with the electronics, but also being able to create software on top of that. The intersection between physical and purely digital motivated me to work on something like this. And if you are able to find that niche, that intersection in life you will truly find what makes you tick.
