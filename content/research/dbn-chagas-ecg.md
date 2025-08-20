
---
title: "Predicting Chagas Disease from ECG via Dynamic Bayesian Networks"
date: 2025-02-01
tags: ["research", "ml", "healthcare"]
summary: "DBN modeling of temporal ECG wave relationships; recall 0.87 with patient‑level CV."
---

- Engineered interpretable time‑series features (P, QRS, T) via NeuroKit2; anchored windows around R‑peaks.
- Trained with pgmpy; patient‑level CV avoided leakage; best model reached **0.87 recall**.
- Modular Python codebase for future research and clinical screening integration.
