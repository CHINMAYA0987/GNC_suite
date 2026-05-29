<div align="center">

# Autonomous Systems Simulation Suite

**A modular collection of planners, controllers, localizers, and guidance laws — implemented in Python.**

Built for autonomy engineers and researchers who want clean, visual, and extensible implementations of core autonomous vehicle algorithms.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

</div>

---

## * Design Philosophy

Every module in this suite is intentionally built around four principles:

| Principle | Description |
|-----------|-------------|
|  **Readable** | Clean, well-commented code — math-first, optimization-second |
|  **Modular** | Zero hardcoding; swap any planner or controller across pipelines |
|  **Extendable** | OOP foundations make adding new algorithms or research variants straightforward |
|  **Visualizable** | Built-in simulation scripts for intuitive, visual understanding of system behavior |

---

## * Modules

### - Planners
> *Coming soon*

---

### - Controllers
> *Coming soon*

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
