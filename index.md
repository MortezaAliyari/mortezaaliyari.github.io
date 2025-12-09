---
layout: default
---

<style>
  .page-wrapper {
    max-width: 1000px;
    margin: 2rem auto;
    display: flex;
    gap: 2rem;
  }

  .sidebar {
    flex: 0 0 260px;
  }

  .profile-card {
    border: 1px solid #e0e0e0;
    background: #fafafa;
    padding: 1.5rem;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0,0,0,0.06);
  }

  .profile-photo {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
  }

  .profile-name {
    font-size: 1.4rem;
    font-weight: 700;
    margin-bottom: 0.25rem;
  }

  .profile-role {
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 0.75rem;
  }

  .profile-location {
    font-size: 0.9rem;
    color: #555;
    margin-bottom: 0.75rem;
  }

  .profile-links {
    list-style: none;
    padding: 0;
    margin: 0;
    text-align: left;
    font-size: 0.95rem;
  }

  .profile-links li {
    margin: 0.35rem 0;
  }

  .profile-links span {
    margin-right: 0.4rem;
  }

  .profile-links a {
    text-decoration: none;
  }

  .profile-links a:hover {
    text-decoration: underline;
  }

  .main-content {
    flex: 1;
  }

  .main-content h1 {
    margin-top: 0;
  }

  @media (max-width: 768px) {
    .page-wrapper {
      flex-direction: column;
    }
    .sidebar {
      flex: 1 1 auto;
    }
  }
</style>

