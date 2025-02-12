---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: publications
---

---
title: "Multi-Task Safe Optimal Adaptive Tracking for Nonlinear Discrete-Time Systems"
date: 2024-02-11
layout: single
excerpt: "A multi-layer neural network-based approach for achieving multi-task safe optimal adaptive tracking in nonlinear discrete-time systems."
---

This paper presents a comprehensive approach for achieving multi-task safe optimal adaptive tracking (MSOAT) for a class of nonlinear discrete-time systems, particularly those in strict-feedback form, utilizing a multi-layer neural network (MNN)-based framework. 

To begin, a cost function with a novel Barrier function (BF) term is introduced for each subsystem to address the weak safely reachable problem, serving as a crucial tool for guiding the system's trajectory toward the safe set while avoiding unwanted sets. To deal with the tracking problem, the Hamilton-Jacobi-Bellman (HJB) framework is used through the actor-critic MNN-based backstepping technique to estimate the solution of the value functions and obtain both virtual and actual optimal control policies for each subsystem, effectively circumventing non-causality issues. 

Further, to mitigate catastrophic forgetting in multi-tasking scenarios, a regularizer term, which is derived from the online version of the Elastic Weight Consolidation (EWC) method, is included in the critic and actor MNN update laws without directly computing the Fisher information matrix. To enhance the convergence rate, the critic MNN is tuned with a hybrid learning technique involving weight adjustments both at specific sampling instants and iteratively within those intervals. A control barrier function (CBF) with a time-varying BF is also integrated into the actor update law, collaborating with the BF to keep the trajectory in the safe set with a smaller trade-off factor, simultaneously validating the safety condition in real-time. 

Finally, the overall stability is established. An example of a 6-DOF autonomous system is provided to validate the effectiveness of the proposed approach.

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
    <strong>Behzad Farzanegan</strong>, Jagannathan Sarangapani   
    <br>
    <em>International Journal of Adaptive Control and Signal Processing, 2024 (Published)</em>  
    <br>
</td>
</tr>
</table>
