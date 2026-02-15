# Forward Kinematics Calculation for 3-Link Robotic Arm

![Kinematics Calculation](images/assembly.png)

## Overview
This project focuses on applying **Forward Kinematics equations** to a 3-link planar robotic arm.  
The goal is to calculate the position of the end effector (X, Y) using given link lengths and joint angles.

## Purpose
The objective of this work is to:
- Understand the mathematical formulation of forward kinematics.
- Apply trigonometric equations to robotic link systems.
- Calculate the final end-effector position step-by-step.
- Verify coordinate results manually.

This project was completed for learning and practice purposes in robotics and kinematics.

## Given Parameters
- L1 = 15 cm  
- L2 = 10 cm  
- L3 = 4 cm  
- θ1 = 30°  
- θ2 = 45°  
- θ3 = -90°

## Forward Kinematics Equations
The end-effector position is calculated using:

x = L1 cos(θ1)  
  + L2 cos(θ1 + θ2)  
  + L3 cos(θ1 + θ2 + θ3)

y = L1 sin(θ1)  
  + L2 sin(θ1 + θ2)  
  + L3 sin(θ1 + θ2 + θ3)

## 📊 Final Result
End Effector Position:

(32.24 , 23.61)

## 👤 Author
Kinematics calculation completed as part of robotics learning and training.
