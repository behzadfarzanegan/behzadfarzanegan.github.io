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
    Developed a reinforcement learning-based control framework for safe and optimal tracking of 6-DoF AUVs. The approach integrates an MNN-based actor-critic method with backstepping and Hamilton-Jacobi-Bellman (HJB) optimization to derive optimal control policies. Safety is ensured through Barrier Functions (BFs) and Control Barrier Functions (CBFs), while Elastic Weight Consolidation (EWC) prevents catastrophic forgetting in multi-task scenarios. Simulations validate the system’s stability, adaptability, and effectiveness in dynamic underwater environments.
</td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="800" controls>
        <source src="/images/auv.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

---

<table style="border-collapse: collapse; border: none; width: 100%;">
<tr style="border: none;">
<td width="250" style="border: none; text-align: center;">
    <div style="border: 2px solid black; border-radius: 15px; padding: 10px; display: inline-block;">
        <img src="/images/ASV.png" width="250" style="border-radius: 15px;">
    </div>
</td>
<td style="border: none; padding: 10px;">
    <strong>Explainable Multi-Model Safety-Aware Deep RL Output Feedback Control for Autonomous Surface Vessels</strong>  
    <br>
    Developed a deep reinforcement learning-based optimal control framework for safety-aware trajectory tracking of Autonomous Surface Vessels (ASVs). The system integrates an MNN-based observer to estimate state vectors, addressing system uncertainties. Safety constraints are enforced by incorporating a Control Barrier Function (CBF) into the Hamiltonian using Karush-Kuhn-Tucker (KKT) conditions. 

    To enhance learning stability, an actor-critic MNN with Singular Value Decomposition (SVD) tuning mitigates the vanishing gradient problem. Additionally, a safe lifelong learning (SLL) control scheme prevents catastrophic forgetting when adapting to varying ASV dynamics. The framework further employs Shapley Additive Explanations (SHAP) for interpretability, identifying key factors influencing the DRL-based control policy. 

    Simulation results on a nonlinear, underactuated ASV model demonstrate the effectiveness of SLL, achieving a **17% reduction in cumulative costs** and **32% improvement in RMS tracking error** compared to non-SLL approaches.
</td>
</tr>
</table>

<div style="text-align: center; margin-top: 20px;">
    <video width="800" controls>
        <source src="/images/asv.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>


---
