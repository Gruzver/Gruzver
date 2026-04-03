Hi, I'm Gr 👋
I'm a robotics engineering graduate student at [Universidad], Peru, working on autonomous navigation, robot perception, and multi-robot systems for search and rescue.
Currently part of a PROCIENCIA-funded SAR project building a heterogeneous robot team — quadruped, ground rover, and thermal UAV — for post-disaster victim detection in unstructured environments.

🔧 Tech Stack
Middleware & Frameworks
ROS2 Nav2 MoveIt 2 micro-ROS Ignition Gazebo Isaac Sim
Perception & AI
YOLOv8 OpenCV PyTorch SLAM Toolbox robot_localization (EKF) RealSense D435 RPLidar
Languages
Python C++
Hardware
ODrive Raspberry Pi Pico W DJI thermal cameras PS5 DualSense Pinocchio IK

🤖 Projects
🔴 Drone Tracker
Real-time person detection and GPS geolocation from thermal drone video
ROS2 pipeline that processes thermal drone footage to detect, track, and geolocate people in real time. Built for SAR and surveillance scenarios using DJI thermal cameras.

YOLOv8x fine-tuned on ~5,000 custom thermal frames
Multi-object tracking with persistent IDs + Kalman filter smoothing
Pixel-to-GPS conversion using drone telemetry (altitude, yaw/pitch/roll, FOV)
Live Leaflet.js dashboard with person markers, trajectories, and drone FOV overlay
DJI .SRT telemetry parsing · Single ros2 launch entry point

ROS2 YOLOv8 PyTorch OpenCV Kalman Filter DJI GPS Geolocation

🟠 Chaska Rover
Full-stack ROS2 platform for rover competitions (URC / ERC)
4-wheel swerve-drive chassis with a 6-DOF robotic arm, 3D LiDAR, depth cameras, and IMU. Three switchable drive modes (swerve, differential, Ackermann), velocity-based arm IK via Pinocchio, and full teleoperation through PS5 DualSense.
ROS2 Swerve Drive MoveIt 2 Pinocchio 3D LiDAR 6-DOF Arm URC/ERC

🟡 Amiibot
Autonomous differential-drive robot for social navigation research
4-wheel differential-drive platform with identical ROS2 interface in simulation (Ignition Gazebo) and on real hardware. Full Nav2 stack, EKF sensor fusion, dynamic obstacle avoidance with RealSense D435, and SLAM mapping.

AMCL localization · NavFn planner · DWB local controller
SLAM Toolbox for autonomous map generation
Point cloud → laserscan pipeline for 3D obstacle avoidance

ROS2 Nav2 SLAM Toolbox EKF RealSense D435 Ignition Gazebo ODrive

🟢 Kit Manipulador
4-DOF robotic arm with ROS2 + MoveIt 2 + micro-ROS
Educational robot arm workspace with Gazebo simulation, MoveIt 2 motion planning, and real hardware integration via micro-ROS on Raspberry Pi Pico W.
ROS2 MoveIt 2 micro-ROS Raspberry Pi Pico W Gazebo

🔬 Current Research
Multi-robot SAR system — PROCIENCIA E009-2026 · [Universidad], Peru
Heterogeneous team of quadruped + rover + thermal UAV for victim detection in post-disaster scenarios. My focus: ROS2 navigation stack, person detection from thermal imaging, and multi-platform simulation in Gazebo/Isaac Sim.

📫 Contact
[tu.email@universidad.edu.pe] · LinkedIn
