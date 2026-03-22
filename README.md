# 🚁 Corrosion Scan UAV (MATLAB)

This repository hosts a high-fidelity **Autonomous Drone Navigation** system designed for automated corrosion detection on industrial structures. It integrates flight control, environmental sensing, and an inspection modeling pipeline within a MATLAB-based simulation.

## 🚀 Project Overview
The primary goal of this system is to enable a UAV to autonomously navigate complex environments detect structural corrosion using computer vision, and maintain a safe flight trajectory using specialized control logic.

## 🛠️ Tech Stack
* **Software:** MATLAB, Simulink
* **Toolboxes:** Robotics System Toolbox, Reinforcement Learning Toolbox

## 🧩 Key Features
* **Autonomous Navigation:** Waypoint following and trajectory optimization for systematic surface scanning.
* **RL Environment:** A custom Reinforcement Learning environment (`rl_env`) for training flight agents to handle varying wind conditions.
* **Corrosion Detection Logic:** Integration of sensing and inspection modeling to identify and tag corrosion spots in real-time.
* **Flight Control:** Robust flight logic handling stability and obstacle avoidance.

## 📂 Project Structure
* `/drone_logic`: Core control algorithms and flight stability models.
* `/rl_env`: Custom MATLAB scripts defining the Reinforcement Learning environment and training parameters.
* `/script`: Utility scripts for data logging and simulation initialization.
* `README.md`: Project documentation.

## 🏁 Getting Started

### Prerequisites
* MATLAB (R2021b or later recommended)
* Simulink
* Aerospace and Reinforcement Learning Toolboxes

