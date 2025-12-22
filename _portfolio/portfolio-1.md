---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: publications
---

## Selected Projects

<!-- Qcar ========================================================================================== -->
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
    <td width="25%" style="border: none; text-align: center;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/Qcar.jpg" style="max-width: 100%; height: auto; border-radius: 15px;">
        </div>
    </td>
    <td style="border: none; padding: 10px;">
        <strong>QCar Control and Estimation Framework</strong>  
        <br>
        This project implements a control and estimation framework for a QCar system, leveraging sensor fusion techniques with Kalman Filters (KF) and Extended Kalman Filters (EKF). The system integrates data from gyroscopes, GPS, and motor tachometers to estimate the state of the vehicle, including position, heading angle, and sensor biases. To ensure precise motion control, the system employs a Proportional-Integral-Derivative (PID) controller. The PID controller regulates vehicle speed and 
        steering angle by dynamically adjusting control inputs based on real-time state estimates. 
    </td>
</tr>
</table>

<div style="display: flex; justify-content: center; align-items: center; width: 100%; margin-top: 20px; gap: 10px;">
    <video style="width: 45%; height: auto;" controls>
        <source src="/images/Qcar.webm" type="video/webm">
        Your browser does not support the video tag.
    </video>
    <img src="/images/EKF.png" alt="EKF" style="width: 45%; height: auto;">
</div>


---
<!-- Qdrone ========================================================================================== -->
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
    <td width="25%" style="border: none; text-align: center;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/uav.png" style="max-width: 100%; height: auto; border-radius: 15px;">
        </div>
    </td>
    <td style="border: none; padding: 10px;">
        <strong>Multi-Layer Neural Network-Based Optimal Adaptive Tracking Control of Unmanned Aerial Vehicles</strong>  
        <br>
        We propose a novel deep reinforcement learning-based optimal adaptive tracking control framework for 
        nonlinear discrete-time UAV systems with partially uncertain dynamics. The approach employs an 
        actor-critic multilayer neural network (MNN) to approximate the value function and optimize the UAV control policy.  
        A hybrid learning scheme is introduced, where the critic MNN weights are updated in real-time at each sampling instant 
        and refined iteratively between instants to accelerate convergence.  
        To mitigate the persistency of excitation (PE) condition, a replay buffer is incorporated into the critic update law 
        using concurrent learning, improving sample efficiency and control robustness. This approach enhances UAV tracking accuracy while reducing cumulative 
        control cost, ensuring robust performance under uncertainty.  
    </td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="50%" controls>
        <source src="/images/qdrone.MP4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

---

<!-- bumperbot ========================================================================================== -->
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
    <td width="25%" style="border: none; text-align: center;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/bumperbot2" style="max-width: 100%; height: auto; border-radius: 15px;">
        </div>
    </td>
    <td style="border: none; padding: 10px;">
        <strong>Bumperbot: ROS2-Based Mobile Robot Control & Estimation</strong>  
        <br>
        This project focuses on the development and simulation of a mobile robot (Bumperbot) using ROS2, integrating motion control, sensor fusion, and state estimation. The robot’s dynamics and hardware configuration were defined using URDF, and the <code>ros2_control</code>     plugin was implemented for real-time actuation. Simulation was conducted in Gazebo, providing a realistic environment for testing. 
         The robot is controlled via a joystick, interfaced with ROS2 for seamless manual operation. For autonomous capabilities, an IMU and wheel encoders were utilized, with an Extended Kalman Filter (EKF) fusing sensor data for accurate state estimation. This allowed for precise             localization and motion control. 
        <br><br>
        <strong>Key Features:</strong>
        <ul>
            <li>URDF-based robot modeling and integration with <code>ros2_control</code></li>
            <li>Simulation and validation in Gazebo</li>
            <li>Joystick-based teleoperation using ROS2 interfaces</li>
            <li>IMU and wheel encoder fusion with EKF for state estimation</li>
            <li>Real-time sensor data processing and motion control</li>
        </ul>
    </td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="45%" controls poster="/images/bumperbot_preview.png">
        <source src="/images/bumperbot.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video width="45%" controls>
        <source src="/images/bumperbot_control.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
---
<!-- bumperbot 2========================================================================================== -->

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 30px;">
<tr style="border: none;">
    <td width="25%" style="border: none; text-align: center; vertical-align: top;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/bumperbot.png" style="max-width: 100%; height: auto; border-radius: 15px;">
        </div>
    </td>
    <td style="border: none; padding: 10px; vertical-align: top;">
        <strong>Custom ROS 2 Global Planners (C++ Implementation)</strong>  
        <br>
        This project focuses on the algorithmic core of autonomous navigation. Rather than relying on pre-built packages, I implemented <strong>Dijkstra</strong> and <strong>A* (A-Star)</strong> path planning algorithms from scratch in C++. These planners operate as standalone ROS 2 nodes, subscribing to <code>/map</code> and <code>/goal_pose</code> to calculate optimal trajectories in real-time.
        <br><br>
        The implementation handles raw <code>OccupancyGrid</code> data, transforming world coordinates to grid indices to build a graph representation of the environment. I utilized standard C++ optimization techniques (priority queues, custom comparators) to ensure efficient pathfinding. The nodes also publish visualization data, allowing for real-time debugging of the search frontier (visited nodes) versus the final calculated path in RViz.
        <br><br>
    </td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px; margin-bottom: 40px;">
    <video width="50%" controls poster="/images/dijkstra_preview.png">
        <source src="/images/Planner.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>


