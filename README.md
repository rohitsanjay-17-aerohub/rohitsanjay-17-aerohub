<div align="center">

<!-- Banner placeholder: add <img src="assets/banner.png" width="100%" /> here once your Figma banner is exported and committed to the repo -->

# Rohit Sanjay Ganesh
### Aerospace & Robotics Engineer · GNC · Autonomous Systems · UAV Flight Systems

![C++](https://img.shields.io/badge/C%2B%2B-1B263B?style=flat-square&logo=cplusplus&logoColor=00B4D8)
![Python](https://img.shields.io/badge/Python-1B263B?style=flat-square&logo=python&logoColor=FFD43B)
![ROS2](https://img.shields.io/badge/ROS2-00B4D8?style=flat-square&logo=ros&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-0077B6?style=flat-square)
![MATLAB/Simulink](https://img.shields.io/badge/MATLAB%2FSimulink-FF6B35?style=flat-square)
![Gazebo](https://img.shields.io/badge/Gazebo-415A77?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-1B263B?style=flat-square&logo=opencv&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-FF6B35?style=flat-square)
![Git](https://img.shields.io/badge/Git-1B263B?style=flat-square&logo=git&logoColor=F05032)
![Linux](https://img.shields.io/badge/Linux-415A77?style=flat-square&logo=linux&logoColor=FCC624)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rohit--sanjay--g17-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/rohit-sanjay-g17/)
[![GitHub](https://img.shields.io/badge/GitHub-rohitsanjay--17--aerohub-181717?style=flat&logo=github)](https://github.com/rohitsanjay-17-aerohub)
[![Email](https://img.shields.io/badge/Email-rganes13@asu.edu-D14836?style=flat&logo=gmail)](mailto:rganes13@asu.edu)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Work%20(OPT)-brightgreen?style=flat)](mailto:rganes13@asu.edu)
![Profile views](https://komarev.com/ghpvc/?username=rohitsanjay-17-aerohub&color=0A66C2&style=flat)

</div>

---

## 👋 About Me

M.S. Aerospace Engineering Graduate from **Arizona State University** (GPA: 3.87/4.0, graduated Dec 2025), specializing in **GNC, autonomous UAV systems, and robotics software**. I bridge classical control theory with embedded C++/Python/ROS2 stacks, from Simulink models to flight-ready physical hardware.

🔭 Currently working on multi-UAV safe control at ASU's Safe Robotics Lab
🎯 Targeting roles in: **Robotics Software Engineer · Forward Deployed Engineer · GNC Engineer · UAV Autonomy**
🌍 Authorized to work in the U.S. (OPT, no sponsorship required)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rohitsanjay-17-aerohub&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rohitsanjay-17-aerohub&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165" />

<img src="https://streak-stats.demolab.com/?user=rohitsanjay-17-aerohub&theme=tokyonight&hide_border=true" alt="GitHub streak" width="60%" />

</div>

---

## 🛠️ Technical Stack

**Languages & Tools**
`C++` `Python` `MATLAB/Simulink` `Bash` `CMake` `Git` `Linux (Ubuntu/Debian)`

**GNC & Autonomy**
`ROS1` `ROS2` `PX4` `MAVROS` `SLAM (Cartographer)` `AMCL` `NavFn/DWA` `Behavior Trees` `Motion Planning` `TF Frames`

**Controls & Estimation**
`PID` `LQR/LQG` `Linear MPC` `EKF/UKF` `Kalman Filter` `Madgwick Filter` `Sensor Fusion` `System ID`

**Perception**
`RGBD Cameras` `YOLOv5` `OpenCV`

**Simulation & Hardware**
`Gazebo (SITL/HITL)` `RViz` `Jetson Nano` `LiDAR/IMU/Camera` `FPV Drone Assembly` `Log-Based Debugging`

---

## 🚀 Featured Projects

### Multi-UAV Safe Control — GCBF+ on Crazyflie (Safe Robotics Lab, ASU)
> *ROS2 · Crazyflie · Graph Neural Networks · Safe Multi-Agent Control · Repo coming soon*

Deployed a ROS2 node on **3 physical Crazyflie 2.1 nano-UAVs** with Lighthouse-based positioning, integrating the Neural Graph Control Barrier Function (GCBF+) framework for decentralized, collision-free multi-agent control. Real-time GNN inference enabled dynamic obstacle avoidance and safe position swapping, validated through staged flight tests on physical hardware.

---

### [Bumperbot — ROS2 Robotics Software Stack (Course Project)](https://github.com/rohitsanjay-17-aerohub/bumperbot_ws)
> *ROS2 · Odometry & Control · SLAM & Localization · Behavior Trees · Motion Planning*

Built a complete ROS2 robotics stack across three phases: odometry and low-level control, mapping and localization, and planning and navigation. Implemented wheel odometry with sensor fusion and Kalman filtering for state estimation, SLAM-based mapping and localization, and behavior-tree-driven planners and executors for autonomous navigation and obstacle avoidance.

[Watch the Nav2 demo](https://drive.google.com/file/d/1vR_AhagI9RF4NhfAt_DB1W1sXTq92bfy/view?usp=sharing)

> Note: this repo excludes the AWS RoboMaker residential and warehouse Gazebo world assets (that pack has since been archived by AWS). Equivalent world files are available from [Automatic Addison's Gazebo/ROS2 world file collection](https://automaticaddison.com/useful-world-files-for-gazebo-and-ros-2-simulations/).

---

### [6-DOF Aircraft Dynamics, Trim & Stability Analysis](https://github.com/rohitsanjay-17-aerohub/6DOF-Aircraft-Simulation)
> *MATLAB/Simulink · System Identification · Eigenvalue Analysis · MPC*

Built a full nonlinear rigid-body 6-DOF aircraft model in Simulink with aerodynamic forces, stability derivatives, and propulsion. Performed trim analysis, state-space linearization, and extracted short-period, phugoid, Dutch roll, and spiral modes. Used `fmincon` to refine lateral-directional stability via system ID against real flight logs.

---

### [ROSMASTER X3 — Autonomous Navigation with Dynamic Object Detection & Avoidance (ROS1, Team Lead)](https://github.com/rohitsanjay-17-aerohub/rosmaster_x3_multiwaypoint_nav)
> *ROS1 · Cartographer SLAM · AMCL · move_base · YOLOv5 · Team of 6*

Led a 6-person team in ASU's EGR 530 (Principles of Systems Engineering) building a full ROS1 autonomy stack on the [ROSMASTER X3](https://www.yahboom.net/study/ROSMASTER-X3) (Jetson Nano, 2D LiDAR, RGBD depth camera, IMU, mecanum-wheel drive). Integrated three subsystems: Cartographer-based SLAM mapping with AMCL localization and a tuned move_base stack (Navfn/Dijkstra global planner, DWA local planner) for multi-waypoint navigation; HSV-based line following with a smart-recovery behavior that rotates in place to reacquire a lost line instead of stalling; and an 11-class YOLOv5s traffic sign detector trained on a self-generated synthetic dataset, running live onboard for real-time recognition.

[Watch the full demo](https://docs.google.com/file/d/1i9JFSkMMwrphAcVNhFx-NmGoc0Qa8LJ-/preview) · [Presentation slides (PDF)](https://github.com/rohitsanjay-17-aerohub/rosmaster_x3_multiwaypoint_nav/blob/main/docs/presentation.pdf)

---

### Scaled VTOL UAV — F-35 Inspired (Flight Controls Lead)
> *C++ · dRehmFlight · PID Tuning · Python Log Analysis · Repo coming soon*

Modified and deployed an open-source C++ autopilot on a custom VTOL platform with mode-dependent actuator mixing and hover-to-forward transition logic. Used Madgwick-filtered IMU for state feedback; iteratively tuned PID gains via Python post-flight analysis, achieving <3° steady-state roll error.

---

### Linear MPC — Constrained Trajectory Control
> *Python · Model Predictive Control · Trajectory Optimization · Repo coming soon*

Implemented a linear MPC controller for trajectory tracking under actuator constraints. Benchmarked against PID across varying prediction horizons and cost weight matrices to evaluate stability, tracking accuracy, and control effort trade-offs.

---

## 💼 Experience Highlights

| Role | Organization | Period |
|---|---|---|
| Deputy Project Manager (Resources) | NASA L'SPACE / Team AVATAR | Sep 2024 – Apr 2025 |
| UAV Hardware (FPV) Technician | Chennai Drone Academy | Oct – Dec 2023 |
| Flight Test Engineering Intern | IIT Kanpur | Aug 2022 |

- **NASA L'SPACE**: Led mission-wide budgeting under a $200M cost cap using the NASA Instrument Cost Model (NICM); guided team through MCR, SRR, MDR, and PDR reviews.
- **IIT Kanpur**: Executed real flight experiments on Cessna 206H, Piper Saratoga, and NAL Hansa aircraft, extracting drag polars, CG determination, and neutral point from live flight data.
- **Chennai Drone Academy**: Built and maiden-flew 10+ custom FPV quadrotors end-to-end; logged 40+ flight hours, reducing average drone downtime from 2 days to under 18 hours.

---

## 🎓 Education

**M.S. Aerospace Engineering** — Arizona State University *(GPA: 3.87/4.0)*
Jan 2024 – Dec 2025 · Tempe, AZ
*Coursework: Linear Systems Theory · Advanced Modeling & Control · Nonlinear Control Design · Flight Dynamics · Estimation Theory · Robot Kinematics & Dynamics*

**B.E. Aeronautical Engineering** — Rajalakshmi Engineering College *(GPA: 8.17/10)*
2019 – 2023 · Chennai, India

---

## 📫 Let's Talk

I'm actively looking for full-time roles in UAV autonomy, GNC, robotics software, or forward deployed engineering. If you're building autonomous aerial or ground systems and want someone who can own the full stack, from control law to field test, let's connect.

<div align="center">

rganes13@asu.edu · [LinkedIn](https://www.linkedin.com/in/rohit-sanjay-g17/) · [GitHub](https://github.com/rohitsanjay-17-aerohub)

</div>
