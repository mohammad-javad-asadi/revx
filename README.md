<div align="center">

  <img width="240" height="203" alt="new_logo" src="https://github.com/user-attachments/assets/d9d67d10-179b-4f31-add1-3ac8283ebcdc" style="mix-blend-mode: screen;" />
  
  <h1 style="font-size: 2.8em; font-weight: 800; margin-bottom: 5px; letter-spacing: -1px;">REVX</h1>
  <code>Low-Latency System & Workstation Optimizer</code>
</div>

<br />

## Table of Contents

**1.** [**About RevX**](#about-revx)  
**2.** [**How it works?**](#how-it-works)  
**3.** [**Key Performance Tweaks**](#key-performance-tweaks)  
**4.** [**🧠 CPU Optimization Architecture**](#-cpu-optimization-architecture)  
**5.** [**🎮 GPU & Graphics Optimization Suite**](#-gpu--graphics-optimization-suite)  
**6.** [**💾 Memory & Storage Pipeline Tweak**](#-memory--storage-pipeline-tweaks)  
**7.** [**🌐 Advanced TCP/IP & Network Optimizer**](#-advanced-tcpip--network-optimizer)  
**8.** [**⚡ Built-in Network Diagnostic Tools**](#-built-in-network-diagnostic-tools)  
**9.** [**Workstation & Rendering Boost**](#workstation--rendering-boost)  
**10.** [**Installation & Safety**](#installation--safety)  
**11.** [**Configuration**](#configuration)  
**12.** [**License**](#license)

<br />
<div align="center">
  <a href="https://github.com/mohammad-javad-asadi/revx/releases/latest"><img src="https://img.shields.io/badge/Download-Stable-green?style=for-the-badge&logo=github&logoSize=auto" alt="Stable release"></a>
  <img src="https://img.shields.io/badge/Status-100%25_Free-brightgreen?style=for-the-badge&logo=github" alt="Free Status">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
</div>

## About RevX

**RevX** is a low-latency, high-responsiveness Windows system optimizer designed specifically for gamers, power users, and 3D digital artists. It completely eliminates unnecessary OS resource hogging to stabilize your system's performance.

> [!WARNING]
> **The Ugly Truth About Traditional Optimizers:** > Most generic optimizers on GitHub or the market are filled with **fake claims**, or worse—they blindly apply destructive registry hacks and forced overclocks that can **permanently damage your hardware, trigger thermal throttling, or cause random Blue Screens (BSOD).** At best, they do absolutely nothing; at worst, they ruin your system stability because they are not tailored to your specific machine.

> [!NOTE]
> **The RevX Difference (Hardware-Aware Dynamic Tuning):**
> RevX doesn't use dangerous "one-size-fits-all" scripts. Our engine deeply analyzes your exact rig before applying a single tweak. It detects whether you are on a **Desktop PC** or a **Laptop**, calculates your system's **Thermal Capacity**, and intelligently tunes frame pacing, input latency, network stability, and power efficiency without pushing your hardware to unsafe limits.

> [!IMPORTANT]
> * **RevX is 100% FREE and Open-Source.** We do not have any premium tiers, hidden paywalls, or subscription models. 
> * **Beware of Scams:** Any website or app charging money for RevX is a fraudulent copy. Only download from this official GitHub repository.

---

## How it works?
Windows defaults are heavily cluttered with background telemetry, severe power throttling, and inefficient scheduling. **RevX** applies targeted, low-level kernel and service tweaks to bypass default OS bottlenecks, allowing your hardware to work directly for your active applications.

<div align="center">

  ![RevX Interface](آدرس_آپلود_عکس_محیط_برنامه)

</div>

---

## Key Performance Tweaks

### 🎮 Gaming & Latency (Absolute Frame Stability)
- **Micro-Stutter Elimination:** Dynamically adjusts thread priority to ensure your CPU focuses entirely on the active game, dramatically stabilizing **1% Low FPS**.
- **Input Lag Reduction:** Tunes Windows timer resolutions to the absolute lowest safe limits, resulting in instant mouse and keyboard responses.
- **Network Packet Shaping:** Optimizes network throttling indexes and SMBv3 protocols to eliminate bufferbloat, ensuring a rock-solid, stable ping in online matches.

### 🔋 Battery & System Responsiveness
- **Next-Gen Battery Optimizer:** Deeply suspends hidden background telemetry, indexing services, and aggressive Windows updates while on battery, potentially **doubling your laptop runtime**.
- **Smart OS Decrapifier:** Safely flushes system font caches, corrupted registry entries, and icon cache artifacts without breaking core Windows security or Windows Update.

---

## 🧠 CPU Optimization Architecture

RevX features an advanced, low-level CPU tuning suite engineered to bypass legacy OS clipping limits, flatten DPC latency spikes, and clean hardware runtime jitter. Below is the comprehensive technical breakdown of our core kernel features:

### ⚡ Windows Timer Resolution
* **Technical Operation:** Forces the Windows kernel to update its internal clock more frequently.
* **System Impact:** Drastically reduces frame pacing issues and minimizes input delay for razor-sharp competitive gaming.
* **Core Benefit:** Minimizes input delay & system latency.

### 🔋 Disable Windows Power Throttling
* **Technical Operation:** Bypasses Windows energy-saving algorithms that artificially limit CPU thread performance.
* **System Impact:** Ensures maximum sustained clock speeds and raw power during heavy workloads and intense gaming sessions.
* **Core Benefit:** Unlocks sustained maximum CPU frequencies.

### ⏱️ Optimize BCD & Synthetic Timers
* **Technical Operation:** Reconfigures fundamental kernel initialization parameters to strip away artificial OS timing layers and legacy diagnostic overhead.
* **System Impact:** Forces direct hardware synchronization to aggressively neutralize deep DPC latency spikes, ensuring flawless frame pacing without relying on emulated software clocks.
* **Core Benefit:** Strips artificial timing layers to neutralize DPC latency spikes.

### 🚀 Dynamic Foreground Priority
* **Technical Operation:** Systematically demotes non-essential services, updaters, and bloatware to the absolute lowest CPU priority (Idle).
* **System Impact:** Aggressively suffocates background noise while mathematically shielding critical OS tasks, guaranteeing your active application undisputed processor access.
* **Core Benefit:** Demotes background bloatware to Idle for undisputed CPU access.

### 🧬 NT Kernel Execution Optimization
* **Technical Operation:** Dynamically calibrates thread scheduling quantums based on your specific CPU core topology.
* **System Impact:** Restructures kernel-level cache allocation and hardware interrupt processing to bypass default OS limits.
* **Core Benefit:** Calibrates kernel scheduling & cache architecture for max CPU throughput.

### 💎 Intel Anti-Jitter & Execution Optimizer
* **Technical Operation:** Terminates hidden hardware-level diagnostic polling and embedded analytics engines.
* **System Impact:** Eliminates random CPU micro-stutters and injects custom boot-level flags to forcefully unlock advanced instruction pipelines for faster context switching and multi-threaded rendering.
* **Core Benefit:** Eliminates CPU micro-stutters & unlocks raw execution speed.

### ⚡ Enable Intel® TSX Instructions
* **Technical Operation:** Unlocks Transactional Synchronization Extensions on supported Intel architectures.
* **System Impact:** Accelerates hardware-level lock-free multi-threading execution for highly complex simulations and intense multitasking applications.
* **Core Benefit:** Hardware-level multi-threading acceleration.

### 🌐 Modernize Network Protocol (SMBv3)
* **Technical Operation:** Disables obsolete, CPU-heavy legacy network protocols (SMBv1/v2).
* **System Impact:** Enforces modern SMBv3 routing to harden system security against structural vulnerabilities while significantly cutting down raw CPU overhead during network polling.
* **Core Benefit:** Reduces network CPU overhead & hardens security.

---

## 🎮 GPU & Graphics Optimization Suite

RevX implements deep pipeline optimizations directly addressing graphics drivers, DRM subsystems, and runtime display architectures to secure low frame-time variance and instantaneous frame dispatch.

### ⚡ Enable PCIe MSI (Message Signal Interrupts)
* **Technical Operation:** Forces the GPU to communicate directly via high-speed PCIe memory writes instead of outdated hardware interrupt lines.
* **System Impact:** Aggressively slashes device-to-CPU latency, resulting in instantaneous input response and the eradication of frame micro-stutters.
* **Core Benefit:** Slashes hardware latency for instantaneous input response.

### 🚀 Optimize MMCSS Game Priority
* **Technical Operation:** Re-calibrates execution thresholds within the Windows Multimedia Class Scheduler (MMCSS).
* **System Impact:** Aggressively overrides standard OS resource limits and enforces strict hardware prioritization to suffocate background interference.
* **Core Benefit:** Locks maximum system resources for uninterrupted 3D rendering.

### 🔒 Disable NVIDIA HDCP
* **Technical Operation:** Slices through background DRM encryption protocols that constantly monitor your display pipeline.
* **System Impact:** Bypasses cryptographic handshakes to lighten the GPU frame buffer processing weight, ensuring a pure, low-latency signal to your monitor.
* **Core Benefit:** Strips display DRM to minimize frame buffer latency.

### 🛑 Disable NVIDIA Telemetry
* **Technical Operation:** Ruthlessly terminates background diagnostic endpoints, hidden Node.js instances, and driver tracking services.
* **System Impact:** Reclaims valuable CPU cycles and network bandwidth hijacked by driver bloatware while ensuring absolute privacy.
* **Core Benefit:** Reclaims CPU cycles hijacked by background driver bloatware.

### 🏎️ NVIDIA Driver Pipeline Optimization
* **Technical Operation:** Injects low-level parameters directly into the NVIDIA Kernel Mode Driver (`nvlddmkm`).
* **System Impact:** Enforces round-robin DPC distribution across all CPU cores and enables asynchronous context preemption to bypass standard render queues.
* **Core Benefit:** Minimizes pipeline latency for immediate frame dispatch.

### 🛠️ Disable AMD ULPS & Optimize ADLX
* **Technical Operation:** Hooks into the advanced ADLX framework to bypass standard Radeon software limits.
* **System Impact:** Disables Ultra-Low Power State (ULPS) to prevent micro-sleeps during gameplay and forces aggressive compute-mode shader dispatching.
* **Core Benefit:** Disables power limits for maximum compute-mode frame generation.

### 🌐 Optimize DirectX & DXGI Runtime
* **Technical Operation:** Injects deep modifications into the DirectX Graphics Infrastructure (DXGI) and `DXGKRNL`.
* **System Impact:** Enforces optimized swap-chain pipelines, enables D3D12 runtime dynamic codegen, and strictly strips legacy software emulation and debug layers.
* **Core Benefit:** Optimizes swap-chains for minimum rendering overhead.

### 🛡️ Bypass Windows GPU Watchdog (TDR)
* **Technical Operation:** Disables the Windows Timeout Detection and Recovery (TDR) mechanism.
* **System Impact:** Neutralizes the OS-level watchdog to prevent Windows from forcefully resetting the GPU driver during intensive rendering or locked P-State workloads.
* **Core Benefit:** Stops OS interruptions to reduce latency.

### 💎 Update & Optimize DLSS / FG
* **Technical Operation:** Bypasses outdated DLSS files included in the game folder and forces the engine to target the driver's latest runtimes directly.
* **System Impact:** Enforces the most optimized DLSS (SR), Frame Generation (DLSS-G), and Ray Reconstruction (RR) algorithms to improve image stability and optimize Tensor Core scheduling.
* **Core Benefit:** Updates DLSS to reduce ghosting & artifacts.

### 🎛️ RevX Advanced Graphics Profiles
Includes built-in preset configurations directly interfacing with core driver parameters:
* **`NVIDIA Profile`:** Direct mapping of optimal e-sports and workstation layout flags.
* **`RevX Cool`:** Thermal-aware profiles focusing on keeping temperatures down without dropping core performance thresholds.
* **`Max Boost`:** Unshackles hardware power limits for raw, uninterrupted execution delivery.

---

## 💾 Memory & Storage Pipeline Tweaks

Unclogs structural I/O lanes, manages system memory topologies dynamically, and ensures ultra-fast asset loading directly from modern storage setups.

### 🧠 Dynamic Memory Topology Profiler
* **Technical Operation:** Deploys an intelligent algorithmic check of physical RAM capacity to auto-scale Windows memory management parameters.
* **System Impact:** Dynamically toggles memory compression, scales I/O page lock limits, and forces core kernel paging execution based on your hardware tier.
* **Core Benefit:** Eradicates memory bottlenecks and micro-stutters dynamically.

### ⚙️ Disable SysMain & Predictive Caching
* **Technical Operation:** Completely terminates the `SysMain` (Superfetch) service and strictly restricts the Windows Prefetcher to boot-only tasks.
* **System Impact:** Disables predictive background RAM caching, auto-layout algorithms, and idle disk defragmentation to stop intrusive system interruptions during execution.
* **Core Benefit:** Reclaims valuable physical memory allocations and absolutely eliminates random disk I/O spikes.

### ⚡ NVMe Driver Latency Override
* **Technical Operation:** Injects low-level parameters directly into the native storage stack driver profiles.
* **System Impact:** Expands Host Memory Buffer (HMB) allocations and completely bypasses mandatory OS device access queries to establish an open, direct channel for raw asset data.
* **Core Benefit:** Forces maximum I/O speed for immediate 3D texture and asset loading.

### 📂 NTFS Protocol Streamlining
* **Technical Operation:** Modifies core NTFS file system registry and initialization flags.
* **System Impact:** Disables on-the-fly file compression, active background driver encryption, legacy 8.3 short-name generation, and constant last-access timestamp writes.
* **Core Benefit:** Reclaims valuable CPU file-system polling cycles and guarantees maximum raw data throughput.

### ❌ Disable Legacy NTFS Tunneling
* **Technical Operation:** Shrinks the NTFS tunneling cache queue to its absolute minimum limits.
* **System Impact:** Disables an outdated backward-compatibility subsystem that continuously memorizes metadata during high-frequency file deletion and recreation loops.
* **Core Benefit:** Eliminates redundant storage tracking overhead during heavy data streaming workloads.

---

## 🌐 Advanced TCP/IP & Network Optimizer

Overrides default conservative Windows networking heuristics to stabilize package distribution and remove packet queue delays.

### 🚀 Remove Network Bandwidth Limits
* **Technical Operation:** Removes the artificial QoS packet scheduler bandwidth caps reserved by default Windows policies.
* **System Impact:** Allows the connection pipeline to utilize the absolute maximum available throughput of your network adapter.
* **Core Benefit:** Unlocks unthrottled networking bandwith.

### 📡 Network Packet Throttling Override
* **Technical Operation:** Recalibrates thresholds within the Windows Multimedia System Profile network variables.
* **System Impact:** Overrides how the OS shifts CPU focus between active network adapter interrupts and raw 3D rendering execution loops under load.
* **Core Benefit:** Stabilizes packet delivery pacing to completely prevent random ping spikes.

### ⚡ Advanced TCP/IP Stack Override
* **Technical Operation:** Reconstructs the network architecture stack variables by forcing modern network congestion control algorithms and multi-core packet scaling.
* **System Impact:** Enforces immediate packet dispatching (Nagle's Algorithm bypass) and shuts down legacy heuristic monitoring.
* **Core Benefit:** Eliminates data transmission delays and ensures a rock-solid ping for competitive multi-player interaction.

---

## ⚡ Built-in Network Diagnostic Tools

RevX comes equipped with integrated performance benchmark utilities directly available within the network dashboard, ensuring your connectivity tweaks are fully verified:

* **⚡ Best DNS Benchmark Engine:** Performs ultra-low overhead handshake queries to top tier global DNS providers (Cloudflare, Google, NextDNS, Quad9) to identify and automatically apply the absolute lowest latency provider for your location.
* **🌐 Integrated Ookla Speedtest Client:** Hooks directly into the official Ookla network API, allowing you to fetch true download speeds, upload speeds, and connection jitter benchmarks natively without heavy web-browser processing overhead.
* **🎮 Live Game Ping Diagnostic Matrix:** Continuously profiles live ICMP routes and latency pacing to major competitive multiplayer datacenters (Valve/Steam, Riot Games, Epic, Blizzard) to verify your packet shaping modifications.

---

## Workstation & Rendering Boost

RevX isn't just for gaming. If you are working on heavy 3D rendering, video editing, or software development, RevX unlocks maximum hardware throughput:
- **Unleashed RAM/CPU Cycles:** Cleans up active system overhead before launching heavy tasks.
- **Improved Workstation Fluidity:** Keeps viewport navigation responsive in software like Blender, Maya, or Premiere Pro by optimizing background memory page filing.

<div align="center">

  ![Performance Graph](آدرس_آپلود_عکس_نمودار_یا_تست)

</div>

---

## Installation & Safety

> [!CAUTION]
> **Online Anti-Cheat Notice:** While RevX is clean and safe, applying deep low-level system tweaks can sometimes be flagged by highly sensitive anti-cheat engines (e.g., Vanguard, FaceIt) if run simultaneously. We recommend applying tweaks and restarting your PC before launching heavily monitored competitive multiplayer games.

### Prerequisites
* **Supported OS:** Windows 10 & Windows 11 (Fully optimized for latest builds)
* **Access:** Administrator Privileges required to modify system services.

### Instructions
1. Download the latest stable release from the [Releases](https://github.com/mohammad-javad-asadi/revx/releases) tab.
2. Extract the archive and launch the dashboard.
3. Select your desired performance or utility mode and apply the tweaks with a single click.

---

## Configuration
Please check the built-in documentation inside the dashboard or check our upcoming `Config.md` guide for full breakdowns of advanced flags and personalized hardware overrides.

---

## License
This project is licensed under the **MIT License** - meaning you are completely free to use, modify, and distribute the software.