---

<!-- bumperbot 3========================================================================================== -->

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 30px;">
<tr style="border: none;">
    <td width="25%" style="border: none; text-align: center; vertical-align: top;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/bumperbot.png" style   </td>
    <td style="border: none; padding: 10px; vertical-align: top;">
        <strong>Custom ROS 2 Motion Planning Framework (C++ Implementation)</strong>  
        <br>
        This project implements a complete navigation pipeline, starting with global path planning and followed by local motion control. The global planner uses the <strong>A*</strong> algorithm, developed from scratch in C++, to compute an optimal path on an occupancy grid map. The planner runs as a ROS 2 node, subscribing to <code>/map</code> and <code>/goal_pose</code> topics to generate collision-free paths in real time.
        <br><br>
        After generating the global path, two different motion planning strategies were implemented for trajectory tracking:
        <ul>
            <li><strong>PD Controller:</strong> A proportional-derivative controller for smooth heading and position error correction, ensuring stable convergence to the path.</li>
            <li><strong>Pure Pursuit:</strong> A geometric approach that selects a dynamic look-ahead point on the path and computes steering commands for efficient path following.</li>
        </ul>
        <br><br>
    </td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px; margin-bottom: 40px;">
    <video width="45%" controls poster="/images/pure_pursuit.png">
        <source src="/images/pure_pursuit.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video width="45%" controls poster="/images/Motion_PD.png">
        <source src="/images/Motion_PD.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>


---
<!-- AUV ========================================================================================== -->


<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="25%" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/AUV.png" style="max-width: 100%; height: auto; border-radius: 15px;">
    </div>
</td>
<td style="border: none; padding: 10px;">
    <strong> Multi-Tasking Deep RL-Based Optimal Control of 6-DoF Autonomous Underwater Vehicles</strong>  
    <br>
    Developed a reinforcement learning-based control framework for safe and optimal tracking of 6-DoF AUVs. The approach integrates an MNN-based actor-critic method with backstepping and Hamilton-Jacobi-Bellman (HJB) optimization to derive optimal control policies. Safety is ensured through Barrier Functions (BFs) and Control Barrier Functions (CBFs) integrated into learning update laws, while Elastic Weight Consolidation (EWC) prevents catastrophic forgetting in multi-task scenarios. Simulations validate the system’s stability, adaptability, and effectiveness in dynamic underwater environments.
</td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="50%" controls>
        <source src="/images/AUV.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>




---
<!-- USV ========================================================================================== -->
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="25%" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/USV.png" style="max-width: 100%; height: auto; border-radius: 15px;">
    </div>
</td>
<td style="border: none; padding: 10px;">
    <strong>Explainable Multi-Model Safety-Aware Deep RL Output Feedback Control with Obstacle Avoidance and A* Path Planning for Autonomous Surface Vessels</strong>  
    <br>
Developed an Explainable safety-aware deep reinforcement learning (DRL)-based control framework for optimal trajectory tracking of Autonomous Surface Vessels (ASVs). The framework employs a multilayer neural network (MNN) observer for state estimation and integrates Control Barrier Functions (CBFs) into the Hamiltonian via the Lagrangian multiplier to enforce safety constraints. An actor-critic MNN, optimized using Singular Value Decomposition (SVD), stabilizes learning by mitigating the vanishing gradient problem. Additionally, a safe lifelong learning (SLL) scheme based on multiple models prevents catastrophic forgetting across varying ASV dynamics. The framework also incorporates an A* path planning module for generating collision-free trajectories and a real-time obstacle avoidance strategy for safe navigation. SHAP analysis is used to enhance interpretability by identifying critical features in the optimal policy. Simulations on an underactuated ASV model demonstrate that SLL improves performance, reducing cumulative costs by 17% and RMS tracking error by 32% compared to a non-SLL control scheme.
</td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="50%" controls>
        <source src="/images/USV.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<div style="display: flex; justify-content: center; align-items: center; gap: 5px; flex-wrap: nowrap; max-width: 80vw;">
    <img src="/images/correlation_heatmap.png" alt="Correlation Heatmap" style="width: 35%; height: auto;">
    <img src="/images/shap_summary_plot.png" alt="SHAP Summary Plot" style="width: 35%; height: auto;">
</div>

---

<!-- DDPG ========================================================================================== -->
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="25%" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/DDPG_Pendulum.png" style="max-width: 100%; height: auto; border-radius: 15px;">
    </div>
</td>
<td style="border: none; padding: 10px;">
    <strong>Deep Reinforcement Learning: DDPG for Continuous Control</strong>  
    <br>
    Implemented a robust Deep Reinforcement Learning framework (DDPG) using TensorFlow and the Keras Functional API to solve continuous control benchmarks (Gymnasium Pendulum-v1). The architecture utilizes a model-free Actor-Critic approach with Ornstein-Uhlenbeck (OU) process noise to optimize exploration in physical tasks with inertia. System stability is achieved through an optimized Experience Replay buffer for off-policy learning and Polyak averaging (soft updates) for target network synchronization, ensuring convergence in high-dimensional continuous action spaces.
</td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="50%" controls>
        <source src="/images/DDPG_Demo.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>






