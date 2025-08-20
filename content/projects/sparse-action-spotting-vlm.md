---
title: "Sparse Action Spotting with Video‑Language Models"
date: 2025-08-20
tags: ["project"]
summary: "Python, PyTorch, Hugging Face Transformers & TRL"
---

- Fine‑tuned Qwen2‑VL‑2B on SoccerNet v2 one‑minute clips + commentary for sparse highlight detection.
- QLoRA finetuning; token‑level cross‑entropy via TRL SFTTrainer; IoU‑based P/R/F1 evaluation.
- Higher recall (0.40) and F1 (0.11) vs larger Mistral‑7B and OpenAI o4‑mini baselines in our setting.
