---
title: "Energy‑Optimized LLVM via RL Pass Ordering"
date: 2025-08-20
tags: ["project"]
summary: "Python, LLVM, CompilerGym, PyTorch"
---

- Reinforcement learning to optimize LLVM pass sequences for code size and static energy proxies.
- PPO agents trained with static reward combining energy and size; outperformed -O3/-Oz on several benchmarks.
- Custom static energy model based on ARM Cortex‑A7 assembly + IR analysis.
