<p align="center">
  <img src="./assets/header.svg" alt="Juan Esteban Beron Zapata — Autonomous Aerospace Systems" width="100%">
</p>

<p align="center">
  <a href="https://kosmicplane.github.io"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/juan-esteban-beron"><b>LinkedIn</b></a> ·
  <a href="https://orcid.org/0009-0002-2350-7632"><b>ORCID</b></a> ·
  <a href="mailto:aeroberon@gmail.com"><b>Email</b></a>
</p>

## About

🚀 **Aeronautical Engineering graduate** working on autonomous aerospace systems that must remain useful when conditions depart from nominal assumptions.

My research interests center on **safety-critical control, resilient autonomy, onboard sensing and state estimation, multi-robot systems, and simulation-to-hardware validation**. I am particularly interested in systems that can detect changes in their environment or internal capability, preserve safety, and execute appropriate contingency, reconfiguration, or recovery actions while continuing the mission when feasible.

My work has included UAV and spacecraft testbeds, communication-aware drone swarms, multi-sensor navigation, flight-dynamics modeling, and experimental validation with real hardware.

## Research focus

- 🛡️ **Safety-critical control:** CBF/HOCBF, CLF, MPC, LQR-based funnels, constrained control.
- 🔁 **Resilient autonomy:** contingency preservation, reconfiguration, fault-aware operation, dynamic environments.
- 🤖 **Multi-robot systems:** communication-aware coordination, swarm networking, topology adaptation.
- 📡 **Sensing & state estimation:** IMU/GNSS, VIO/SLAM, embedded sensing, telemetry, sensor fusion.
- 🔬 **Experimental validation:** ROS 2, PX4, Gazebo, Isaac Sim, OptiTrack, Crazyflie, embedded hardware and field testing.

## Selected research & engineering

<details open>
<summary><b>🛡️ Safety & Contingency Certificates — Caltech / AMBER Lab</b></summary>

<br>

[**Repository →**](https://github.com/kosmicplane/Safety-Contingency-Certificates)

Research framework for contingency-aware autonomous landing in dynamic obstacle environments. The work combines **Poisson/PDE-based safety fields, control barrier and Lyapunov methods, MPC, and LQR-tree funnels** to construct safe alternatives while preserving rapid response to changes in the environment.

The framework was evaluated in simulation and hardware experiments, including comparisons between Poisson-based guidance and funnel-based route construction. Formal theoretical validation of the broader contingency framework remains ongoing.

</details>

<details>
<summary><b>📡 SWARMSYM / SNaaS Simulator — KAUST / NetLab</b></summary>

<br>

[**Repository →**](https://github.com/kosmicplane/SNAAS_SYM-SNAAS-Simulator)

A reproducible simulation framework for **communication-aware multi-UAV systems and Swarm Network-as-a-Service (SNaaS)** experiments. It integrates **ROS 2, PX4, Isaac Sim, and NVIDIA Sionna** to study dynamic network topology, SNR/capacity, routing behavior, UAV failures, standby integration, and connectivity recovery.

The work connects vehicle motion and network state so that communication constraints become part of the autonomy problem rather than a separate post-processing layer.

</details>

<details>
<summary><b>🧭 SenDiMoniProg Navigation & Embedded Sensing — National Central University</b></summary>

<br>

[**Repository →**](https://github.com/kosmicplane/SenDiMoniProg-IMU)

ROS 2 embedded sensing and navigation work using **IMU, GNSS, camera/RealSense data, Jetson-class hardware, ESP32 telemetry, and RViz-based monitoring**. The project included distributed sensor integration, field/laboratory testing, and communication-pipeline optimization.

A key systems result was reducing ESP32 → Jetson → server end-to-end telemetry latency from **92 ms to 6 ms** in the tested pipeline.

</details>

<details>
<summary><b>🛰️ Atmospheric Probe Flight Dynamics & Multi-Pitot Sensing — UdeA</b></summary>

<br>

[**Repository →**](https://github.com/kosmicplane/CUBE-SAT-FLIGHT-DYNAMICS-PITOTS)

Flight-dynamics and sensing work for a CubeSat-class atmospheric probe, including **descent modeling, stability analysis, multi-Pitot airspeed-vector sensing, CFD, wind-tunnel calibration, IMU/GPS/Pitot integration, and post-flight trajectory reconstruction**.

The project connected analytical and computational models with physical testing and flight data from the Spaceport America Cup campaign.

</details>

## Technical toolkit

<p>
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white">
  <img src="https://img.shields.io/badge/PX4-2B2B2B?style=flat-square&logo=drone&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/MATLAB-EF6C00?style=flat-square">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
</p>

## Research environments

**Caltech / AMBER Lab** · **KAUST / NetLab** · **National Central University** · **Universidad de Antioquia** · **Universidad Pontificia Bolivariana**

## Beyond engineering

✈️ Flight training & aviation · 🌍 Travel & exploration · 🌲 Nature · 🏊 Swimming & training

---

<p align="center">
  <i>Autonomy is most interesting when the environment stops behaving as expected.</i>
</p>
