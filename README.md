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


## Demos & Interface

<table>
  <!-- Row 1: VR App Demo -->
  <tr>
    <td colspan="2" align="center" valign="top">
      <h4>🖥️ Custom Unity VR App (Teleoperation)</h4>
      <video src="https://github.com/user-attachments/assets/23806e4e-4318-4ccd-b5cc-56ed6c962815" controls width="100%"></video>
      <br>
      <em>Self-developed Unity VR interface.</em>
    </td>
  </tr>
  <!-- Row 2: Two ACT Demos side-by-side -->
  <tr>
    <td width="50%" align="center" valign="top">
      <h4>🤖 ACT Pipeline</h4>
      <video src="https://github.com/user-attachments/assets/51f2aae1-5020-4cb8-a740-58e5d098d9fb" controls width="100%"></video>
      <br>
      <em>Autonomous closed-loop execution.</em>
    </td>
    <td width="50%" align="center" valign="top">
      <h4>🤖 Clean up desk by putting tape and pen into the box</h4>
      <video src="https://github.com/user-attachments/assets/37463f66-bac5-41e2-9261-6ca977a9c7ed" controls width="100%"></video>
      <br>
      <em>Autonomous closed-loop execution.</em>
    </td>
        <td width="50%" align="center" valign="top">
      <h4>🤖 stack cups (alyaws as green cup base)</h4>
      <video src="https://github.com/user-attachments/assets/81f5cf1b-6629-4d63-b849-6b43d33c7934" controls width="100%"></video>
      <br>
      <em>Autonomous closed-loop execution.</em>
    </td>
  </tr>
</table>
