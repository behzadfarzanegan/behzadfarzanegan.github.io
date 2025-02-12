---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: publications
---

## Selected Project

<table style="border-collapse: collapse; border: none;">
<tr style="border: none;">
<td width="200" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/AUV.png" width="150" style="border-radius: 15px;">
    </div>
</td>
<td style="border: none;">
    <strong>Deep RL-based Optimal Control of 6-DoF Autonomous Underwater Vehicles</strong>  
    <br>
    uring my research at Missouri University of Science and Technology, I developed a novel reinforcement learning-based control framework for multi-task safe optimal adaptive tracking (MSOAT) in nonlinear discrete-time systems, particularly those in strict-feedback form. This work aimed to enhance safety, stability, and adaptability in autonomous systems such as robot manipulators, mobile robots, and unmanned surface vehicles.

The proposed approach utilizes a multi-layer neural network (MNN)-based actor-critic framework combined with backstepping techniques to solve the Hamilton-Jacobi-Bellman (HJB) equation. This enables the estimation of optimal value functions and the derivation of both virtual and actual optimal control policies while circumventing non-causality issues. To ensure safe system operation, a novel Barrier Function (BF) is introduced in the cost function of each subsystem, guiding the system trajectory toward safe regions while avoiding undesirable states. Additionally, a control barrier function (CBF) with a time-varying BF is integrated into the actor update law to provide real-time safety guarantees with minimal trade-offs.

To address the challenge of catastrophic forgetting in multi-task learning, a regularization term inspired by the online Elastic Weight Consolidation (EWC) method is incorporated into the critic and actor MNN update laws. This allows the system to retain knowledge across multiple tasks without the need for direct computation of the Fisher information matrix. The training process is further enhanced by a hybrid learning technique that adjusts critic weights at specific sampling instants and iteratively within those intervals, significantly improving convergence rates.

The theoretical stability of the proposed framework is rigorously established, and its effectiveness is demonstrated through simulations on a six-degree-of-freedom (6-DOF) autonomous system. This research contributes to the field of reinforcement learning-based adaptive control, providing a robust and scalable solution for safety-aware decision-making in autonomous and intelligent systems operating in dynamic environments. 
    <br>
    <em>International Journal of Adaptive Control and Signal Processing, 2024 (Published)</em>  
    <br>
</td>
</tr>
</table>
