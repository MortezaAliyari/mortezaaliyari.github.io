---
layout: profile
title: Home
permalink: /
---

# About

I’m a PhD candidate in Electrical Engineering at **National Taiwan University (NTU)**, working on **multi-agent RL**, **safe control**, and **real-world UAV experiments**. Before my PhD, I worked on **localization for self-driving vehicles** and **robotics software / embedded systems**.

## What I build (quick snapshot)

- **UAV autonomy**: safe learning + formation control + onboard perception
- **AMR fleet autonomy**: route planning, deadlock resolution, validation pipelines (ROS2)
- **Robust systems**: performance-focused C++ implementations and real deployment constraints

---

## Featured Videos & Demos

<div class="video-grid">

  <div class="card">
    <div class="video-embed">
      <iframe
        src="https://www.youtube.com/embed/cEvN69tPWAc"
        title="UAV Mapping with RGBD Camera"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>
    <div class="card-body">
      <h3>UAV Mapping with RGBD Camera (Depth → Map)</h3>
      <p><strong>Problem:</strong> GPS-denied mapping using onboard depth sensing.</p>
      <p><strong>What I built:</strong> ROS pipeline from depth → point cloud → mapping + tuning for stability.</p>
      <p><strong>Why it matters:</strong> Enables reliable autonomy and inspection without external infrastructure.</p>
      <div class="tags">
        <span class="tag">UAV</span><span class="tag">RealSense</span><span class="tag">ROS</span><span class="tag">Mapping</span>
      </div>
    </div>
  </div>

<div class="card">
  <div class="video-embed">
    <iframe
      src="https://www.youtube.com/embed/d5sq-jWmDXA"
      title="AMR Navigation with Task Planning (Behavior Trees)"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen></iframe>
  </div>

  <div class="card-body">
    <h3>AMR Navigation + Task Planning with Behavior Trees</h3>

    <p><strong>Problem:</strong> In warehouse environments, task execution can become hard to debug and maintain as the number of states, exceptions, and recovery behaviors grows.</p>

    <p><strong>What I built:</strong> A behavior-tree-based task planner in C++ to make execution logic modular (clear node responsibilities) and easy to extend with recovery/fallback behaviors.</p>

    <p><strong>How I validated it:</strong> Used <strong>Groot</strong> for real-time visualization and monitoring of task status, and integrated navigation with <strong>move_base_flex</strong> to support flexible planners/controllers and safer motion execution.</p>

    <p><strong>Impact:</strong> More transparent task status, faster debugging, and a more maintainable autonomy stack for real deployments.</p>

    <div class="tags">
      <span class="tag">AMR</span>
      <span class="tag">Behavior Trees</span>
      <span class="tag">Task Planning</span>
      <span class="tag">move_base_flex</span>
      <span class="tag">ROS</span>
      <span class="tag">C++</span>
    </div>
  </div>
</div>


</div>

**See all videos →** [/videos/](/videos/)  
**Projects →** [/projects/](/projects/) · **Publications →** [/publications/](/publications/) · **CV →** [/cv/](/cv/)
