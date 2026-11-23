<div align="center">
  <img src="./assets/pylot-banner.svg" width="100%" alt="PyLoT Robotics — Build robots. Share what works." />

  <br />
  <br />

  <a href="https://pylot.kaijo-physics.club/"><img src="https://img.shields.io/badge/WEBSITE-Visit%20PyLoT-62E8EF?style=for-the-badge&amp;labelColor=101D30" alt="Visit the PyLoT website" /></a>
  <a href="https://github.com/orgs/PyLoT-Robotics/repositories?type=source"><img src="https://img.shields.io/badge/OPEN%20SOURCE-Explore-ADA0FF?style=for-the-badge&amp;labelColor=101D30" alt="Explore our source repositories" /></a>

  <br />
  <br />

  <strong>Open-source tools and ideas from hands-on robotics.</strong>

  <p>From smartphone debugging to robot arm control and human perception.<br />
  We build the tools we wish we had — and share them with you.</p>

  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&amp;logo=ros&amp;logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Python-22314E?style=flat-square&amp;logo=python&amp;logoColor=75E9EF" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-22314E?style=flat-square&amp;logo=cplusplus&amp;logoColor=75E9EF" alt="C++" />
  <img src="https://img.shields.io/badge/Vue.js-22314E?style=flat-square&amp;logo=vuedotjs&amp;logoColor=75E9EF" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Docker-22314E?style=flat-square&amp;logo=docker&amp;logoColor=75E9EF" alt="Docker" />
</div>

<br />

## ✦ Made in the workshop

We build, test, and improve robots — and release the tools we create along the way.  
See each project's README for setup instructions, supported environments, and development status.

