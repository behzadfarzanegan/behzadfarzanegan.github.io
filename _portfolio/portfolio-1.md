---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: publications
---

## Selected Projects
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="250" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/AUV.png" width="250" style="border-radius: 15px;">
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
    <video width="600" controls>
        <source src="/images/AUV.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>





---

<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="250" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/USV.png" width="250" style="border-radius: 15px;">
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
    <video width="600" controls>
        <source src="/images/USV.webm" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<div style="display: flex; justify-content: center; align-items: center; gap: 5px; flex-wrap: nowrap; max-width: 80vw;">
    <img src="/images/correlation_heatmap.png" alt="Correlation Heatmap" style="width: 35%; height: auto;">
    <img src="/images/shap_summary_plot.png" alt="SHAP Summary Plot" style="width: 35%; height: auto;">
</div>









---
<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
    <td width="250" style="border: none; text-align: center;">
        <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
            <img src="/images/uav.png" width="250" style="border-radius: 15px;">
        </div>
    </td>
    <td style="border: none; padding: 10px;">
        <strong>Multi-Layer Neural Network-Based Optimal Adaptive Tracking Control of Unmanned Aerial Vehicles</strong>  
        <br>
        We propose a novel <strong>deep reinforcement learning-based optimal adaptive tracking control framework</strong> for 
        <strong>nonlinear discrete-time UAV systems</strong> with <strong>partially uncertain dynamics</strong>. The approach employs an 
        <strong>actor-critic multilayer neural network (MNN)</strong> to approximate the <strong>value function</strong> and optimize the UAV control policy.  

        A <strong>hybrid learning scheme</strong> is introduced, where the <strong>critic MNN weights</strong> are updated <strong>in real-time at each sampling instant</strong> 
        and refined iteratively <strong>between instants</strong> to accelerate convergence.  

        To mitigate the <strong>persistency of excitation (PE) condition</strong>, a <strong>replay buffer</strong> is incorporated into the <strong>critic update law</strong> 
        using <strong>concurrent learning</strong>, improving sample efficiency and control robustness. This approach enhances UAV tracking accuracy while reducing cumulative 
        control cost, ensuring robust performance under uncertainty.  
    </td>
</tr>
</table>




