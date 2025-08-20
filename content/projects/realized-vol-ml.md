---
title: "Low‑Latency Realized Volatility Pipeline"
date: 2025-08-20
tags: ["project"]
summary: "Python, PyTorch, CUDA/C++, ONNX, Polars, FastAPI, NumPy, Typer"
---

- End‑to‑end pipeline: data ingest → training → ONNX export → FastAPI inference (JSON + binary NumPy).
- Custom CUDA kernel for RMSPE loss (~2× faster); ~11× throughput improvement on binary endpoint.
- Lightweight Transformer (~400K params) with AMP and Torch 2.0 compile for speed.
