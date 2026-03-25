# 🚁 Corrosion Scan UAV (MATLAB)

This project is a simulation of an autonomous drone built to inspect industrial structures for corrosion. The goal is pretty straightforward — get a UAV to fly on its own, scan surfaces, and flag areas that might need attention, all while staying stable and avoiding obstacles.

---

## 🚀 What it does

The drone navigates through a defined environment using waypoints, scans surfaces using a simple inspection model, and marks possible corrosion spots during flight. It’s also trained to handle disturbances like wind using a reinforcement learning setup.

---

## 🛠️ Tech Stack

- MATLAB  
- Simulink  
- Robotics System Toolbox  
- Reinforcement Learning Toolbox  

---

## 🧩 Features

- **Autonomous Navigation**  
  Follows waypoints and adjusts its path to cover surfaces efficiently.

- **Reinforcement Learning Environment**  
  A custom `rl_env` is used to train the drone to deal with things like wind and uncertainty.

- **Corrosion Detection**  
  Includes basic sensing + inspection logic to identify and tag corrosion areas.

- **Flight Control**  
  Handles stability and obstacle avoidance through custom control logic.

---

## 🏁 Getting Started

### Requirements

- MATLAB (R2021b or later recommended)  
- Simulink  
- Aerospace Toolbox  
- Reinforcement Learning Toolbox  

---

## Notes

This is mainly a simulation-focused project meant to explore how autonomous inspection drones might work in real-world industrial scenarios.
