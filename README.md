# Mobile Robotics Projects

This repository contains all homework assignments and projects developed as part of the **EECE 5550: Mobile Robotics** course at Northeastern University.

Each assignment focuses on a core area in mobile robotics, including kinematics, control, localization, SLAM, and planning.

## ✅ Implemented

#### HW1 – Pure Pursuit Path Tracking
Implemented a Pure Pursuit controller using a lookahead point to compute curvature and angular velocity (`omega`) for trajectory following. Includes kinematic modeling and visual path evaluation.

#### HW2 – MPPI Local Planner
Developed a sampling-based Model Predictive Path Integral (MPPI) planner to move a robot toward a target position. Formulated and optimized a trajectory cost function over rollouts using CVXPY. Includes local planner simulation and control sampling.

#### HW3 – Lidar Sensing and Coordinate Frames
Simulated a 2D Lidar sensor model, incorporating noise and probabilistic modeling. Implemented coordinate frame transformations and sensor field-of-view logic for mapping perception data accurately in the robot's world frame.

#### HW4 – Monte Carlo Localization and Mapping
Built a Monte Carlo Localization (MCL) system to estimate robot pose using sensor likelihoods and motion updates. Implemented occupancy grid mapping using laser data, enabling SLAM-like functionality in a known map environment.

#### HW5 – Graph-Based SLAM with GTSAM
Used the GTSAM library to implement full Graph SLAM by constructing a factor graph from odometry and Lidar landmark measurements. Optimized the pose graph using nonlinear solvers for accurate global mapping and localization.

