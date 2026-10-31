---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
.project-catalog { display: grid !important; grid-template-columns: repeat(2, minmax(0, 1fr)) !important; gap: 22px !important; margin: 22px 0 44px !important; }
.project-tile { display: block !important; min-width: 0; overflow: hidden; border-radius: 10px; border: 1px solid #d9e2e8; background: transparent; text-decoration: none !important; color: inherit !important; box-shadow: 0 2px 8px rgba(17,35,49,.05); }
.project-tile:hover { box-shadow: 0 9px 22px rgba(17,35,49,.14); }
.project-tile img, .project-tile video { display: block !important; width: 100% !important; height: 205px !important; object-fit: cover !important; border-radius: 0; margin: 0; }
.project-tile .tile-body { padding: 16px 18px 19px !important; }
.project-tile h3 { margin: 0 0 9px; font-size: 1.08rem; line-height: 1.35; }
.project-tile p { margin: 0; color: #596b76; font-size: .86rem; line-height: 1.5; }
.project-tile .research-meta { margin-top: 11px; font-size: .74rem; font-weight: 600; letter-spacing: .025em; color: #486e81; }
@media(max-width:680px) { .project-catalog { grid-template-columns: 1fr !important; } .project-tile img, .project-tile video { height: 205px !important; } }
@media(prefers-color-scheme:dark) { .project-tile p { color: #b5c1c9; } .project-tile { border-color: #4f616b; } .project-tile .research-meta { color: #9cc5d4; } }
</style>
## Research Projects

<div class="project-catalog">

  <a class="project-tile" href="{{ '/projects/speak-to-the-city/' | relative_url }}">
    <img src="{{ '/images/speak-to-the-city-thumbnail.png' | relative_url }}" alt="Speak to the City thumbnail">
    <div class="tile-body">
      <h3>Speak to the City</h3>
      <p>Multimodal resolution of outside-the-vehicle references in dynamic automotive environments.</p>
      <div class="research-meta">AutomotiveUI 2026 · Best Paper</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/gesturecoach/' | relative_url }}">
    <img src="{{ '/images/gesturecoach_thumbnail.png' | relative_url }}" alt="GestureCoach thumbnail">
    <div class="tile-body">
      <h3>GestureCoach</h3>
      <p>LLM-driven gesture recommendations for presentation rehearsal.</p>
      <div class="research-meta">UIST 2025</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/3hands/' | relative_url }}">
    <img src="{{ '/images/3hands_thumbnail.png' | relative_url }}" alt="3HANDS thumbnail">
    <div class="tile-body">
      <h3>3HANDS</h3>
      <p>Learning from humans for generating naturalistic handovers with supernumerary robotic limbs.</p>
      <div class="research-meta">CHI 2025</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/wrlkit/' | relative_url }}">
    <img src="{{ '/images/wrlkit_thumbnail.png' | relative_url }}" alt="WRLKit thumbnail">
    <div class="tile-body">
      <h3>WRLKit</h3>
      <p>Computational design and fabrication of personalized wearable robotic limbs.</p>
      <div class="research-meta">UIST 2023</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/i-need-a-third-arm/' | relative_url }}">
    <img src="{{ '/images/ineedathirdarm_thumbnail.png' | relative_url }}" alt="I Need a Third Arm thumbnail">
    <div class="tile-body">
      <h3>I Need a Third Arm!</h3>
      <p>The impact of supernumerary robotic limbs on human embodiment and behavior.</p>
      <div class="research-meta">CHI 2023</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/moire-curved-surfaces/' | relative_url }}">
    <img src="{{ '/images/fabricationofmoireoncurvedsurfaces_thumbnail.jpg' | relative_url }}" alt="Fabrication of Moiré on Curved Surfaces thumbnail">
    <div class="tile-body">
      <h3>Fabrication of Moiré on Curved Surfaces</h3>
      <p>Computational optics, simulation, and fabrication of moiré on curved surfaces.</p>
      <div class="research-meta">Optics Express 2020</div>
    </div>
  </a>


</div>

## Engineering Projects

<div class="project-catalog">

  <a class="project-tile" href="{{ '/projects/mini-ctorch/' | relative_url }}">
    <img src="https://raw.githubusercontent.com/artin-saberpour/Mini_CTorch/main/py/training_progress.gif" alt="Mini_CTorch thumbnail">
    <div class="tile-body">
      <h3>Mini_CTorch</h3>
      <p>Custom CUDA kernels, matrix multiplication, automatic differentiation, and neural network training.</p>
      <div class="research-meta">C · CUDA</div>
    </div>
  </a>

  <a class="project-tile" href="{{ '/projects/srl-impedance-control/' | relative_url }}">
    <img src="https://github.com/user-attachments/assets/c2939f0f-b13e-4a47-9758-30ae4f98ccca" alt="SRL impedance controller MuJoCo demonstration">
    <div class="tile-body">
      <h3>SRL Impedance Control</h3>
      <p>6-DoF MuJoCo simulation and impedance control for a supernumerary robotic limb.</p>
      <div class="research-meta">Control · Simulation</div>
    </div>
  </a>


  <a class="project-tile" href="https://github.com/artin-saberpour/Kinova-unity-ros2-clik-6d-controller">
    <video autoplay muted loop playsinline preload="metadata" poster="{{ '/images/kinova_simulation.png' | relative_url }}" aria-label="Kinova Unity ROS2 closed-loop inverse kinematics controller demonstration"><source src="https://raw.githubusercontent.com/artin-saberpour/Kinova-unity-ros2-clik-6d-controller/main/rendered_samples/rendered_sample.mp4" type="video/mp4"></video>
    <div class="tile-body">
      <h3>Kinova Unity–ROS2 CLIK Controller</h3>
      <p>Six-dimensional task-space closed-loop inverse kinematics with ROS2 and Unity.</p>
      <div class="research-meta">ROS2 · Unity · Kinematics</div>
    </div>
  </a>
</div>

