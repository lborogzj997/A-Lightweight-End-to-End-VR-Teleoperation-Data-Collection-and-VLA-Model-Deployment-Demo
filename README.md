# 🤖 Dual-Arm VR Teleoperation & VLA Pipeline

> **Full-stack dual-arm VR teleoperation, data collection, and VLA deployment pipeline powered by [LeRobot](https://github.com/huggingface/lerobot).**

This project is a hands-on exploration of **Vision-Language-Action (VLA)** architectures for dual-arm manipulation. It features a **custom Unity VR app**, a controller powered by Pinocchio**, and a lightweight **ACT** policy deployment pipeline via LeRobot.

---

## ✨ Features

- **Custom Unity VR App**: Self-developed VR teleoperation interface for intuitive, low-latency 6-DoF spatial control.
- **Pinocchio Kinematics Engine**: Custom dual-arm robot controller providing linear Cartesian trajectory planning and kinematics resolution via [Pinocchio](https://github.com/stack-of-tasks/pinocchio).
- **LeRobot Ecosystem**: Native integration with Hugging Face LeRobot for standardized dataset logging, training, and policy evaluation.
- **Lightweight ACT Baseline**: Fast, closed-loop policy deployment for initial validation before scaling to larger VLA models.

---

## 🏗️ System Overview

```text
[ Custom Unity VR App ] ──(UDP/ROS)──> [ Pinocchio Kinematics Controller ]
                                                 │ (Cartesian/Joint Control)
                                                 ▼
[ Dual-Arm Robot / Sim ] <──(Closed-Loop)─── [ LeRobot (Lightweight ACT) ]
