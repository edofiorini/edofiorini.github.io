---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a full PDF version of my CV [here](/files/Edoardo_Fiorini_CV.pdf).

Education
======
* M.S. in Computer Engineering for Robotics and Smart Industry, University of Verona, Italy, 2020 - 2022 (110/110 cum laude)
  * Thesis: *A robust motion planning algorithm for Welding Robots based on Optical Tracked Learning by Demonstration and CAD model*
  * Supervisor: Prof. Riccardo Muradore
* B.S. in Bioinformatics, University of Verona, Italy, 2017 - 2020 (107/110)
  * Thesis: *Robotics Interface for a BCI System*
  * Supervisor: Dr. Francesco Setti

Work experience
======
* **May 2024 - Present: Research Scientist, Interactive Skill Learning (ISL) Group**
  * DLR (German Aerospace Center), Institute of Robotics and Mechatronics, Cognitive Robotics (KRO) Department, Future Manufacturing domain
  * Conducting research on injecting human priors into learning models for interactive learning of generated robotic skills, bridging machine learning and control in robotics
  * Developing methods to detect human-robot physical interaction and provide feedback using uncertainty-aware energy tanks
  * Designing user-friendly interfaces for trajectory segmentation and task-relevant prior specification
  * Working on Reinforcement Learning from Imitation Learning with human-in-the-loop feedback
  * Applying diffusion policies and Vision-Language-Action (VLA) models with human-in-the-loop input for continuous skill adaptation
  * Involved in the EU project INVERSE, applying human-robot collaboration research to intuitive skill inversion, validated on real use cases from Kone Cranes and Centro Ricerche Fiat (CRF)
  * Showcased solutions at international fairs (e.g. Automatica) on real robots, for tasks such as cable insertion and bearing ring insertion

* **May 2023 - May 2024: Robotics Researcher, ALTAIR Robotics Lab**
  * University of Verona, Italy
  * Developed an autonomous rover with a manipulator mounted on top for precision agriculture
  * Implemented navigation and control using ROS/ROS2, SLAM, and the ROS2 Navigation stack, with GPS-based positioning for outdoor navigation
  * Worked with a UR5 robotic manipulator for weed removal and fruit-picking tasks
  * Built perception pipelines with Intel RealSense and ZED stereo cameras and YOLOv6 for real-time object detection, complemented by a custom-built in-house multispectral camera
  * Developed front-end visualization tools in JavaScript and Vue.js
  * Validated the platform in simulation (CoppeliaSim, Gazebo) and real field navigation tests

* **August 2022 - February 2023: Master's Thesis, ALTAIR Robotics Lab**
  * University of Verona, Italy
  * Implemented and validated a robust motion planning workflow for a welding robot based on the Learning by Demonstration paradigm, using a hand-tool pointer tracked by an optical system and the welding workpiece CAD model
  * Built and validated an experimental collaborative welding cell integrating a Franka Emika Panda manipulator with an OptiTrack motion capture system, developing the full software stack in C++ and ROS
  * Research published at CASE 2024 (IEEE International Conference on Automation Science and Engineering)

* **April 2022 - June 2022: Internship, DLR Institute of Robotics and Mechatronics**
  * Oberpfaffenhofen, Munich, Germany
  * Participated in the Factory of the Future (FoF) development team, building a flexible production network demonstrated live at the Automatica trade fair
  * Researched and implemented motion planning methods for a KUKA LWR manipulator mounted on a linear axis, applied to multiple robotic skills such as box handling and motor insertion
  * Integrated motion planning into the robotic system and conducted experimental evaluation in Python

* **2020 - 2023: Graduate Teaching Assistant**
  * University of Verona, Italy
  * Programming I (Computer Science) and Programming Languages and Tools with Laboratory (Human Centered Medical System Engineering)
  * Reviewed theoretical concepts, prepared exercises and code, held office hours, invigilated exams

Skills
======
* Programming Languages: Python, C/C++, MATLAB/Simulink, Java, HTML, LaTeX, SQL
* Robotics Frameworks: ROS, ROS2, MoveIt
* Robotic Platforms: Franka Emika Panda, KUKA iiwa/LWR, Universal Robot UR5/UR5e, Robotnik RB-Kairos mobile robot
* Perception & Sensing: Intel RealSense, ZED stereo cameras, custom multispectral cameras, OptiTrack motion capture, LiDAR, GPS, 3D scanning (Gocator)
* Machine Learning & Control: Reinforcement Learning, Imitation Learning, Learning by Demonstration, diffusion policies, Vision-Language-Action (VLA) models, SLAM, motion planning, anomaly detection
* Simulation: Gazebo, CoppeliaSim, URSim
* Web/Front-end: JavaScript, Vue.js
* Operating Systems: Linux, Windows, macOS

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Languages
======
* Italian: Native speaker
* English: Fluent (TOEIC B2 Certification)
