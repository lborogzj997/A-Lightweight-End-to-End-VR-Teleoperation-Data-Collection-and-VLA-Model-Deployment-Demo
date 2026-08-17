
# 🤖 Dual-Arm VR Teleoperation & VLA Pipeline

> **Full-stack dual-arm VR teleoperation, data collection, and VLA deployment pipeline powered by [LeRobot](https://github.com/huggingface/lerobot).**

This project is a hands-on exploration of **Vision-Language-Action (VLA)** architectures for dual-arm manipulation. It features a **custom Unity VR app**, a controller powered by Pinocchio**, and a lightweight **ACT** policy deployment pipeline via LeRobot.

---

## ✨ Features

- **Custom Unity VR App**: Self-developed VR teleoperation interface for intuitive, low-latency 7-DoF spatial control.
- **Pinocchio Kinematics Engine**: Custom dual-arm robot controller providing linear Cartesian trajectory planning and kinematics resolution via [Pinocchio](https://github.com/stack-of-tasks/pinocchio).
- **LeRobot Ecosystem**: Native integration with Hugging Face LeRobot for standardized dataset logging, training, and policy evaluation.
- **Lightweight ACT Baseline**: Fast, closed-loop policy deployment for initial validation before scaling to larger VLA models.

---


## 🎬 Demos & Interface
<table>
  <tr>
    <td width="35%" align="center" valign="center">
      <h4>🖥️ Custom Unity VR App (Teleoperation)</h4>
      <video src="https://github.com/user-attachments/assets/23806e4e-4318-4ccd-b5cc-56ed6c962815" controls width="100%"></video>
      <br>
      <em>Self-developed Unity VR interface.</em>
    </td>
    <td width="35%" align="center" valign="top">
      <h4>🤖 ACT Policy Demo</h4>
      <video src="https://github.com/user-attachments/assets/51f2aae1-5020-4cb8-a740-58e5d098d9fb" controls width="100%"></video>
      <br>
      <em>Autonomous closed-loop execution.</em>
    </td>
  </tr>
</table>


