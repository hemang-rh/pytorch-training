# PyTorch GPU Training Demo on OpenShift AI

This repository demonstrates how to run a **synthetic PyTorch training job** on Red Hat OpenShift AI using GPU nodes.  
It’s designed to help validate GPU utilization, scaling, and training efficiency across **1–N GPUs**, with tunable parameters and live utilization sampling.

---

## ✨ Features

- **Self-contained synthetic training** (no data download)
- **Multi-GPU aware** (auto-detects GPUs, uses DataParallel)
- **Progress bar per epoch** with live throughput and loss
- **Tunable workload intensity** for benchmarking
- **GPU utilization + memory metrics** saved to `/mnt/data/gpu_samples.csv`
- **Explains constant GPU memory behavior**
- **Ready for OpenShift AI Jupyter Workbench**

---
