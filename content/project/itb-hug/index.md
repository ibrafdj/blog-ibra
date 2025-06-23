---
author: Ibrahim Fadhil Djauhari
title: "Hybrid Underwater Glider (HUG)"
description: "Developed the navigation, guidance, and control systems of an AUV with two modes of movement"
# date: "2020-08-12"
# tags: 
#   - "english"
# language: "english"
thumbnail: "/project/itb-hug.jpg"
hideMeta: true
---

A HUG can switch between moving in a low-power glide mode and a high-precision propulsion mode. This hybrid movement allows it to maximize its survey duration by first travelling to the survey site in glide mode, then switch to propulsion mode while surveying the site.

The ITB-HUG is being developed in *Institut Teknologi Bandung* (ITB) by the Computer & Control Systems research group. In 2019, my team and I joined this project to work on my final undergraduate capstone design project titled "Integration of Navigation, Guidance, and Control of Hybrid Underwater Glider".

Our work focused on the design, implementation, and integration of the navigation, guidance, and control systems for the ITB-HUG, a type of Autonomous Underwater Vehicle (AUV) capable of both gliding and propulsion-based movement. The primary goal was to enable the HUG to conduct autonomous underwater missions, such as bathymetry (underwater mapping), by accurately following a predetermined path. The entire system was developed within the Robot Operating System (ROS) framework, which facilitated modular design and communication between the different software components. We verified the performance of our integrated system through Hardware-in-the-Loop Simulations (HILS), where the control and navigation software ran on the HUG's actual embedded computers while the vehicle's dynamics and the underwater environment were simulated.

The navigation system's core function is to provide precise real-time estimations of the vehicle's position, orientation, and velocity. To achieve this, we implemented a closed-loop error-state Extended Kalman Filter (EKF). This system fuses data from a primary Inertial Measurement Unit (IMU) with measurements from several supporting sensors, including a Doppler Velocity Log (DVL), a Global Positioning System (GPS) for when the vehicle is surfaced, and a depth sensor. This multi-sensor fusion is critical for correcting the inherent drift of the IMU, ensuring the navigation solution is accurate enough to meet the International Hydrographic Organization's (IHO) standards for hydrographic surveys.

The guidance and control systems work in tandem to steer the HUG along its mission path. The guidance system uses a Line-of-Sight (LOS) algorithm to generate a path between waypoints and calculates the necessary surge speed, pitch, and yaw angles to follow it. These commands are then sent to the hierarchical control system, which translates them into specific actions for the HUG's actuators, such as the main thruster, buoyancy engine, moving mass, and control surfaces (rudder and elevator). The system was successfully tested in challenging scenarios, including a 1000-meter long gliding mission and a complex 50×50 m^2 lawnmower pattern, demonstrating its effectiveness for bathymetry missions with a maximum cross-track error of 6.269 m in the XY plane and 0.072 m in the XZ plane.

After graduating in 2020, I continued working in the ITB-HUG project for three years. I co-invented two patents registered in Indonesia based on our work on the ITB-HUG's navigation, guidance, and control systems.

<!-- [^1]: Heick, T. (2020, June 19). _The Definition of Synchronous Learning_. Retrieved August 5, 2020, from Teach Thought: https://www.teachthought.com/technology/the-definition-of-synchronous-learning/ -->
