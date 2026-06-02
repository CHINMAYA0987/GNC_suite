<div align="center">

# Autonomous Systems Simulation Suite

**A modular collection of planners, controllers, localizers, and guidance laws — implemented in Python.**

Built for autonomy engineers and researchers who want clean, visual, and extensible implementations of core autonomous vehicle algorithms.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

</div>

---



## * Modules

### - Planners

#### RRT
<img width="720" height="406" alt="RRT_planner" src="https://github.com/user-attachments/assets/925b9bd1-defc-43bc-babe-0d5554bb4953" />


#### Bug
<img width="720" height="406" alt="bug_planner" src="https://github.com/user-attachments/assets/7190275a-8b3a-47f3-b17e-20a43d3f12de" />


#### A-Star
<img width="720" height="406" alt="a_star" src="https://github.com/user-attachments/assets/14a03baf-1fef-4618-bec4-536923b7deb6" />

#### PRM
<img width="720" height="406" alt="PRM" src="https://github.com/user-attachments/assets/ed49735c-eae2-4279-9467-511db61fc368" />


---

### - Controllers

#### Carrot Chase
<img width="720" height="406" alt="carrot_chase_control" src="https://github.com/user-attachments/assets/c8645f00-8b3b-4fa5-9f48-f4778fd375c8" />

#### Pure Pursuit
<img width="720" height="406" alt="pure_pursuit_control" src="https://github.com/user-attachments/assets/2f0b37b6-a577-4940-903a-3e6ab3b5e9a4" />

#### LQR Control
<img width="720" height="406" alt="lqr_controller" src="https://github.com/user-attachments/assets/ea7c580d-f247-4292-a46c-ab87e1bd90c4" />

#### MPC Control
<img width="720" height="406" alt="MPC_controller" src="https://github.com/user-attachments/assets/97bab039-6c86-454c-9d19-7e4a719c8935" />


---

### - Guidance Laws

Implementations of classical and modern guidance laws for pursuit and interception problems.

#### Pure Pursuit Navigation (PPN)

> Pursuer always points directly at the target. Simple, effective, and widely used in missile guidance and robotics.

<p align="center">
  <img width="720" height="406" alt="Pure Pursuit Navigation" src="https://github.com/user-attachments/assets/d6003493-dd42-42ac-80d8-ab648229ebab" />
</p>

---

#### True Proportional Navigation (TPN)

> Pursuer steers proportional to the line-of-sight rotation rate. More efficient trajectories and better energy use than PPN.

<p align="center">
  <img width="720" height="406" alt="True Proportional Navigation" src="https://github.com/user-attachments/assets/afa4cd16-210f-41a6-851e-851150fd3e0f" />
</p>

---

#### PPN vs TPN — Side-by-Side Comparison

<p align="center">
  <img width="578" height="207" alt="TPN vs PPN Comparison" src="https://github.com/user-attachments/assets/0fa99db7-ab47-45fc-9c80-5fd6930b8108" />
</p>

<div align="center">

| Feature | PPN | TPN |
|--------|-----|-----|
| Steering basis | Direct line-of-sight angle | LOS rotation rate |
| Trajectory efficiency | Moderate | High |
| Implementation complexity | Low | Medium |
| Typical use case | Robotics, drones | Missile guidance |

</div>

---

### - Localizer
> *Coming soon*

---


## * Contributing

Contributions, bug reports, and algorithm suggestions are welcome! Feel free to open an issue or submit a pull request.

---

<div align="center">
  <sub>Built with ❤️ for the autonomy engineering community</sub>
</div>
