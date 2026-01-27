# Robotic GMAW / MIG Welding – Offline Programming with RoboDK

## Overview
I am currently assisting a group of senior design students with a project focused on developing and validating welding parameters for GMAW/MIG welding using an industrial robotic arm. Once the welding parameters are finalized, the team plans to use RoboDK for offline programming to effectively perform metal additive manufacturing using a welding process.

This offline programming portion of the project that I am contributing to.
- Offline programming using RoboDK  
- Translating toolpaths into robot-readable motion commands  
- Troubleshooting motion planning and coordinate systems  
- Supporting simulation-to-hardware transition  


## Current Status
The team has successfully:
- Developed initial welding parameters  
- Created RoboDK simulations of the robotic arm and workcell  

The main challenge we are currently facing is **converting G-code toolpaths into motion commands that RoboDK and the robot controller can properly interpret**. While the simulations run correctly, translating these paths into Cartesian motion that the robot can execute remains an ongoing issue.

---

## Technical Challenge
The primary difficulty lies in:
- Converting G-code into Cartesian or joint-space instructions compatible with the robot
- Ensuring correct frame alignment and tool orientation
- Maintaining smooth, continuous motion suitable for welding applications  

This step is critical for enabling reliable robotic welding-based additive manufacturing.

---

## Workcell Simulation
![RoboDK Simulation](RoboDk.jpeg)

---

## Robotic Platform
![Yaskawa Robotic Arm](robotic_arm.jpeg)

---

## Ongoing Work
This project is actively in progress. I will continue to add updates as solutions are developed and progress is made toward successfully generating executable robot motion from offline toolpaths.

---

## Skills & Concepts Applied
- Offline robot programming  
- RoboDK simulation environment  
- Industrial robot kinematics  
- Coordinate frames and toolpaths  
- Robotics–manufacturing integration  
