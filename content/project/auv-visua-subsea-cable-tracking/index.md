---
author: Ibrahim Fadhil Djauhari
title: "AUV Visual Subsea Cable Tracking"
description: "Developed real-time system for detecting, following, and searching subsea cables using an AUV"
# date: "2020-08-12"
# tags: 
#   - "english"
# language: "english"
thumbnail: "/project/auv-visual-subsea-cable-tracking.jpg"
hideMeta: true
---

This research project is done with the [Ocean Perception Lab](https://www.oceanperception.com) at the University of Southampton.

Our research focuses on developing a comprehensive, real-time system for an Autonomous Underwater Vehicle (AUV) to efficiently search for, detect, and follow subsea communication cables. Given that these cables form the backbone of global data transmission and are vulnerable to damage, our goal is to create a robust inspection method that can handle the significant challenges of the deep-sea environment, such as high uncertainty in cable location, the featureless nature of the cables, and instances where the cable is buried or obscured. Our integrated system allows an AUV to not only track a visible cable using visual data but also to intelligently search for and relocate the cable after losing contact, making long-distance autonomous inspection missions feasible.

The system combines two key innovations. The first is a real-time visual detection and following algorithm that processes images from an onboard camera. We utilize advanced machine learning classifiers, specifically GeoCLR, which has proven effective at identifying the cable in seafloor imagery with a low rate of false positives—a crucial factor for stable tracking. When the cable is detected, the algorithm computes its position and orientation to generate immediate navigational waypoints for the AUV to follow it closely. The second component is a novel search and path estimation method for when the cable is not visible, due to being buried or outside the camera's view. This system employs a graph-based Simultaneous Localisation and Mapping (SLAM) approach, which continually updates a map of the cable's route and its uncertainty based on successful observations. This updated map then guides a systematic zig-zag search pattern, significantly improving the AUV's ability to relocate the cable efficiently.

To address the challenge of matching sensor observations to the featureless cable, we introduced a cable-relative coordinate frame that allows for reliable data association within the SLAM framework. We have rigorously tested our system through simulations using real-world cable routes from surveys off the coast of Oregon and Plymouth. These simulations, incorporating the dynamics of the Sparus II and AE2000F AUVs, have demonstrated that our method can consistently observe over 66% of a cable's remaining length even with numerous buried sections and significant initial route uncertainty. Future work will involve sea trials with the University of Southampton's Smarty200 AUV to validate these findings in a real-world operational environment.

This project results in two academic[^1] publications[^2].

[^1]: A. Bodenmann, I. F. Djauhari, J. Devgon and B. Thornton, "Real-time Subsea Communication Cable Detection for AUV-based Inspection," 2024 IEEE/OES Autonomous Underwater Vehicles Symposium (AUV), Boston, MA, USA, 2024, pp. 1-6, doi: 10.1109/AUV61864.2024.11030782.

[^2]: I. F. Djauhari, A. Bodenmann, S. Simmons and B. Thornton, "Subsea Cable Search and Path Estimation Using Graph SLAM for AUV-Based Inspection," 2025 IEEE Underwater Technology (UT), Taipei, Taiwan, 2025, pp. 1-6, doi: 10.1109/UT61067.2025.10947380.