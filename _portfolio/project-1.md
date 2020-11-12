---
title: "A Wearable System for Lower-limb Motion Monitoring"
excerpt: "<br/><img src='/images/project/project1.jpg'>"
permalink: /project/project1
collection: portfolio
---

In this project we present an approach to efficiently extract 3D human keypoints using a RGBD camera for static posture assessment and deploy the system in a portable computer without GPU.  
The approach firstly employs a lightweight model, which is an optimized version of OpenPose, 
for 2D human pose estimation and fuses the aligned depth data to the 2D keypoins to get 3D localization of human joints. 
CPU acceleration for inference is accomplished by Intel OpenVINO toolkit during this process. 
Then two typical postures in fitness called standing and overhead squat are assessed according to the given evaluation standards. 
Experiments show that this system can fulfill the tasks to extract 3D human postures and create assessment for static actions during fitness at 16 fps. 
For squat action this system is more robust than traditional depth-based skeleton tracking algorithms.
