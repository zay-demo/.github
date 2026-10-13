<div align="center">

<!-- Banner 图建议比例 3:1 或 4:1，放置于本仓库的 assets 目录 -->
<img src="https://raw.githubusercontent.com/spacemit-robotics/.github/main/assets/banner.png" alt="SpacemiT Banner" width="100%" onerror="this.style.display='none'"/>

# RISC-V Architecture for an Intelligent Future

<p align="center">
  <b>High-performance RISC-V SoCs powering On-Device AI Agents and Embodied Robotics.</b><br>
  Zero Cloud Latency • Full Privacy • True Upstream Mainline
</p>

<!-- 核心技术与生态徽章 -->
<p align="center">
  <img src="https://img.shields.io/badge/Architecture-RISC--V%20(RVA22%2BVector)-blue?style=flat-square&logo=riscv&logoColor=white" alt="RISC-V">
  <img src="https://img.shields.io/badge/Linux%20Kernel-Mainline%20Supported-success?style=flat-square&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Toolchain-GCC%20%7C%20LLVM%20Upstream-orange?style=flat-square" alt="Toolchain">
  <img src="https://img.shields.io/badge/Hardware-K1%20%7C%20K3%20SoCs-blueviolet?style=flat-square" alt="Hardware">
</p>

<p align="center">
  <a href="https://docs.spacemit.com">📖 开发者文档</a> •
  <a href="#-silicon-matrix">⚡ 芯片规格</a> •
  <a href="https://github.com/spacemit-robotics">🦾 机器人仓库</a> •
  <a href="https://forum.spacemit.com">💬 社区论坛</a>
</p>

</div>

---

### 🌐 About SpacemiT (进迭时空)

SpacemiT builds next-generation RISC-V processors designed for compute-intensive edge workloads. Our SoCs bring high-performance computing, vector acceleration, and neural processing directly onto silicon, enabling **100% on-device AI execution** without recurring cloud API bills or network latency.

> **Our Upstream-First Philosophy**  
> We actively contribute to and respect the open-source ecosystem. Both **K1** and **K3** are supported in **mainline Linux**, standard **GCC**, **LLVM**, and **Binutils**. No proprietary closed toolchains, no broken custom kernels — your standard Linux distribution toolchain simply works out of the box.

---

### 🚀 Two Core Applications

<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI Agent Computer
*An always-local intelligence core for edge systems.*

Think of it as a Raspberry Pi-class board running LLMs and multimodal vision natively — serving as your product's local brain with deterministic privacy and zero API costs.

**What you can build today:**
- **Local LLM & Tool Use**: Native chat and agentic function calling (Qwen, DeepSeek, Llama, GLM) via OpenAI-compatible endpoints.
- **Multimodal Vision Pipeline**: High-fps detection, real-time tracking, instance segmentation, and pose estimation.
- **Conversational Voice**: Full edge loop: Wake-word → VAD → ASR → On-device LLM reasoning → TTS.

👉 **[Explore Agent Software & Examples →](https://github.com/spacemit-robotics)**

</td>
<td width="50%" valign="top">

### 🦾 AI Robot & Embodied Intelligence
*A complete edge-compute platform powered by K3.*

From sensor fusion to motor execution, K3 delivers the heterogeneous compute needed for high-frequency motion control, SLAM, and policy inference entirely on-chip.

**What you can build today:**
- **Embodied Manipulation**: Deploy imitation-learning policies directly on hardware (ACT, SmolVLA).
- **Humanoid Whole-Body Control**: Low-latency Reinforcement Learning (RL) policy inference.
- **Spatial Autonomy**: Real-time Visual SLAM and onboard autonomous navigation.
- **Sim-to-Real Workflow**: Train in MuJoCo simulation and flash straight to K3 hardware.

👉 **[Explore Robotics Demos & Kernels →](https://github.com/spacemit-robotics)**

</td>
</tr>
</table>

---

### ⚡ Silicon Matrix

| SoC | Target Segment | Architecture & Highlights | Key Software Repos |
| :--- | :--- | :--- | :--- |
| **SpacemiT K1** | Single-board Computers, Edge AI Boxes, Intelligent Terminals | 8-core RISC-V (RVA22), 2.0 TOPS NPU, RISC-V Vector 1.0 support | Linux BSP, Muse-Pi OS, NPU Toolchain |
| **SpacemiT K3** | Embodied AI, Humanoids, Quadrupeds, High-payload Robotic Arms | Advanced Heterogeneous Compute, High-bandwidth Vision/Sensory I/O | [spacemit-robotics](https://github.com/spacemit-robotics), MuJoCo-to-K3 |

---

### 🛠️ Open Source Ecosystem Map

* **Kernel & Low-Level Stack**
  * `linux-kernel`: SpacemiT reference kernel trees & patchsets targeting mainline.
  * `uboot` / `opensbi`: Open firmware implementation conforming to RISC-V privileged spec.
* **AI & Acceleration Runtimes**
  * `npu-runtime`: Optimized runtime for on-device quantized model execution.
  * `model-zoo`: Pre-converted weights and benchmark scripts for vision and LLM models.
* **Robotics & Embodied Frameworks**
  * [spacemit-robotics](https://github.com/spacemit-robotics): Complete codebase for robot arm control, SLAM navigation, and humanoid RL deployments.

---

<div align="center">

### 🤝 Join the RISC-V Edge Revolution

Whether you are hacking on a custom board, porting an OS distribution, or building an autonomous robot, we welcome your feedback and pull requests!

[官方网站](https://www.spacemit.com) • [技术文档 Hub](https://docs.spacemit.com) • [购买开发板](https://shop.spacemit.com) • [加入开发者社区](https://discord.gg/spacemit)

</div>