| Project | What it does | Code license |
| :--- | :--- | :--- |
| 📱 **[Robin](https://github.com/PyLoT-Robotics/robin)** | **Turn your phone into a robotics tool.** Debug, collect data, and visualize ROS 2 robots from a smartphone. | MIT |
| 🦾 **[kinematics_so100](https://github.com/PyLoT-Robotics/kinematics_so100)** | **Bring SO-ARM100 to ROS 2.** URDF models, inverse kinematics, and RViz visualization. | MIT |
| 👀 **[pinto_model_zoo_ros2](https://github.com/PyLoT-Robotics/pinto_model_zoo_ros2)** | **Connect perception models to robots.** ROS 2 wrappers for PINTO_model_zoo models, built for RoboCup@Home. | Apache-2.0 |
| 🧭 **[A-Star-MPC-Follower](https://github.com/PyLoT-Robotics/A-Star-MPC-Follower)** | **Plan a path. Follow smoothly.** A ROS 2 person-following controller combining A* path search, spline smoothing, and MPC. | MIT |
| 🚶 **[follow-person](https://github.com/PyLoT-Robotics/follow-person)** | **Person following, packaged.** ROS 2 person following with RealSense and 2D LiDAR, without a Nav2 dependency. | Apache-2.0 |
| 🖥️ **[PyLoT_Face](https://github.com/PyLoT-Robotics/PyLoT_Face)** | **Bring robot video to the browser.** A WebRTC video viewer and streaming node. | Apache-2.0 |
| ↕️ **[lift_wrapper](https://github.com/PyLoT-Robotics/lift_wrapper)** | **Simple lift control.** Arduino Uno stepper-motor control with serial movement commands and homing. | MIT |
| **[follow-person-cpp](https://github.com/PyLoT-Robotics/follow-person-cpp)** | C++17 LiDAR mapping for follow-person, with paired upstream benchmarks and English/Japanese documentation. | Apache-2.0 |
| **[a-star-mpc-follower-cpp](https://github.com/PyLoT-Robotics/a-star-mpc-follower-cpp)** | C++17 A* and occupancy-grid kernels with upstream parity checks and measured performance tables. | MIT |
| **[robot-audio-bench](https://github.com/PyLoT-Robotics/robot-audio-bench)** | Reproducible audio stimuli, SNR measurements, and speech-recognition evaluation reports. | Apache-2.0 |
| **[robot-knowledge-graph](https://github.com/PyLoT-Robotics/robot-knowledge-graph)** | YAML knowledge graphs with CRUD, text/PDDL export, a CLI, and ROS 2 integration. | Apache-2.0 |
| **[ros2-door-monitor](https://github.com/PyLoT-Robotics/ros2-door-monitor)** | LaserScan/TF door-state monitoring with debounce and a watchdog. | Apache-2.0 |
| **[ros2-pointcloud-crop](https://github.com/PyLoT-Robotics/ros2-pointcloud-crop)** | TF-aware multi-box PointCloud2 cropping while preserving point fields. | Apache-2.0 |
| **[ros2-named-locations](https://github.com/PyLoT-Robotics/ros2-named-locations)** | Record and store named poses, set an initial pose, and send Nav2 goals. | Apache-2.0 |
| **[ros2-arm-tools](https://github.com/PyLoT-Robotics/ros2-arm-tools)** | Joint limits, named-pose teaching, and FollowJointTrajectory move/jog tools. | Apache-2.0 |
| **[ros2-wave-detector](https://github.com/PyLoT-Robotics/ros2-wave-detector)** | Tracked waving-gesture detection with optional YOLO and aligned-depth integration. | Apache-2.0 |
| **[rgbd-grasp-estimator](https://github.com/PyLoT-Robotics/rgbd-grasp-estimator)** | RGB-D point clustering, surface normals, and geometric grasp estimation. | Apache-2.0 |
| **[ros2-gamepad-teleop](https://github.com/PyLoT-Robotics/ros2-gamepad-teleop)** | Gamepad control for base, head, arm, gripper, and speech requests, with configurable joint profiles and an input watchdog. | Apache-2.0 |
| **[step-response-tools](https://github.com/PyLoT-Robotics/step-response-tools)** | Offline CSV analysis of settling time, overshoot, and oscillation reversals in arbitrary physical units. | Apache-2.0 |

Robin, the C++ variants, and the standalone tools provide English READMEs with linked Japanese documentation. The C++ performance tables report measured kernel/callback workloads; see each README for conditions and scope.

This list includes public projects with an identified code license. Model weights, datasets, and dependencies have their own terms.  
Some models used by **pinto_model_zoo_ros2** have non-commercial or research-only terms. Check each repository's license and NOTICE files for details.

<details>
<summary><strong>✦ OSS forks — Projects we build on</strong></summary>

<br />

These repositories are forks of existing open-source projects. Follow the upstream links to meet their original developers and explore their work.

| Repository | What it does | Upstream | Code license |
| :--- | :--- | :--- | :--- |
| **[DynamixelSDK](https://github.com/PyLoT-Robotics/DynamixelSDK)** | SDK for DYNAMIXEL servos. | [tasada038/DynamixelSDK](https://github.com/tasada038/DynamixelSDK) | Apache-2.0 |
| **[detic_onnx_ros2](https://github.com/PyLoT-Robotics/detic_onnx_ros2)** | Detic ONNX inference for ROS 2. | [OUXT-Polaris/detic_onnx_ros2](https://github.com/OUXT-Polaris/detic_onnx_ros2) | Apache-2.0 |
| **[feetech_scs_ros2_driver](https://github.com/PyLoT-Robotics/feetech_scs_ros2_driver)** | ROS 2 driver for FeeTech servos. | [fateshelled/feetech_scs_ros2_driver](https://github.com/fateshelled/feetech_scs_ros2_driver) | Apache-2.0 |
| **[livox_ros_driver2](https://github.com/PyLoT-Robotics/livox_ros_driver2)** | ROS driver for Livox LiDAR. | [atinfinity/livox_ros_driver2](https://github.com/atinfinity/livox_ros_driver2) | MIT and others ([details](https://github.com/PyLoT-Robotics/livox_ros_driver2/blob/humble/LICENSE.txt)) |
| **[ros2_vosk](https://github.com/PyLoT-Robotics/ros2_vosk)** | ROS 2 speech recognition with Vosk. | [redchillipadi/ros2_vosk](https://github.com/redchillipadi/ros2_vosk) | Apache-2.0 |
| **[ros2_vosk_msgs](https://github.com/PyLoT-Robotics/ros2_vosk_msgs)** | Message definitions for ros2_vosk. | [redchillipadi/ros2_vosk_msgs](https://github.com/redchillipadi/ros2_vosk_msgs) | Apache-2.0 |
| **[sobits_gazebo_worlds](https://github.com/PyLoT-Robotics/sobits_gazebo_worlds)** | Worlds for Gazebo simulation. | [TeamSOBITS/sobits_gazebo_worlds](https://github.com/TeamSOBITS/sobits_gazebo_worlds) | BSD-3-Clause |
| **[urg_node2](https://github.com/PyLoT-Robotics/urg_node2)** | ROS 2 driver for HOKUYO 2D LiDAR. | [Hokuyo-aut/urg_node2](https://github.com/Hokuyo-aut/urg_node2) | Apache-2.0 |

</details>

<p align="center">
  <a href="https://github.com/orgs/PyLoT-Robotics/repositories?type=public">Explore all public repositories →</a>
</p>

## ✦ Robots for people

We are a student robotics team based at Tokyo Metropolitan University, Japan.  
Through RoboCup@Home and hands-on development, we explore robots that support everyday life — and share the tools we build along the way.

## ✦ Build with us

Feedback, bug reports, documentation improvements, and code contributions are all welcome.

- **Try it** — Try a project and tell us about your setup and experience.
- **Open an issue** — Share questions, bugs, and ideas in the relevant repository.
- **Send a PR** — Small fixes and improvements are welcome, too.

We build on the work of the open-source community and credit the original developers.  
Please check each repository for the licenses and terms that apply to its code, models, and other components.

<br />

<div align="center">
  <strong>Built by students. Shared with everyone.</strong><br />
  <sub>PyLoT Robotics · Japan · <a href="https://pylot.kaijo-physics.club/">Website</a></sub>
</div>
