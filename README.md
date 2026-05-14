# Sonic vs. Eggman: Iron Odyssey (PC Edition)

## Project Overview
This repository contains the official PC port of **Sonic vs. Eggman: Iron Odyssey**, a high-fidelity 3D experience originally architected for high-performance homebrew environments. This version is optimized for Windows and Linux, utilizing a high-integrity decentralized framework to bridge the gap between legacy gaming engines and modern PC hardware.

## Core Technical Architecture
The PC edition maintains the "World Computer" architectural standards while adapting hardware-specific optimizations for standard x86-64 environments.

*   **Engine Integration:** Powered by the **Sovereign-Gateway-Core**, ensuring secure data exchange and autonomous financial operations within the game environment.
*   **Performance Optimization:** Features the "Zero-Stall" initiative, adapted from the **Lumiose Legacy** project to provide low-latency performance on high-frequency PC setups.
*   **Programming Standards:** Core logic is implemented in **Rust** and **C++** for memory safety and hardware-level efficiency, while **Solidity** manages the decentralized asset layer.

## Repository Structure
```text
├── src/
│   ├── main.rs              # Entry point for Rust-based engine core
│   ├── renderer_cxx/        # C++ DirectX 12/Vulkan implementation
│   └── agents/              # Autonomous AI workflows (OpenClaw/Moltbot)
├── assets/
│   ├── box_art/             # 3D Render Art (PC Edition)
│   └── engine_configs/      # Legacy engine optimization profiles
├── contracts/
│   └── Gateway_Core.sol     # Smart contracts for sovereign financial systems
└── docs/
    ├── ARCHITECTURE.md      # Detailed World Computer framework schematics
    └── PORTING_LOG.md       # Notes on transitioning from Project Stellar Plus
    
