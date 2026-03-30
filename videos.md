---
layout: profile
title: Videos
permalink: /videos/
---

# Videos & Demos

Here are selected demonstrations of my work in robotics and UAV autonomy, mapping, and mobile robot navigation.

<div class="video-grid">

  <div class="card">
    <div class="video-embed">
      <iframe
        src="https://www.youtube.com/embed/cEvN69tPWAc"
        title="UAV Mapping with RGBD Camera"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>

    <div class="project-update">
      <img
        src="{{ '/assets/img/last-update-jun_2025_icon.png' | relative_url }}"
        alt="Last update icon"
        class="project-update-icon" />
      <!-- <span class="project-update-text">Last update: Month YYYY</span> -->
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
        src="https://www.youtube.com/embed/3yPShnmhooA"
        title="RVO->Real-time avoidance capabilities in dynamic obstacles environments"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>

    <div class="project-update">
      <img
        src="{{ '/assets/img/last-update-Mar_2024_icon.png' | relative_url }}"
        alt="Last update icon"
        class="project-update-icon" />
      <!-- <span class="project-update-text">Last update: Month YYYY</span> -->
    </div>

    <div class="card-body">
      <h3>Multi-agent obstacle-avoidance simulation framework</h3>
      <p><strong>Problem:</strong> How can multiple robots maintain safe, coordinated motion in dynamic and crowded environments without relying too heavily on a single leader?</p>
      <p><strong>What I built:</strong> A ROS1/Gazebo/C++ multi-agent simulation framework inspired by reciprocal collision avoidance for cooperative robot navigation.</p>
      <p><strong>Why it matters:</strong> It built my foundation in swarm robotics, decentralized avoidance, and scalable multi-agent system design.</p>
      <div class="tags">
        <span class="tag">AMR</span><span class="tag">Lidar</span><span class="tag">ROS1</span><span class="tag">C++</span>
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

    <div class="project-update">
      <img
        src="{{ '/assets/img/last-update-sep_2022_icon.png' | relative_url }}"
        alt="Last update icon"
        class="project-update-icon" />
      <!-- <span class="project-update-text">Last update: Month YYYY</span> -->
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

    <div class="card">
    <div class="video-embed">
      <iframe
        src="https://www.youtube.com/embed/XaLbEKf8UhA"
        title="Multi Robots Navigation ROS Noetic and Gazebo"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>

    <div class="project-update">
      <img
        src="{{ '/assets/img/last-update-jan_2022_icon.png' | relative_url }}"
        alt="Last update icon"
        class="project-update-icon" />
      <!-- <span class="project-update-text">Last update: Month YYYY</span> -->
    </div>

    <div class="card-body">
      <h3>Multi Robots Navigation ROS Noetic and Gazebo</h3>
      <p><strong>Problem:</strong> What happens when one robot is no longer enough? The jump from single-robot navigation to multi-agent systems is where robotics becomes far more realistic—and far more challenging. Managing multiple robots in ROS1 means handling separate topics, namespaces, and control flows without interference.</p>
      <p><strong>What I built:</strong> I built a dual-TurtleBot3 navigation project in ROS1 using C++, Gazebo 11, and Ubuntu Focal, where two different robots operate in the same simulated environment. The core focus was creating a clean multi-agent structure by properly separating each robot’s topics and navigation stack.</p>
      <p><strong>Why it matters:</strong> This project gave me the hands-on foundation for future multi-agent robotics systems. It was an early but essential step toward scalable robot coordination, where the real challenge is not just motion—but architecture, communication, and system reliability.</p>
      <div class="tags">
        <span class="tag">Obstacle-Avoidance</span><span class="tag">Multiagent</span><span class="tag">ROS</span><span class="tag">RealTime</span>
      </div>
    </div>
  </div>





</div>