<div class="page-wrapper">

  <aside class="sidebar">
    <div class="profile-card">
      <img src="/assets/img/profile.jpg" alt="Morteza Aliyari" class="profile-photo" />

      <div class="profile-name">Morteza Aliyari</div>
      <div class="profile-role">
        PhD Candidate · Robotics &amp; Control
      </div>
      <div class="profile-location">
        📍 Taipei, Taiwan
      </div>

      <ul class="profile-links">
        <li><span>✉️</span><a href="mailto:D12921b18@ntu.edu.tw">NTU Email</a></li>
        <li><span>✉️</span><a href="mailto:mortezaliyari@gmail.com">Gmail</a></li>
        <li><span>🔗</span><a href="https://www.linkedin.com/in/morteza-aliyari" target="_blank">LinkedIn</a></li>
        <li><span>🐙</span><a href="https://github.com/MortezaAliyari" target="_blank">GitHub</a></li>
        <li><span>🎓</span><a href="https://scholar.google.com" target="_blank">Google Scholar</a></li>
        <li><span>📺</span><a href="https://www.youtube.com/@mortezaaliyari1055" target="_blank">YouTube</a></li>
      </ul>
    </div>
  </aside>

  <section class="main-content">
    <h1>About</h1>
    <p>
      I work at the intersection of <strong>nonlinear control</strong>,
      <strong>multi-agent deep reinforcement learning</strong>, and
      <strong>real-world robotic systems</strong>. My recent projects focus on
      <strong>safe TSY null-space RL for bearing-rigid quadrotor formations</strong> and
      <strong>multi-robot route planning for autonomous mobile robots (AMRs)</strong>
      in ROS2-based systems.
    </p>
    <p>
      Core tools: ROS2, PX4, Gazebo, C++17, Python, and solid data structures &amp;
      algorithms. Keywords: UAV formation control, safe RL, control barrier
      functions, multi-agent path planning, warehouse robotics.
    </p>

    <h2>Research Interests</h2>
    <ul>
      <li>Multi-UAV formation control and bearing rigidity</li>
      <li>Safe reinforcement learning and control barrier functions</li>
      <li>Multi-agent route planning, deadlock detection and resolution</li>
      <li>ROS2, PX4, Gazebo, and real-world robotic experimentation</li>
      <li>High-performance C/C++ and Python implementations</li>
    </ul>

    <h2>Selected Publications</h2>
    <ol>
      <li>
        <strong>M. Aliyari</strong>, C.-H. Tsai, T.-K. Lin, E.-R. Wang, M.-L. Chiang, and L.-C. Fu,<br/>
        <em>“Safe TSY null-space deep reinforcement learning for bearing-rigid quadrotor formations,”</em><br/>
        preprint, 2026.
      </li>
      <li>
        <strong>M. Aliyari</strong>, W.-K. Wong, Y. Bouteraa, S. Najafinia, A. Fekih, and S. Mobayen,<br/>
        <em>“Design and implementation of a constrained model predictive control approach for unmanned aerial vehicles,”</em><br/>
        <em>IEEE Access</em>, vol. 10, pp. 91750–91762, 2022. doi: 10.1109/ACCESS.2022.3202020.
      </li>
      <li>
        F. Bayat, S. Najafinia, and <strong>M. Aliyari</strong>,<br/>
        <em>“Mobile robots path planning: Electrostatic potential field approach,”</em><br/>
        <em>Expert Systems with Applications</em>, vol. 100, pp. 68–78, 2018.
        doi: 10.1016/j.eswa.2018.01.050.
      </li>
      <li>
        A. Khooshehmehri, S. Nasrollahi, and <strong>M. Aliyari</strong>,<br/>
        <em>“Chaos synchronization in Josephson junction using a nonlinear model predictive controller based on particle filter: Processor in the loop implementation,”</em><br/>
        <em>International Journal of Industrial Electronics, Control and Optimization</em>, vol. 4, no. 3, pp. 355–366, Jul. 2021.
      </li>
      <li>
        A. Khooshehmehri, S. Nasrollahi, and <strong>M. Aliyari</strong>,<br/>
        <em>“Chaos synchronization in Josephson junction using nonlinear robust adaptive controller: HIL implementation,”</em><br/>
        <em>International Journal of Dynamics and Control</em>, vol. 10, pp. 1228–1239, 2022.
        doi: 10.1007/s40435-021-00870-9.
      </li>
    </ol>

    <h2>Selected Projects</h2>

    <h3>Safe Null-Space RL for Bearing-Rigid UAV Formations</h3>
    <ul>
      <li>Combines a rigidity-based formation controller with deep RL in the TSY null space.</li>
      <li>Enables safe translation, scaling, and rotation of multi-UAV formations while preserving bearing rigidity.</li>
      <li>Implemented in C++/Python + ROS2, evaluated in cluttered and dynamic environments.</li>
    </ul>

    <h3>Multi-Robot Route Planner for AMRs (ROS2)</h3>
    <ul>
      <li>Designed a <strong>GraphPlanner + AgentMonitor</strong> pipeline for large-scale AMR fleets in warehouse-like environments.</li>
      <li>Implements collision detection, deadlock resolution, and route validation for dozens of robots.</li>
      <li>Includes a benchmarking framework to compare planning algorithms at scale, with modular code architecture for real deployments.</li>
    </ul>

    <h3>UAV Model Predictive Control (IEEE Access)</h3>
    <ul>
      <li>Constrained MPC design for quadrotor trajectory tracking under input and state limitations.</li>
      <li>Validated through simulation and real-time processor-in-the-loop experiments.</li>
    </ul>

    <h2>Experience</h2>
    <ul>
      <li>
        <strong>PhD Candidate in Electrical Engineering</strong> – National Taiwan University<br/>
        Safe RL for bearing-rigid quadrotor formations and multi-UAV systems;
        formation control, CBF-based safety, and ROS2 / PX4 experiments.
      </li>
      <li>
        <strong>Robotics / Control Engineer (Autonomous Mobile Robots)</strong><br/>
        Multi-robot path planning and fleet management for AMRs in warehouses;
        ROS2-based route planner, deadlock resolution, and real-world deployment.
      </li>
    </ul>

    <h2>CV</h2>
    <p>
      <a href="/assets/cv_morteza_aliyari.pdf">Download my CV (PDF)</a>
      (place your CV at <code>/assets/cv_morteza_aliyari.pdf</code> in the repo).
    </p>

    <h2>Contact</h2>
    <p>
      The fastest way to reach me is by email or LinkedIn. I am open to research
      collaborations and internship opportunities in robotics, safe RL, and
      multi-agent systems.
    </p>
  </section>

</div>
