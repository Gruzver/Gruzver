<div align="center">

# Gruzver Phocco

**Robotics & Perception Engineer**

*MSc Computer Science & Robotics · PUCP, Lima, Peru*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gruzverphocco/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:gruzver.phocco@pucp.edu.pe)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Gruzver)

</div>

---

## About

I'm a robotics engineer and master's student at PUCP (Pontificia Universidad Católica del Perú), working on autonomous navigation, robot perception, and multi-robot systems.

Currently part of a **PROCIENCIA-funded SAR project** — building a heterogeneous robot team (quadruped + ground rover + thermal UAV) for post-disaster victim detection in unstructured environments.

My focus: **ROS2 navigation stacks, thermal person detection, sim-to-real transfer, and multi-platform Gazebo/Isaac Sim simulation**.

---

## Tech Stack

**Middleware & Robotics**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=flat&logo=ros&logoColor=white)
![MoveIt2](https://img.shields.io/badge/MoveIt_2-22314E?style=flat&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-f58113?style=flat&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=flat&logo=nvidia&logoColor=white)
![micro-ROS](https://img.shields.io/badge/micro--ROS-22314E?style=flat&logo=ros&logoColor=white)

**Perception & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat&logoColor=white)

**Hardware & Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RealSense](https://img.shields.io/badge/Intel_RealSense-0071C5?style=flat&logo=intel&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

---

## Projects

### [Drone Tracker](https://github.com/Gruzver/drone-tracker) — Thermal SAR perception pipeline
> Real-time person detection and GPS geolocation from thermal drone video

ROS2 pipeline processing DJI thermal footage to detect, track, and geolocate people in real time. Built for search-and-rescue scenarios.

- YOLOv8x fine-tuned on ~5,000 custom thermal frames
- Multi-object tracking with persistent IDs + Kalman filter GPS smoothing
- Pixel-to-GPS conversion using drone telemetry (altitude, yaw/pitch/roll, FOV)
- Live Leaflet.js dashboard · DJI `.SRT` telemetry parser · Single `ros2 launch` entry point

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

### [Chaska Rover](https://github.com/Gruzver/chaska_rover) — Competition rover platform (URC / ERC)
> Full-stack ROS2 platform for university rover challenges

4-wheel swerve-drive chassis with a 6-DOF robotic arm, 3D LiDAR, depth cameras and IMU. Three switchable drive modes (swerve, differential, Ackermann), velocity-based arm IK via Pinocchio, PS5 DualSense teleoperation.

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![MoveIt2](https://img.shields.io/badge/MoveIt_2-22314E?style=flat&logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

---

### [Amiibot](https://github.com/Gruzver/amiibot_ws) — Social navigation research platform
> Autonomous differential-drive robot for human-aware navigation

Dual sim/real platform with identical ROS2 interface in Ignition Gazebo and on hardware (ODrive + RPLidar + RealSense D435). Full Nav2 stack, EKF sensor fusion, SLAM mapping, and dynamic obstacle avoidance.

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=flat&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-f58113?style=flat)
![SLAM](https://img.shields.io/badge/SLAM_Toolbox-555555?style=flat)

---

### [Kit Manipulador](https://github.com/Gruzver/kit_manipulador) — 4-DOF arm with micro-ROS
> ROS2 + MoveIt 2 + micro-ROS on Raspberry Pi Pico W

Robot arm workspace with Gazebo simulation, MoveIt 2 motion planning, and real hardware integration via micro-ROS.

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![MoveIt2](https://img.shields.io/badge/MoveIt_2-22314E?style=flat&logo=ros&logoColor=white)
![micro-ROS](https://img.shields.io/badge/micro--ROS-22314E?style=flat&logo=ros&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

---

## GitHub Stats

<div align="center">

[![Gruzver's GitHub stats](https://github-readme-stats.vercel.app/api?username=Gruzver&show_icons=true&theme=default&hide_border=true&count_private=true)](https://github-readme-stats.vercel.app/api?username=Gruzver&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Gruzver&layout=compact&theme=default&hide_border=true&langs_count=6)

</div>

---

## Current Research

**Multi-robot SAR system** · PROCIENCIA E009-2026 · PUCP, Lima, Peru

Heterogeneous team — quadruped, rover, and thermal UAV — for victim detection in post-disaster environments. Working on: ROS2 navigation stack, thermal person detection pipeline, multi-platform sim-to-real in Gazebo/Isaac Sim.

---

<div align="center">
<sub>Open to visiting research internships in robotics, perception, and autonomous systems · Oct 2026</sub>
</div>
