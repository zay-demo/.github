<div align="center">

<!-- SpacemiT Official Logo -->
<a href="https://www.spacemit.com">
  <img src="https://files.seeusercontent.com/2026/09/28/7aSv/logosquare1.png" alt="SpacemiT Logo" width="260" onerror="this.src='https://www.spacemit.com/favicon.ico'; this.width=64;"/>
</a>

# RISC-V Architecture for an Intelligent Future

<p align="center">
  <b>High-performance RISC-V SoCs powering On-Device AI Agents and Embodied Robotics.</b><br>
  Zero Cloud Latency • Deterministic Privacy • Upstream Mainline Native
</p>

<!-- Ecosystem & Architecture Badges -->
<p align="center">
  <a href="https://riscv.org/"><img src="https://img.shields.io/badge/ISA-RISC--V%20(RVA23%20%2B%20Vector%201.0)-blue?style=flat-square&logo=riscv&logoColor=white" alt="RISC-V"></a>
  <a href="https://www.kernel.org/"><img src="https://img.shields.io/badge/Linux%20Kernel-Mainline%20Supported-success?style=flat-square&logo=linux&logoColor=white" alt="Linux"></a>
  <img src="https://img.shields.io/badge/Toolchain-GCC%20%7C%20LLVM%20Upstream-orange?style=flat-square" alt="Toolchain">
  <img src="https://img.shields.io/badge/Silicon-K1%20%7C%20K3%20SoCs-blueviolet?style=flat-square" alt="Hardware">
  <a href="https://discord.gg/spacemit"><img src="https://img.shields.io/badge/Community-Discord-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://docs.spacemit.com">Documentation</a> •
  <a href="#-silicon-matrix">Product Matrix</a> •
  <a href="https://github.com/spacemit-robotics">Robotics Hub</a> •
  <a href="#-open-source-stack">Software Stack</a> •
  <a href="https://forum.spacemit.com">Community</a>
</p>

</div>

---

### 🌐 About SpacemiT

SpacemiT builds next-generation RISC-V compute processors designed for demanding edge workloads. Our SoCs integrate high-throughput computing cores, standard vector extensions (RVV 1.0), and dedicated neural acceleration directly onto silicon — enabling **100% on-device AI execution** without recurring cloud API fees or network latency penalties.

> **Upstream-First Engineering**  
> We actively contribute to open-source foundation projects. Both **K1** and **K3** are supported in **mainline Linux**, standard **GCC**, **LLVM**, and **Binutils**. No proprietary toolchains, no obsolete custom forks — standard distribution packages from Debian, Ubuntu, and Fedora work out of the box.

---

### 🚀 Target Applications

<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI Agent Computer
*An always-local intelligence core for edge hardware.*

Think of it as a Raspberry Pi-class platform running generative LLMs and multimodal vision natively — serving as your product's local brain with deterministic privacy and instant execution.

**Capabilities out of the box:**
- **Local LLMs & Tool Use**: Native quantized chat models and autonomous function-calling (Qwen, DeepSeek, Llama, GLM) via OpenAI-compatible endpoints.
- **Multimodal Vision**: Real-time high-FPS detection, tracking, instance segmentation, and pose estimation.
- **Conversational Voice**: Full offline edge pipeline: Wake-Word → VAD → ASR → On-device LLM reasoning → TTS.
- **Multi-Agent Loops**: Autonomous local tasks with peripheral sensor input.

👉 **[Explore AI Agent Repositories →](https://github.com/spacemit-com)**

</td>
<td width="50%" valign="top">

### 🦾 AI Robot & Embodied Intelligence
*A complete edge-compute robotics platform driven by K3.*

From sensory perception to dynamic motor trajectory generation, K3 delivers the heterogeneous compute required for high-frequency motion loops, SLAM, and policy execution directly on the bot.

**Capabilities out of the box:**
- **Imitation Learning & Manipulation**: Direct execution of behavioral cloning policies (ACT, SmolVLA).
- **Humanoid & Quadruped Control**: Low-latency Reinforcement Learning (RL) whole-body control policies.
- **Spatial Autonomy**: Real-time Visual-Inertial SLAM, point cloud processing, and onboard path planning.
- **Sim-to-Real Pipeline**: Zero-overhead transitions from MuJoCo physics simulation to K3 bare metal.

👉 **[Explore Robotics Demos & SDKs →](https://github.com/spacemit-robotics)**

</td>
</tr>
</table>

---

### ⚡ Product Matrix

| CPU | Form Factors & Segments | Architecture & Highlights | Primary Repositories |
| :--- | :--- | :--- | :--- |
| **SpacemiT K1** | Single-board Computers, Edge AI Gateways, Smart Displays | 8-core RISC-V (RVA22), 2.0 TOPS NPU, RISC-V Vector 1.0 support | Linux BSP, Muse-Pi OS, NPU Toolchain |
| **SpacemiT K3** | Embodied AI, Humanoids, Quadrupeds, Robotic Arms | High-throughput Heterogeneous Compute, High-bandwidth Vision/Sensory I/O | [spacemit-robotics](https://github.com/spacemit-robotics), MuJoCo-to-K3 Runtime |

---

<div align="center">

### 🤝 Join the Ecosystem

Whether you are bringing up a custom board, packaging an operating system, or building autonomous robots, we welcome your feedback, issues, and pull requests.

[Official Website](https://www.spacemit.com) • [Documentation](https://docs.spacemit.com) • [Buy Hardware](https://shop.spacemit.com) • [Community Forum](https://forum.spacemit.com)

</div>
