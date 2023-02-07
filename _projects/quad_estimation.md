---
title: Online Kinematics Calibration in Visual-Inertial-Leg Odometry

description: |
  A open source visual-inertial-leg odometry with high estiation accuracy

people:
  - zac
  - shuo

layout: project
image: "/img/vilo.gif"
last-updated: 2023-02-08
---

One important challenge for autonomous robots operating in GPS-denied environments is long-term state estimation.
The controller and the state estimator used on legged robots need accurate forward kinematics functions to calculate foothold locations and estimate robot velocity. Due to foot deformation, the actual forward kinematics often differ from the forward kinematics model. We propose a method to estimate forward kinematics parameters online within a visual-inertial-leg odometer whose state contains not only physical states like position and velocity, but also leg kinematics parameters such as actual contact points on the feet. The odometer integrates multi-modal information from visual sensor, inertial sensor, joint sensor and foot contact sensor in a factor graph manner. The factor graph defines a probabilistic inference problem whose solution contains the best estimation of the physical states, inertial sensor biases and forward kinematics parameters.
